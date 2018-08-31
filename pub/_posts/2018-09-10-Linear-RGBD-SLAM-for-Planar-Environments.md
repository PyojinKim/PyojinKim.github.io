---
title: "Linear RGB-D SLAM for Planar Environments"
header:
  teaser: /thumbnails/2018_ECCV.png
conference: ECCV
links: 
 - paper: 
   link: /download/papers/2018_ECCV.pdf
   name: "Paper"
 - video: 
   link: https://youtu.be/GO0Q0ZiBiSE
   name: "Video"
 - poster: 
   link: /download/posters/2018_ECCV_poster.pdf
   name: "Poster"
 - bibtex: 
   name: "Bibtex"
excerpt: "We propose a new formulation for including orthogonal planar features as a global model into a linear SLAM approach based on sequential Bayesian filtering. Previous planar SLAM algorithms estimate the camera poses and multiple landmark planes in a pose graph optimization. However, since it is formulated as a high dimensional nonlinear optimization problem, there is no guarantee the algorithm will converge to the global optimum. To overcome these limitations, we present a new SLAM method that jointly estimates camera position and planar landmarks in the map within a linear Kalman filter framework. It is rotations that make the SLAM problem highly nonlinear. Therefore, we solve for the rotational motion of the camera using structural regularities in the Manhattan world (MW), resulting in a linear SLAM formulation. We test our algorithm on standard RGB-D benchmarks as well as additional large indoor environments, demonstrating comparable performance to other state-of-the-art SLAM methods without the use of expensive nonlinear optimization."
---

{% include youtubePlayer.html id="GO0Q0ZiBiSE" %}

We propose a new formulation for including orthogonal planar
features as a global model into a linear SLAM approach based on
sequential Bayesian filtering. Previous planar SLAM algorithms estimate
the camera poses and multiple landmark planes in a pose graph optimization.
However, since it is formulated as a high dimensional nonlinear optimization
problem, there is no guarantee the algorithm will converge to
the global optimum. To overcome these limitations, we present a new
SLAM method that jointly estimates camera position and planar landmarks
in the map within a linear Kalman filter framework. It is rotations
that make the SLAM problem highly nonlinear. Therefore, we solve for
the rotational motion of the camera using structural regularities in the
Manhattan world (MW), resulting in a linear SLAM formulation. We
test our algorithm on standard RGB-D benchmarks as well as additional
large indoor environments, demonstrating comparable performance to
other state-of-the-art SLAM methods without the use of expensive nonlinear
optimization.

## Bibtex <a id="bibtex"></a>
```
@inproceedings{kim2018linear,
  author = {Kim, Pyojin and Coltin, Brian and Kim, H Jin},
  title = {Linear RGB-D SLAM for Planar Environments},
  year = {2018},
  booktitle = {ECCV},
}
```
