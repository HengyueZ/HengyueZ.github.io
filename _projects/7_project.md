---
layout: page
title: GLAMOR
description: The first dynamical SMBH mass measurements at high redshifts, enabled by gravitational lensing
img: assets/img/SPT0418.png
importance: 1
category: work
related_publications: false
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

Gravitational lensing magnifies the luminosity and extends the angular size of the lensed object, providing opportunities to spatially resolve the SMBH SoI of high-redshift galaxies for the first time. The recently formed **G**ravitational **L**ensing **A**nd **M**assive **O**bject **R**ecovery (**GLAMOR**) collaboration aims to use ultra-high-resolution ALMA observations to perform the first dynamical measurements of SMBH masses at high redshifts. Together with [Michael Barth](https://darthbarth.science/) at the University of Montreal, we developed a novel dynamical modelling code package that forward models gas dynamics and gravitational lensing simultaneously to infer SMBH masses in lensed galaxies observed by ALMA. The code has three significant advantages over most existing dynamical and lens modelling codes: **(1)** It forward models the lens configuration and parameters, allowing us to quantify their contributions to the uncertainties of dynamical parameters (such as the SMBH mass). **(2)** It fits ALMA data directly in visibility space, eliminating uncertainties and systematics introduced by interferometric imaging. **(3)** It is automatically differentiable, substantially speeding up parameter fitting and allowing the use of machine-learning-based modelling procedures. Below is a demo of our modelling package on a simulated ALMA observation of a lensed galaxy. It successfully recovers the SMBH mass of $5.6 \times 10^{9}$ $M_\mathrm{\odot}$ and the stellar mass of $4.8 \times 10^{11}$ $M_\mathrm{\odot}$ by fitting the simulated observation.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/simulated lens.png" title="Fitting to simulated data" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    (a): Ground truth velocity map of a mock ALMA observation of a simulated lensed galaxy in the source plane. The contours show source plane magnification, and white circles show the effective beam size at those magnifications. (b): Ground truth velocity map of the mock observation in the image plane. The white circle represents the beam size of the observation. (c): PVD of the ground truth (red), overlaid on the PVD of the best-fitting model using our forward modelling pipeline (greyscale contours, fit in the visibility plane with MCMC). Our pipeline accurately recovers the ground truth SMBH mass and stellar mass, reproducing the PVD nicely. (d): Same as (c) but with the best-fitting model without any BH. The velocity rise revealed at $R < 0.''1$ cannot be reproduced without a BH.
</div>

**I am now leading an ALMA Cycle 11 program that observes a lensed galaxy at $z=4.24$ to perform the first dynamical SMBH mass measurement at $z\approx4$. Part of the data has arrived, and the quality looks promising! Stay tuned for the results!**
