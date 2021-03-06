---
title: "SimPEG: An open source framework for simulation and gradient based parameter estimation in geophysical applications"
date: 2015-07-05
author: rcockett, skang, lheagy, apidlisecky, doldenburg
journal: Computers and Geosciences
thumbnail: simpeg.png
layout: publication
tags: simpeg, open-source, simulation, inversion, geophysics
alm: true
oa: true
doi: 10.1016/j.cageo.2015.09.015
citation: "Cockett, R., S. Kang, L. J. Heagy, A. Pidlisecky, and D. W. Oldenburg, 2015, SimPEG: An open source framework for simulation and gradient based parameter estimation in geophysical applications: Computers & Geosciences, 85, Part A, 142–154."
---



# Abstract

Inverse modeling is a powerful tool for extracting information about the subsurface from geophysical data. Geophysical inverse problems are inherently multidisciplinary, requiring elements from the relevant physics, numerical simulation, and optimization, as well as knowledge of the geologic setting, and a comprehension of the interplay between all of these elements. The development and advancement of inversion methodologies can be enabled by a framework that supports experimentation, is flexible and extensible, and allows the knowledge generated to be captured and shared. The goal of this paper is to propose a framework that supports many different types of geophysical forward simulations and deterministic inverse problems. Additionally, we provide an open source implementation of this framework in Python called SimPEG (Simulation and Parameter Estimation in Geophysics, http://simpeg.xyz). Included in SimPEG are staggered grid, mimetic finite volume discretizations on a number of structured and semi-structured meshes, convex optimization programs, inversion routines, model parameterizations, useful utility codes, and interfaces to standard numerical solver packages. The framework and implementation are modular, allowing the user to explore, experiment with, and iterate over a variety of approaches to the inverse problem. SimPEG provides an extensible, documented, and well-tested framework for inverting many types of geophysical data and thereby helping to answer questions in geoscience applications. Throughout the paper we use a generic direct current resistivity problem to illustrate the framework and functionality of SimPEG.