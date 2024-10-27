---
layout: page
title: Design and Calibration of the Signal Reception System of a Radio Telescope
description: UPNA Internship
img: assets/img/radiotelescope/main.jpg
importance: 2
category: RF
---

This project is the result of a 6-month work Internship in the Public University of Navarre in 2022. Here you can find a summary of the work carried out as well as the link to the complete text.

## Abstract 

This project focuses on enhancing the capabilities of the Jocellyn Bell Burnell Radio Telescope at the Public University of Navarre. Key improvements include the development of a calibration and observation system and partial automation of the telescope’s movement system. The calibration system enables accurate detection of the 21-cm hydrogen line, crucial for observing neutral hydrogen in galactic structures, using software-defined radio (SDR) receivers, specifically RSPduo and BladeRF devices. Custom modifications to GNU Radio software allow for the saving and re-utilization of calibration settings, streamlining future observations. The automation of the telescope's movement system was achieved via a client-server setup, allowing it to follow preset paths without manual intervention. This project not only enhances the telescope's operational precision but also promotes radio astronomy among university students, offering a practical platform for academic research and skill development in telecommunications and astrophysics.

The complete document can be found [here](https://edgomezg.github.io/assets/pdf/Memoria Radiotelescopio Eduardo Gomez.pdf).

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/radiotelescope/spectrum Deneb.png" title="Spectrum pointing to Deneb star" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/radiotelescope/radiotelescope.jpg" title="Radio telescope" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    On the left, the spectrum received pointing to Deneb star, observing several arms of the Milky Way. Right, the Radio Telescope.
</div>