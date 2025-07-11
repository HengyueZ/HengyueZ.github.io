---
layout: page
title: WISDOM
description: Supermassive black hole mass measurements using molecular gas kinematics
img: assets/img/BH masses.jpg
importance: 1
category: work
related_publications: true
---

Supermassive black holes (SMBHs) at the centres of galaxies dynamically dominate only a small region, named the "sphere of influence" (SoI). Yet, they play a crucial role in galaxy evolution, growing through gas accretion while regulating star formation through feedback mechanisms. The clues to understanding the co-evolution of SMBHs and galaxies lie in the correlations between SMBH masses and galaxy properties, such as stellar velocity dispersion, bulge mass, and total stellar mass.


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/M-sigma.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/MBH-Mbulge.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/MBH-Mstar.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Left: SMBH mass-stellar velocity dispersion relation in van den Bosch (2016). Middle: SMBH mass-bulge mass relation in McConnell & Ma (2013). Right: SMBH mass-stellar mass relation in van den Bosch (2016).
</div>

The mm-Wave Interferometric Survey of Dark Object Masses ([WISDOM](https://wisdom-project.org/)) project has measured SMBH masses in 13 galaxies using ALMA observations of their molecular gas kinematics, a major step towards pinning down the SMBH-galaxy correlations across the Hubble sequence. My work focuses on obtaining the highest-precision SMBH mass measurements using ultra-high-resolution ALMA observations to **(1)** reveal systematic inaccuracies of lower-resolution SMBH mass determinations, **(2)** distinguish the intrinsic scatter of SMBH-galaxy relations caused by variations of intrinsic galaxy properties (e.g. morphology and stellar mass) from the observational scatter caused by uncertain measurements, and **(3)** probe SMBH accretion and feedback down to circumnuclear scales.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images, even citations {% cite einstein1950meaning %}.
Say you wanted to write a bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>

The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

