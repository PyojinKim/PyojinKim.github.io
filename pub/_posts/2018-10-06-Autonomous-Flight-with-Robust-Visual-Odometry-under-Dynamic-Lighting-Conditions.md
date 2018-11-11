---
title: "Autonomous Flight with Robust Visual Odometry under Dynamic Lighting Conditions"
header:
  teaser: /thumbnails/2018_AURO.png
conference: AURO
links: 
 - paper: 
   link: /download/papers/2018_AURO.pdf
   name: "Paper"
 - video: 
   link: https://youtu.be/agOxpphFDfE
   name: "Video"
 - bibtex: 
   name: "Bibtex"
excerpt: "Sensitivity to light conditions poses a challenge when utilizing visual odometry (VO) for autonomous navigation of small aerial vehicles in various applications. We present an illumination-robust direct visual odometry for a stable autonomous flight of an aerial robot under unpredictable light condition. The proposed stereo VO achieves robustness with respect to the light-changing environment by employing the patch-based affine illumination model to compensate abrupt, irregular illumination changes during direct motion estimation. We furthermore incorporate a motion prior from feature-based stereo visual odometry in the optimization, resulting in higher accuracy and more stable motion estimate. Thorough analyses of convergence rate and linearity index for the feature-based and direct VO methods support the effectiveness of the usage of the motion prior knowledge. We extensively evaluate the proposed algorithm on synthetic and real micro aerial vehicle (MAV) datasets with ground-truth. Autonomous flight experiments with an aerial robot show that the proposed method successfully estimates 6-DoF pose under significant illumination changes."
---

{% include youtubePlayer.html id="agOxpphFDfE" %}

Sensitivity to light conditions poses a challenge when utilizing visual odometry (VO) for autonomous navigation of small aerial vehicles in various applications.
We present an illumination-robust direct visual odometry for a stable autonomous flight of an aerial robot under unpredictable light condition.
The proposed stereo VO achieves robustness with respect to the light-changing environment by employing the patch-based affine illumination model to compensate abrupt, irregular illumination changes during direct motion estimation.
We furthermore incorporate a motion prior from feature-based stereo visual odometry in the optimization, resulting in higher accuracy and more stable motion estimate.
Thorough analyses of convergence rate and linearity index for the feature-based and direct VO methods support the effectiveness of the usage of the motion prior knowledge.
We extensively evaluate the proposed algorithm on synthetic and real micro aerial vehicle (MAV) datasets with ground-truth.
Autonomous flight experiments with an aerial robot show that the proposed method successfully estimates 6-DoF pose under significant illumination changes.

## Bibtex <a id="bibtex"></a>
```
@inproceedings{kim2018autonomous,
  author = {Kim, Pyojin and Lee, Hyeonbeom and Kim, H Jin},
  title = {Autonomous Flight with Robust Visual Odometry under Dynamic Lighting Conditions},
  year = {2018},
  booktitle = {AURO},
}
```
