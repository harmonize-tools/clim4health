# clim4health  <img src='man/figures/logo_harmonize.png' align="right" width="9%" /> <span> <span> <img src='man/figures/logo_BSC.png' align="right" width="16%" /> 

<!-- badges: start -->
[![License](https://img.shields.io/badge/License-AGPL_v3-brightgreen.svg?style=flat)](https://www.gnu.org/licenses/agpl-3.0.html)
<!-- badges: end -->

<img src='man/figures/clim4health.jpg' align="right" width="14%" />

## Overview

**clim4health** is an R package designed to obtain, transform and export climate 
data for their use in epidemiological analyses and other types of applications. 
The package contains a series of functions structured in three sequential blocks: 
input, transformation, and output. 

In the input block, **clim4health** provides functions to download several types of 
climate data including reanalyses, forecasts, hindcasts, and weather stations 
and load them into memory for their processing. The transformation block includes 
functions to postprocess and downscale climate data, perform spatiotemporal
aggregations, as well as compute threshold-based suitability indicators. Finally, 
in the output block, functions to visualize and export the transformed data are 
provided.

<br>
<div align="center">
<img src='man/figures/package_structure.jpg' width="80%" /></center>
</div>
<br> \

**clim4health** is one of the packages developed by the
[Global Health Resilience](https://www.bsc.es/discover-bsc/organisation/research-departments/global-health-resilience) (GHR)
team at the [Barcelona Supercomputing Center](https://www.bsc.es/) (BSC) within 
the [HARMONIZE](https://www.harmonize-tools.org/) project, which comprises 
different R and Python libraries tailored for health, climate, environmental, 
and socioeconomic data acquisition, harmonisation, and visualization.

The package is currently under development and its expected release date 
is **February 2026**.

## Developers

**[Emily Ball, PhD](https://www.bsc.es/ball-emily)**
<a href="https://orcid.org/0000-0002-3002-4068" style="margin-left: 15px;"><img src="https://orcid.org/sites/default/files/images/orcid_16x16.png" alt="ORCID" style="width: 16px; height: 16px;" /></a>\
Barcelona Supercomputing Center\
Climate Services

**[Alba Llabrés, PhD](https://www.bsc.es/llabres-alba)**
<a href="https://orcid.org/0000-0003-2144-675X" style="margin-left: 15px;"><img src="https://orcid.org/sites/default/files/images/orcid_16x16.png" alt="ORCID" style="width: 16px; height: 16px;" /></a>\
Barcelona Supercomputing Center\
Climate Services

**[Carles Milà, PhD](https://www.bsc.es/mila-garcia-carles)**
<a href="https://orcid.org/0000-0003-0470-0760" style="margin-left: 15px;"><img src="https://orcid.org/sites/default/files/images/orcid_16x16.png" alt="ORCID" style="width: 16px; height: 16px;" /></a>\
Barcelona Supercomputing Center\
Global Health Resilience

**[Raul Capellan Fernandez, MSc](https://www.bsc.es/capellan-fernandez-raul)** \
Barcelona Supercomputing Center\
Earth Data and Diagnostics

**[Daniela Lührsen, MSc](https://www.bsc.es/luhrsen-daniela-sofie)**
<a href="https://orcid.org/0009-0002-6340-5964" style="margin-left: 15px;"><img src="https://orcid.org/sites/default/files/images/orcid_16x16.png" alt="ORCID" style="width: 16px; height: 16px;" /></a>\
Barcelona Supercomputing Center\
Global Health Resilience

**[Anna B. Kawiecki, PhD](https://www.bsc.es/kawiecki-peralta-ania)**
<a href="https://orcid.org/0000-0002-0499-2612" style="margin-left: 15px;"><img src="https://orcid.org/sites/default/files/images/orcid_16x16.png" alt="ORCID" style="width: 16px; height: 16px;" /></a>\
Barcelona Supercomputing Center\
Global Health Resilience

**[Rachel Lowe, PhD](https://www.bsc.es/lowe-rachel)**
<a href="https://orcid.org/0000-0003-3939-7343" style="margin-left: 15px;"><img src="https://orcid.org/sites/default/files/images/orcid_16x16.png" alt="ORCID" style="width: 16px; height: 16px;" /></a>\
Barcelona Supercomputing Center\
Global Health Resilience (Group leader)




<!--
# clim4health <a href='https://www.harmonize-tools.org/'><img src='https://harmonize-tools.github.io/harmonize-logo.png' align="right" height="139" /></a>


[![Lifecycle:
maturing](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://lifecycle.r-lib.org/articles/stages.html#experimental)
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)


## Overview
<p style="font-family: Arial, sans-serif; font-size: 14px;">
clim4health is a tool developed within the HARMONIZE project with the aim of post-processing climate data harmonized to the spatiotemporal aggregation of health data. The tool consists in an R-package and its documentation including examples on how to use the tool and recommendations of parameter selection in some case studies. 

The functions that are part of the tool allow for:
- calibration and quality assessment of climate forecasts
- harmonization of the spatial resolution of the climate data with techniques of statistical spatial downscaling or aggregation to shapefiles
- harmonization of the temporal resolution of the climate data with aggregation to epidemiological week or coarser aggregations
- index calculation (e.g. threshold based index)
- visualization of results
- output as .csv file harmonized to the requested format
</p>

## Resources

<details>
<summary>
Downscaling of Climate Data
</summary>

The [downscaling tutorial](https://github.com/harmonize-tools/climate-downscaling) deepens into how to spatially downscale climate data using underlying tools in the clim4health package, using sample data and examples of the HARMONIZE project hotspots.

</details>
<details>
<summary>
Organisation Website
</summary>

[Harmonize](https://www.harmonize-tools.org/) is an international develop cost-effective and reproducible digital tools for stakeholders in hotspots affected by a changing climate in Latin America & the Caribbean (LAC), including cities, small islands, highlands, and the Amazon rainforest.

The project consists of resources and [tools](https://harmonize-tools.github.io/) developed in conjunction with different teams from Brazil, Colombia, Dominican Republic, Peru and Spain.

</details>

## Organizations

<table>
  <tr>
    <td align="center">
      <a href="https://www.bsc.es/" target="_blank">
        <img src="https://imgs.search.brave.com/t_FUOTCQZmDh3ddbVSX1LgHYq4mzCxvVA8U_YHywMTc/rs:fit:500:0:0/g:ce/aHR0cHM6Ly9zb21t/YS5lcy93cC1jb250/ZW50L3VwbG9hZHMv/MjAyMi8wNC9CU0Mt/Ymx1ZS1zbWFsbC5q/cGc" height="64" alt="dplyr logo">
      </a>
    </td>
    <td align="left">
      <strong>GHR</strong><br>
      Global Health Resilience
    </td>
  </tr>
</table>


## Authors

</br>
</br>
<a href="https://github.com/Alba-LB">
  <img src="https://avatars.githubusercontent.com/u/129278822?v=4" style="width: 50px; height: auto;" />
</a>
<span style="display: flex; align-items: center; margin-left: 10px;">
  <strong>Alba Llabrés-Brustenga</strong> (developer)
  <a href="https://orcid.org/0000-0003-2144-675X" style="margin-left: 10px;">
    <img src="https://orcid.org/sites/default/files/images/orcid_16x16.png" alt="ORCID" style="width: 16px; height: 16px;" />
  </a>
</span>

</br>
</br>
<a href="https://github.com/Daniela-L">
  <img src="https://avatars.githubusercontent.com/u/76750744?v=4" style="width: 50px; height: auto;" />
</a>
<span style="display: flex; align-items: center; margin-left: 10px;">
  <strong>Daniela Lührsen</strong> (developer)
  <a href="https://orcid.org/0009-0002-6340-5964" style="margin-left: 10px;">
    <img src="https://orcid.org/sites/default/files/images/orcid_16x16.png" alt="ORCID" style="width: 16px; height: 16px;" />
  </a>
</span>

</br>
</br>
<a href="https://github.com/RaulCapellanFernandez">
  <img src="https://avatars.githubusercontent.com/u/22483508?v=4" style="width: 50px; height: auto;" />
</a>
<span style="display: flex; align-items: center; margin-left: 10px;">
  <strong>Raúl Capellán Fernández</strong> (developer)
</span>
-->
