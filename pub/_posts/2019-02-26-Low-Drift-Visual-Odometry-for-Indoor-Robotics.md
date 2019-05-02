---
title: "Low-Drift Visual Odometry for Indoor Robotics"
header:
  teaser: /thumbnails/2019_pjinkim_PhDthesis.png
conference: PhD Thesis
links: 
 - paper: 
   link: /download/papers/2019_pjinkim_PhDthesis_high.pdf
   name: "PhD Thesis (high res.)"
 - paper: 
   link: /download/papers/2019_pjinkim_PhDthesis_low.pdf
   name: "PhD Thesis (low res.)"
 - bibtex: 
   name: "Bibtex"
---

This thesis explores the robust and accurate 6-DoF camera motion estimation from a sequence of images, called visual odometry (VO) or visual simultaneous localization and mapping (vSLAM).
We focus on the robustness and high accuracy of the VO and visual localization by explicitly modeling the light changes as an affine illumination model, and utilizing the indoor environmental structures such as lines and planes.
This brings the significant advantage to VO that it does not lose estimation accuracy in challenging environments such as light-changing conditions or pure, on the spot rotations.

The first part of the thesis proposes a novel patch-based illumination invariant visual odometry algorithm (PIVO).
PIVO employs an affine illumination change model per each patch in the image to compensate unexpected, abrupt, and irregular illumination changes during the direct motion estimation.
PIVO infers camera geometry directly from the images, i.e., the raw sensor measurements, without intermediate abstraction, for instance in the form of keypoint matches.
We furthermore incorporate a motion prior from feature-based stereo visual odometry in the optimization, resulting in higher accuracy and more stable motion estimates.
We evaluate the proposed VO algorithm on a variety of datasets, and demonstrate autonomous flight experiments with an aerial robot, showing that the proposed method successfully estimates 6-DoF pose under significant illumination changes.

In the second part of the thesis, we propose a low-drift VO that separately estimates rotational and translational motion from lines, planes, and points found in RGB-D images.
To estimate the rotational motion that is a main source of drift in VO in an accurate and drift-free manner, we exploit both lines and planes jointly from environmental regularities.
We recognize and track the structural regularities with an efficient SO(3)-manifold constrained mean shift algorithm.
Once the absolute camera orientation is found, we recover the translational motion from all tracked points with and without depth by minimizing the de-rotated reprojection error.
We compare the proposed algorithm to other state-of-the-art VO methods on a variety of RGB-D datasets that include especially challenging pure rotations, and demonstrate improved accuracy and lower drift error.

{% include base_path %}

## Bibtex <a id="bibtex"></a>
```
@phdthesis{kim2019phdthesis,
  author = {Kim, Pyojin},
  title = {Low-Drift Visual Odometry for Indoor Robotics},
  school = {Seoul National University},
  year = {2019},
  address = {1 Gwanak-ro, Gwanak-gu, Seoul 08826},
  month = {2},
}
```
