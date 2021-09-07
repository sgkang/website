---
title: Research
layout: page
order: date
banner: aem_butte.png
banner_description: "Resistivity distribution of the subsurface in Butte and Glenn Counties, CA, U.S.A."
---

{% from "utils.html" import make_index, make_tags, make_tag, fa %}



In 21 century, population growth and climate change create urgent & challenging geoscience problems from sustainable management of natural resources (e.g. groundwater and critical minerals) to monitoring contaminants and natural hazards (e.g. landslides). Dynamics of all these problems are related to the properties and processes of the Earth’s subsurface, and therefore seeing below the subsurface is a fundamental knowledge required to solve (or help solve) these problems that we faced. My research focuses on advancing Earth Imaging techniques, which utilizes various types of sensors (e.g., ground-based, airborne, satellites) to measure data and images Earth’s subsurface from the data. In order to advance these imaging techniques, I use an open-source approach as a mechanism to communicate and collaborate across disciplinary lines in academia, industry, public & governmental organizations. I bring computational expertise in inverse problems and data science as well as experience related to field acquisition particularly in electromagnetics (EM) geophysics. I am a developer of open-source computational resources (e.g. SimPEG — open-source geophysical software) and want to promote the growth of these open resources as well as use them. 


# Grants

These are funded research projects in which I participate as a principal geoscientist:

<div class="research-index">
    {{ make_index(site.reflinks["/research"].content, site, hr=false, date=false) }}
</div>


# Research Themes

## Integrative Geoscience Problems
These research projects involve engineers, geologists, hydrologists, geophysicists, and multiple types of data with the goal of solving (or helping to solve) the posed geoscience problem. An example research avenue that I plan to pursue is using multi-scale geophysical data from satellite to airborne sensors, which provides a broad range of sampling scales from tens of meters to thousands of kilometers, to understand the complex spatial and temporal controls on hydrologic processes. My research will focus upon using data science and optimization techniques to find spatial and temporal correlation among: (1) InSAR deformation data, (2) airborne electromagnetic (AEM) resistivity data, and (3) hydraulic head data (available from wells). 

<div class="research-index">
    {{ make_tags(["aem"], icon=true) }}
    {{ make_index(site.reflinks["/tag/aem"].content[:4], site, hr=false, date=false) }}
</div>

## EM Imaging to See Under the Cover
For a sustainable management of natural resources (e.g. critical minerals, geothermal), demands to see deeper parts of the subsurface (e.g., a few to tens of kilometers) is exponentially increasing with increasing demands of natural resources. Two major EM imaging techniques relevant to this task are magnetotelluric (MT) and controlled source audio-frequency MT (CSAMT). For a successful implementation of these techniques for imaging “under the cover”, developing robust interpretation techniques to image a three-dimensional resistivity distribution of the subsurface from the MT and CSAMT data is the key. 

## Frequency Dependent Properties
Exploiting the frequency dependence of physical properties, particularly electrical resistivity and magnetic susceptibility, has a large potential, and possibly more will be discovered. For instance, chargeability of subsurface materials (related to electrical resistivity) are different, and hence imaging chargeability of the subsurface can be useful for various geoscience applications. Chargeability signals can be measured through EM surveys in ground, air, and in water; this is often referred to as an induced polarization (IP) technique.  Throughout my PhD work, I have developed inversion algorithms to image subsurface chargeability. 

<div class="research-index">
    {{ make_tags(["ip"], icon=true) }}
    {{ make_index(site.reflinks["/tag/ip"].content[:4], site, hr=false, date=false) }}
</div>

# Open-source resources

I am a co-creator of Python-based open-source geophysical simulation and inversion package, SimPEG, and an editor of on-line text books for EM and applied geophysics: EM GeoSCi and GPG, respectively.

## SimPEG (www.simpeg.xyz)

SimPEG includes a suite of geophysical methods including magnetics, gravity, ERT (or DC resistivity), EM, magnetotellurics (MT).

## EM GeoSci (em.geosci.xyz)

On-line text book for electromagnetic geophysics.

## Geophysics for Practicing Geophysicists (gpg.geosci.xyz)

On-line text book for applied geophysics.