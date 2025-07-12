---
layout: page
title: GLAMOR
description: The first dynamical SMBH mass measurements at high redshifts, enabled by gravitational lensing
img: assets/img/SPT0418.png
importance: 1
category: work
related_publications: true
---

Dynamical SMBH mass measurements are so far limited to $z<0.1$ due to the difficulty for current instruments to resolve the SoI of high-redshift SMBHs while achieving sufficient sensitivity. Thus far, almost all SMBH mass determinations at higher redshifts are indirect estimates calibrated using local SMBH-galaxy scaling relations (with $>0.3$ dex calibration uncertainties) and limited to the brightest quasars. These estimates suggest that high-redshift SMBHs are highly overmassive compared to the local SMBH mass-stellar mass relation, implying heavy SMBH seeds and/or episodes of super-Eddington accretion. However, it requires precise SMBH mass measurements using dynamical methods to confirm the result in an unbiased sample of galaxies and directly probe SMBH formation and SMBH-galaxy coevolution across cosmic time.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/JWST SMBH.png" title="JWST SMBHs" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Figure 4 of Pacucci & Loeb (2024), showing that JWST-discovered high-redshift SMBHs are overmassive relative to the local SMBH mass-stellar mass relation.
</div>

Gravitational lensing magnifies the luminosity and extends the angular size of the lensed object, providing opportunities to perform the first dynamical SMBH mass measurements beyond $z\approx0$. In collaboration with [Michael Barth](https://darthbarth.science/) at the University of Montreal, we developed a novel dynamical modelling code package that forward models gas dynamics and gravitational lensing simultaneously to infer SMBH masses in high-redshift lensed galaxies observed by ALMA. The code has three significant advantages over most existing dynamical and lens modelling codes: **(1)** It forward models the lens configuration and parameters, allowing us to quantify their contributions to the uncertainties of dynamical parameters (such as the SMBH mass). **(2)** It fits ALMA data directly in visibility space, eliminating uncertainties and systematics introduced by interferometric imaging. **(3)** It is automatically differentiable, substantially speeding up parameter fitting and allowing the use of machine-learning-based modelling procedures.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

I am now leading an ALMA Cycle 11 program that observes a lensed galaxy at $z=4.24$ to perform the first dynamical SMBH mass measurement at $z\approx4$. Part of the data has arrived, and the quality looks promising! Stay tuned for the results!
