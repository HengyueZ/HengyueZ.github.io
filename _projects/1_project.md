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
        {% include figure.liquid loading="eager" path="assets/img/M-sigma.png" title="M-sigma relation" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/MBH-Mbulge.png" title="MBH-Mbulge relation" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/MBH-Mstar.png" title="MBH-Mstar relation" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Left: SMBH mass-stellar velocity dispersion relation in van den Bosch (2016). Middle: SMBH mass-bulge mass relation in McConnell & Ma (2013). Right: SMBH mass-stellar mass relation in van den Bosch (2016).
</div>

The mm-Wave Interferometric Survey of Dark Object Masses ([WISDOM](https://wisdom-project.org/)) project has measured SMBH masses in 13 galaxies using ALMA observations of their molecular gas kinematics, a major step towards pinning down the SMBH-galaxy correlations across the Hubble sequence. My work focuses on obtaining the highest-precision SMBH mass measurements using ultra-high-resolution ALMA observations to **(1)** reveal systematic inaccuracies of lower-resolution SMBH mass determinations, **(2)** distinguish the intrinsic scatter of SMBH-galaxy relations caused by variations of intrinsic galaxy properties (e.g. morphology and stellar mass) from the observational scatter caused by uncertain measurements, and **(3)** probe SMBH accretion and feedback down to circumnuclear scales. 

The figure below from my recent work {% cite Zhang_2024 %} shows that the highest-resolution molecular gas kinematic observations using ALMA can resolve the SoI as well as the "gold standard" megamaser observations using VLBI, allowing ultra-high precision SMBH mass measurements in a much more diverse sample of galaxies and studies of the circumnuclear molecular gas disk to unprecedented detail. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Rsoi_plot.png" title="molecular gas VS masers" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Radii and circular velocities of the innermost kinematic tracers of all SMBH mass measurements using megamaser or molecular gas kinematics, in units of the SoI radius and the stellar velocity dispersion, respectively. The dashed black line shows the Keplerian velocity profile. Solid curves in different shades of green show the velocity profiles of a mock galaxy with different Sérsic indices. The highest-resolution measurements (on the leftmost region of the figure) probe the innermost region of the velocity profile, which is dominated by the SMBH and relatively independent of the stellar mass distribution. Although maser observations generally resolve the SoI better than molecular gas observations, my recent high-resolution WISDOM measurement of the SMBH in NGC 383 {% cite Zhang_2025 %}, the leftmost blue data point, probes the SMBH-dominated region equally well as the best maser observations.
</div>

This remarkable NGC 383 measurement is shown below. Achieving a physical resolution of only 10 pc, we detected the strongest SMBH dynamical signature ever seen in molecular gas observations. Dynamical modelling using the [**KinMS**](https://github.com/TimothyADavis/KinMS_fitter) package gives an SMBH mass of $(3.58 \pm 0.19)\times10^9\,M_\odot$. This measurement has an unprecedented precision of 5% and reveals that the previous SMBH mass measurement in this galaxy using lower-resolution ALMA observations slightly overestimated the SMBH mass.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/NGC383_observations.png" title="NGC 383 observations" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Integrated intensity (left) and line-of-sight velocity (right) maps created from our high-resolution NGC 383 data cube. Velocity enhancement due to the SMBH is clearly visible at the centre of the velocity map.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/NGC383_models.png" title="NGC 383 models" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Observed kinematic major-axis position-velocity diagram (PVD) of NGC 383 (orange scale with black contours), overlaid with the PVDs of different models (cyan contours): no SMBH (left), best-fitting model from our work (centre) and best-fitting model from [North et al. (2019; right)](https://academic.oup.com/mnras/article/490/1/319/5571102) derived from lower-resolution observations. The sharp increase (from
the outside in) of the line-of-sight velocities within the central ≈ 0.5 arcsec is a clear kinematic signature of a central SMBH. Our best-fitting model reproduces the material beyond ≈ 350 km/s better than the prevous best-fitting model, demonstrating the importance of high-resolution observations to the precision and accuracy of SMBH mass measurements.
</div>

Additionally, this high-resolution ALMA observation revealed a possible position angle warp in the previously unresolved central region of the molecular gas disk, which aligns the circumnuclear molecular gas disk more closely with the radio jet in this galaxy than the large-scale molecular gas disk. Such an alignment was previously only seen in megamaser disk observations.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/NGC383_warp_model.png" title="NGC 383 warp model" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/NGC383_warp.png" title="NGC 383 warp" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Left: A position angle warp model provides a better fit to the (slightly smoothed) data than a model without warps. Right: For a gas disk perpendicular to the radio jet, the zero-velocity contour (green curve) would align with the radio jet's direction. The possible PA warp in NGC 383 makes the inner circumnuclear molecular gas disk more closely aligned with the radio jet than the outer large-scale molecular gas disk.
</div>
