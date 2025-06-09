---
title: About
layout: page
content:
    - phd
    - masters
    - bachelors
banner: slo.png
banner_position: center left
banner_description: "Imaging sediment type of the subsuface, in Paso Robles, CA, U.S.A."
---


{% from "utils.html" import fa, ai %}

# Short Bio

I completed my PhD in Geophysics at the University of British Columbia, Canada, in 2018. My thesis work focused on computational electromagnetics and its application to mineral exploration. Currently, I am an Assistant Professor leading [Electromagnetic Geophysics Lab](http://emgeolab.org/) at the University of Manitoba. My research focuses on advancing electromagnetic imaging for groundwater and mining applications. I continue to contribute to the development of open source software, [SimPEG](https://www.simpeg.xyz), and educational resources, [GeoSci.xyz](https://www.geosci.xyz), for applied geophysics.

# Curriculum Vitae

A PDF version of my CV:

<a href="https://drive.google.com/file/d/1ja2pF78z9ja9y5mArkP5dLtljh-K9L_0/view?usp=sharing" target="_blank" type="application/pdf" rel="external noopener noreferrer"><i class="fa fa-file-pdf-o"></i> Download Curriculum Vitae</a>


# Around the internet

You can find myself and my research, code, articles, and data at:

<ul class="fa-ul">

<li><i class="fa-li fa fa-github fa-fw"></i>
<a href="https://github.com/sgkang">Github</a>:
<em>software projects, repositories for papers and talks</em>
</li>

<li><i class="fa-li ai ai-orcid fa-fw"></i>
<a href="http://orcid.org/0000-0002-9963-936X">ORCID</a> ( http://orcid.org/0000-0002-9963-936X ):
<em>aggregates all of my scientific output that have DOIs</em>
</li>

<li><i class="fa-li ai ai-impactstory fa-fw"></i>
<a href="https://impactstory.org/u/0000-0002-9963-936X">ImpactStory</a>:
<em>hub for article level metrics and further impact of research</em>
</li>

<li><i class="fa-li ai ai-google-scholar fa-fw"></i>
<a href="https://scholar.google.com/citations?user=wFndVSMAAAAJ&hl=en">Google Scholar</a>:
<em>publication list and citation information</em>
</li>

<li><i class="fa-li ai ai-researchgate fa-fw"></i>
<a href="https://www.researchgate.net/profile/Seogi-Kang">ResearchGate</a>:
<em>academic social network</em>
</li>


</ul>


# Experience

## Assistant Professor


<ul class="fa-ul">
    <li><i class="fa-li fa fa-calendar fa-fw"></i>
        Jan. 2025 - Present
    </li>
    <li><i class="fa-li fa fa-university fa-fw"></i>
        Department of Earth Sciences
        <br>
        Clayton and Ridell Faculty
        <br>
        <a href="https://umanitoba.ca">University of Manitoba</a>, Canada
    </li>
    <li><i class="fa-li fa fa-info-circle fa-fw"></i>
        More information about my role and activities can be found in <a href="http://emgeolab.org"> Electromagnetic Geophysics Lab</a>
    </li>
</ul>


## Postdoctoral Fellow / Research Scientist


<ul class="fa-ul">
    <li><i class="fa-li fa fa-calendar fa-fw"></i>
        Jan. 2019 - Oct. 2024
    </li>
    <li><i class="fa-li fa fa-university fa-fw"></i>
        Department of Geophysics
        <br>
        School of Earth
        <br>
        <a href="https://earth.stanford.edu/">Stanford Univeristy</a>, U.S.A.
    </li>
    <li><i class="fa-li fa fa-info-circle fa-fw"></i>
        More information about my role and activities can be found in <a href="https://enviro.stanford.edu/">Environmental Geophysics Group</a>, <a href="https://mapwater.stanford.edu/">Ground Water Architecture Project</a>, and <a href="https://fastpath.stanford.edu/">Fastpath Web-based Application</a> 
    </li>
</ul>

## Postdoctoral Fellow

<ul class="fa-ul">
    <li><i class="fa-li fa fa-calendar fa-fw"></i>
        June 2018 - Dec. 2018
    </li>
    <li><i class="fa-li fa fa-university fa-fw"></i>
        Department of Earth, Ocean and Atmospheric Sciences
        <br>
        <a href="https://www.eoas.ubc.ca/">University of British Columbia </a>, Canada
    </li>
    <li> Co-created <a href="https://www.simpeg.xyz">SimPEG</a> - Python-based open-source geophysics software</li>
    <li> Developed geophysical 1D spatially-constrained inversion algorithm that can invert large-scale AEM data. The developed software, referred to as simpeg-EM1D is avaiable though the <a href="https://github.com/simpeg/simpegEM1D">Github</a>. This was integrated with a commercial framework (called <a href="https://gif.eos.ubc.ca/giftools">GIFtools</a>), and has been actively used by major mining companes (Teck, Barrick, RioTinto, Anglo American, BHP, Glencore and Vale).
    </li>

</ul>

# Education

<div>
    {%- for edu in this.content -%}
        <h3><a href="{{ edu.url }}">{{ edu.title }}  »</a></h3>
        <ul class="fa-ul">
            <li><i class="fa-li fa fa-calendar fa-fw"></i>
                {{ edu.start_date.year}}-{{ edu.date.year }}
            </li>
            <li><i class="fa-li fa fa-university fa-fw"></i>
                {{ edu.institution }}
            </li>
            <li><i class="fa-li fa fa-graduation-cap fa-fw"></i>
                Advisor: {{ edu.advisor }}
            </li>
            <li><i class="fa-li fa fa-book fa-fw"></i>
                Thesis: {{ edu.thesis }}
            </li>
        </ul>
    {%- endfor -%}
</div>
