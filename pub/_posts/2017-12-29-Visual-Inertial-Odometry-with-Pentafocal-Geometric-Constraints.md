---
title: "Visual Inertial Odometry with Pentafocal Geometric Constraints"
header:
  teaser: /thumbnails/2017_IJCAS.png
conference: IJCAS
links: 
 - paper: 
   link: /download/papers/2017_IJCAS.pdf
   name: "Paper"
 - video: 
   link: https://youtu.be/24nnjRNjI1k
   name: "Video"
 - bibtex: 
   name: "Bibtex"
excerpt: "We present the sliding-window monocular visual inertial odometry that is accurate and robust to outliers by employing a new observation model grounded on the pentafocal geometric constraints. The previous approaches are dependent on the unknown 3D coordinates of the features to estimate the ego-motion. However, the inaccurate 3D position of the features can lead to poor performance in motion estimation. To overcome these limitations, we utilize the pentafocal geometry relationship between five images as camera observation model, which makes it unnecessary to estimate the 3D position of the features. Furthermore, we apply the pentafocal constraints in the 1-point random sample consensus (RANSAC) algorithm to find incorrect feature correspondences. We demonstrate the effectiveness of the proposed algorithm in two types of experiments: the KITTI driving scene dataset and the EuRoC micro aerial vehicle (MAV) flying dataset, both qualitatively and quantitatively. It shows more accurate state estimation performance compared to the well-known stereo visual odometry algorithm and current state-of-the-art visual inertial odometry methods."
---

{% include youtubePlayer.html id="24nnjRNjI1k" %}

We present the sliding-window monocular visual inertial odometry that is accurate and robust to outliers by employing a new observation model grounded on the pentafocal geometric constraints.
The previous approaches are dependent on the unknown 3D coordinates of the features to estimate the ego-motion.
However, the inaccurate 3D position of the features can lead to poor performance in motion estimation.
To overcome these limitations, we utilize the pentafocal geometry relationship between five images as camera observation model, which makes it unnecessary to estimate the 3D position of the features.
Furthermore, we apply the pentafocal constraints in the 1-point random sample consensus (RANSAC) algorithm to find incorrect feature correspondences.
We demonstrate the effectiveness of the proposed algorithm in two types of experiments: the KITTI driving scene dataset and the EuRoC micro aerial vehicle (MAV) flying dataset, both qualitatively and quantitatively.
It shows more accurate state estimation performance compared to the well-known stereo visual odometry algorithm and current state-of-the-art visual inertial odometry methods.

## Bibtex <a id="bibtex"></a>
```
@inproceedings{kim2017visual,
  author = {Kim, Pyojin and Lim, Hyon and Kim, H Jin},
  title = {Visual Inertial Odometry with Pentafocal Geometric Constraints},
  year = {2017},
  booktitle = {IJCAS},
}
```
