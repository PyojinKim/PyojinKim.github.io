---
title: "Robust Visual Odometry to Irregular Illumination Changes with RGB-D camera"
header:
  teaser: /thumbnails/2015_IROS.png
conference: IROS
links: 
 - paper: 
   link: /download/papers/2015_IROS.pdf
   name: "Paper"
 - video: 
   link: https://youtu.be/sLKrVxGTbKQ
   name: "Video"
 - bibtex: 
   name: "Bibtex"
---

{% include youtubePlayer.html id="sLKrVxGTbKQ" %}

Sensitivity to illumination conditions poses a challenge
when utilizing visual odometry (VO) in various applications.
To make VO robust with respect to illumination
conditions, they need to be considered explicitly. In this paper,
we propose a direct visual odometry method which can handle
illumination changes by considering an affine illumination
model to compensate abrupt, local light variations during direct
motion estimation process. The core of our proposed method
is to estimate the relative camera pose and the parameters of
the illumination changes by minimizing the sum of squared
photometric error with efficient second-order minimization.
We evaluate the performance of the proposed algorithm on
synthetic and real RGB-D datasets with ground-truth. Our
result implies that the proposed method successfully estimates
6-DoF pose under significant illumination changes whereas
existing direct visual odometry methods either fail or lose
accuracy.

## Bibtex <a id="bibtex"></a>
```
@inproceedings{kim2015robust,
  author = {Kim, Pyojin and Lim, Hyon and Kim, H Jin},
  title = {Robust Visual Odometry to Irregular Illumination Changes with RGB-D camera},
  year = {2015},
  booktitle = {IROS},
}
```
