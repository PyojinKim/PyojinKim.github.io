---
title: "Indoor RGB-D Compass from a Single Line and Plane"
header:
  teaser: /thumbnails/2018_CVPR.png
conference: CVPR
links: 
 - paper: 
   link: /download/papers/2018_CVPR.pdf
   name: "Paper"
 - video: 
   link: https://youtu.be/qusvgMequqM
   name: "Video"
 - bibtex: 
   name: "Bibtex"
excerpt: "We propose a novel approach to estimate the three degrees of freedom (DoF) drift-free rotational motion of an RGB-D camera from only a single line and plane in the Manhattan world (MW). Previous approaches exploit structural regularities to achieve accurate 3-DoF rotation estimation by using the distribution of surface normal vectors and points at infinity, i.e., vanishing points (VPs). However, they require multiple orthogonal planes or a plenty of consistent lines to be visible throughout the entire rotation estimation process; otherwise, these approaches fail. To overcome these limitations, we present a new method that estimates absolute camera orientation from only a single line and a single plane in RANSAC, which corresponds to the theoretical minimal sampling for 3-DoF rotation estimation. Once we find an initial rotation estimate, we refine the camera orientation by minimizing the average orthogonal distance from the endpoints of the inliers (parallel and orthogonal lines). We demonstrate the superiority of the proposed algorithm through an extensive evaluation on a variety of RGB-D datasets and compare with other state-of-the-art methods."
---

{% include youtubePlayer.html id="qusvgMequqM" %}

We propose a novel approach to estimate the three degrees
of freedom (DoF) drift-free rotational motion of an
RGB-D camera from only a single line and plane in the
Manhattan world (MW). Previous approaches exploit structural
regularities to achieve accurate 3-DoF rotation estimation
by using the distribution of surface normal vectors
and points at infinity, i.e., vanishing points (VPs). However,
they require multiple orthogonal planes or a plenty of
consistent lines to be visible throughout the entire rotation
estimation process; otherwise, these approaches fail. To
overcome these limitations, we present a new method that
estimates absolute camera orientation from only a single
line and a single plane in RANSAC, which corresponds to
the theoretical minimal sampling for 3-DoF rotation estimation.
Once we find an initial rotation estimate, we refine
the camera orientation by minimizing the average orthogonal
distance from the endpoints of the inliers (parallel and
orthogonal lines). We demonstrate the superiority of the
proposed algorithm through an extensive evaluation on a
variety of RGB-D datasets and compare with other state-of-
the-art methods.

## Bibtex <a id="bibtex"></a>
```
@inproceedings{kim2018indoor,
  author = {Kim, Pyojin and Coltin, Brian and Kim, H Jin},
  title = {Indoor RGB-D Compass from a Single Line and Plane},
  year = {2018},
  booktitle = {CVPR},
}
```
