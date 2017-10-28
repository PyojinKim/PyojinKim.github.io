---
title: "Visual Odometry with Drift-Free Rotation Estimation Using Indoor Scene Regularities"
header:
  teaser: /thumbnails/2017_BMVC.png
conference: BMVC
links: 
 - paper: 
   link: /download/papers/2017_BMVC.pdf
   name: "Paper"
 - video: 
   link: https://youtu.be/sC3iiaxBhdw
   name: "Video"
 - bibtex: 
   name: "Bibtex"
---

{% include youtubePlayer.html id="sC3iiaxBhdw" %}

We propose a hybrid visual odometry algorithm to achieve accurate and low-drift
state estimation by separately estimating the rotational and translational camera motion.
Previous methods usually estimate the six degrees of freedom camera motion jointly
without distinction between rotational and translational motion. However, inaccuracy in
the rotation estimate is a main source of drift in visual odometry. We design a hybrid
visual odometry algorithm which separately estimates the rotational and translational
motion to achieve improved accuracy and low drift error. To improve the accuracy of rotational
motion estimation, we exploit orthogonal planar structures, such as walls, floors,
and ceilings, common in man-made environments. We track orthogonal frames with
an efficient SO(3)-constrained mean-shift algorithm, resulting in drift-free rotation estimates.
Based on the absolute camera orientation, we newly propose a way to compute
the translational motion by minimizing the de-rotated reprojection error with the tracked
features. We compare the proposed algorithm with other state-of-the-art visual odometry
methods and demonstrate an improved performance and lower drift error.

## Bibtex <a id="bibtex"></a>
```
@inproceedings{kim2017visual,
  author = {Kim, Pyojin and Coltin, Brian and Kim, H Jin},
  title = {Visual Odometry with Drift-Free Rotation Estimation Using Indoor Scene Regularities},
  year = {2017},
  booktitle = {BMVC},
}
```
