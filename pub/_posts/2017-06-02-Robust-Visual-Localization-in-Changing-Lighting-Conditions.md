---
title: "Robust Visual Localization in Changing Lighting Conditions"
header:
  teaser: /thumbnails/2017_ICRA.png
conference: ICRA
links: 
 - paper: 
   link: /download/papers/2017_ICRA.pdf
   name: "Paper"
 - video: 
   link: https://youtu.be/Nuyq74wbz7I
   name: "Video"
 - bibtex: 
   name: "Bibtex"
---

{% include youtubePlayer.html id="Nuyq74wbz7I" %}

We present an illumination-robust visual localization
algorithm for Astrobee, a free-flying robot designed
to autonomously navigate on the International Space Station
(ISS). Astrobee localizes with a monocular camera and a prebuilt
sparse map composed of natural visual features. Astrobee
must perform tasks not only during the day, but also at night
when the ISS lights are dimmed. However, the localization
performance degrades when the observed lighting conditions
differ from the conditions when the sparse map was built.
We investigate and quantify the effect of lighting variations
on visual feature-based localization systems, and discover that
maps built in darker conditions can also be effective in bright
conditions, but the reverse is not true. We extend Astrobee’s
localization algorithm to make it more robust to changinglight
environments on the ISS by automatically recognizing
the current illumination level, and selecting an appropriate
map and camera exposure time. We extensively evaluate the
proposed algorithm through experiments on Astrobee.

## Bibtex <a id="bibtex"></a>
```
@inproceedings{kim2017robust,
  author = {Kim, Pyojin and Coltin, Brian and Alexandrov, Oleg and Kim, H Jin},
  title = {Robust Visual Localization in Changing Lighting Conditions},
  year = {2017},
  booktitle = {ICRA},
}
```
