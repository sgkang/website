---
title: About
layout: page
content:
    - phd
    - masters
    - bachelors
banner: slo.png
banner_position: center left
banner_description: "Overlooking the Valley of Fire national park in Nevada, USA."
---


{% from "utils.html" import fa, ai %}

# Short Bio

I got my PhD in Geophysics at University of British Columbia, Canada, in 2018. My thesis work focussed on computational electromagnetics and its application to mining problems. Currently, I am a Postdoctoral Researcher in [Environmental Geophysics Group](https://enviro.stanford.edu/) at Stanford University. My focus is on advancing use of an airborne electromagnetic and remote sensing methods for groundwater management and groundwater science. I continue to contribute to the development of open source software, [SimPEG](https://www.simpeg.xyz), and educational resources, [GeoSci.xyz](https://www.geosci.xyz), for geophysics.

# Curriculum Vitae

A PDF version of my CV: Download Curriculum Vitae

<a href="https://github.com/sgkang/website/raw/master/pdf/cv-seogikang-2021.pdf" target="_blank" type="application/pdf" rel="external noopener noreferrer"><i class="fa fa-file-pdf-o"></i> Download Curriculum Vitae</a>


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

## Postdoctoral Fellow


<ul class="fa-ul">
    <li><i class="fa-li fa fa-calendar fa-fw"></i>
        Jan. 2019 - present
    </li>
    <li><i class="fa-li fa fa-university fa-fw"></i>
        Department of Geophysics
        <br>
        School of Earth
        <br>
        <a href="https://earth.stanford.edu/">Stanford Univeristy</a>, U.S.A.
    </li>
    <li><i class="fa-li fa fa-info-circle fa-fw"></i>
        More information about my role and activities can be found in <a href="https://enviro.stanford.edu/">Environmental Geophysics Group</a> and <a href="https://mapwater.stanford.edu/">Ground Water Architecture Project</a>
    </li>
</ul>

## Postdoctoral Fellow

<ul class="fa-ul">
    <li><i class="fa-li fa fa-calendar fa-fw"></i>
        June 2018 - Dec. 2018
    </li>
    <li><i class="fa-li fa fa-university fa-fw"></i>
        Department of Earth, Ocean and Atmopheric Sciences
        <br>
        <a href="https://www.eoas.ubc.ca/">University of British Columbia </a>, Canada
    </li>
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
