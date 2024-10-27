---
layout: page
title: Design of a K-Band Antenna Array
description: Initial design of a K-band radar hardware operating in the 18–27 GHz range
img: assets/img/antenna_array/main.png
importance: 4
category: RF
giscus_comments: true
---

##  Abstract

This project presents the initial design of a K-band radar hardware operating in the 18–27 GHz range. The design focuses on an active corporate feed network for a three-element antenna array, chosen to achieve optimal directivity and maximize range. The design incorporates a low-noise amplifier and a three-port power divider, configured using the AWR software, and explores radiating elements with CST Microwave Studio. Key specifications include precise gain, noise, and impedance requirements to ensure reliable performance at 18.66 GHz, with strict dimensions for manufacturability. CST analysis covers both infinite and finite ground planes, impacting radiation characteristics and efficiency. Finally, the integration of the active feed network and the antenna array in AWR is assessed, with simulations indicating some deterioration in isolation and phase stability. Future work involves refining the layout and optimizing integration for a manufacturable, fully functional radar array. 

This project was carried out in collaboration with [Óscar González Fresno](https://oscgf.github.io/portfolio/) and Oier Huici Itarte.

The complete document can be found [here](https://edgomezg.github.io/assets/pdf/Diseno_array_banda_K.pdf).

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/antenna_array/schema.png" title="general schema" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/antenna_array/layout.png" title="polarization circuit layout" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/antenna_array/main.png" title="complete array farfield radiation" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    On the left, a schematic of the implementation. Middle, part of the polarization circuit layout. Right, the complete array farfield radiation pattern.
</div>