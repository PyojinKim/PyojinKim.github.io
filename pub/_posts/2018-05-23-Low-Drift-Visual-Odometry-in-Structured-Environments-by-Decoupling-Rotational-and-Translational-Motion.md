---
title: "Low-Drift Visual Odometry in Structured Environments by Decoupling Rotational and Translational Motion"
header:
  teaser: /thumbnails/2018_ICRA.png
conference: ICRA
links: 
 - paper: 
   link: /download/papers/2018_ICRA.pdf
   name: "Paper"
 - video: 
   link: https://youtu.be/mt3kbv2TJZw
   name: "Video"
 - poster: 
   link: /download/posters/2018_ICRA_poster.pdf
   name: "Poster"
 - bibtex: 
   name: "Bibtex"
excerpt: "We present a low-drift visual odometry algorithm that separately estimates rotational and translational motion from lines, planes, and points found in RGB-D images. Previous methods estimate drift-free rotational motion from structural regularities to reduce drift in the rotation estimate, which is the primary source of positioning inaccuracy in visual odometry. However, multiple orthogonal planes are required to be visible throughout the entire motion estimation process, otherwise these VO approaches fail. We propose a new approach to estimate drift-free rotational motion jointly from both lines and planes by exploiting environmental regularities. We track the spatial regularities with an efficient SO(3)-manifold constrained mean shift algorithm. Once the drift-free rotation is found, we recover the translational motion from all tracked points with and without depth by minimizing the de-rotated reprojection error. We compare the proposed algorithm to other state-of-the-art visual odometry methods on a variety of RGB-D datasets (including especially challenging pure rotations) and demonstrate an improved accuracy and lower drift error."
---

{% include youtubePlayer.html id="mt3kbv2TJZw" %}

We present a low-drift visual odometry algorithm
that separately estimates rotational and translational motion
from lines, planes, and points found in RGB-D images. Previous
methods estimate drift-free rotational motion from structural
regularities to reduce drift in the rotation estimate, which is the
primary source of positioning inaccuracy in visual odometry.
However, multiple orthogonal planes are required to be visible
throughout the entire motion estimation process, otherwise
these VO approaches fail. We propose a new approach to
estimate drift-free rotational motion jointly from both lines and
planes by exploiting environmental regularities. We track the
spatial regularities with an efficient SO(3)-manifold constrained
mean shift algorithm. Once the drift-free rotation is found, we
recover the translational motion from all tracked points with
and without depth by minimizing the de-rotated reprojection
error. We compare the proposed algorithm to other state-of-
the-art visual odometry methods on a variety of RGB-D
datasets (including especially challenging pure rotations) and
demonstrate an improved accuracy and lower drift error.

## Bibtex <a id="bibtex"></a>
```
@inproceedings{kim2018low,
  author = {Kim, Pyojin and Coltin, Brian and Kim, H Jin},
  title = {Low-Drift Visual Odometry in Structured Environments by Decoupling Rotational and Translational Motion},
  year = {2018},
  booktitle = {ICRA},
}
```
