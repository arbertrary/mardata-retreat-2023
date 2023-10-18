---
bibliography: example.bib
chalkboard: 'template-deck.json'
controls: true
csl: 'chicago-author-date.csl'
menu: true
title: Reproducible Semi-Immersive Analysis of Georeferenced Datasets
subtitle: ZBW Kolloquium
author: Armin Bernstetter
slideNumber: true
date: 24.10.2023
---

# {.columns}

## {.left style="text-align:center"}

![](assets/img/Bernstetter_Foto2.jpg)

## Armin Bernstetter {.right}

- M.Sc. Computer Science (University of Würzburg)
- GEOMAR Helmholtz Centre for Ocean Research Kiel
- MarDATA Helmholtz School for Marine Data Science
- Supervision: 
  - Prof. Dr. Isabella Peters (ZBW/CAU)
  - Dr. Tom Kwasnitschka (GEOMAR)


# IMMERSIVE ANALYTICS {style="text-align:center"}

# Visual Analytics

## Data Visualization {.fragment}

Representing data in a way to be understood by humans

## Visual Data Exploration {.fragment}

Exploring data by interacting with visualizations

## Sensemaking {.fragment}
Gaining knowledge and insight through data exploration

<!-- Problem: How to assess the value of visualization? -->
<!-- - Value of Visualization [@vanwijk2005value] -->

# {.notes}

Overall, we are located in the area of Human-Computer Interaction or Human-Data Interaction. I will not go fully into detail here because the terms themselves are self-explanatory enough for this talk.

In contrast to e.g. automated data analytics by machine learning or other computer-based techniques, visual analytics is performed by humans through interaction with visualized data.

# Immersion {.columns}

## {.top}

>- A feeling of being **immersed** and **present** in a virtual environment (**VE**)
- VEs can have varying degrees and aspects of immersion (spatial immersion, 3D/stereoscopy, head tracking, surround sound, ...)
- Examples: *CAVE*s, Head-Mounted Displays, Domes (e.g. *ARENA2*)

## {.bottom align=center .fragment style="display: inline-flex;  justify-content: space-evenly;"}

![The CAVE - Audio Visual Experience Automatic Virtual Environment. [@cruzneira1992cave]](assets/img/CAVE_Crayoland.jpg){width=30%}
![HTC Vive Pre Head-Mounted Display with two wireless handheld controllers (bottom) and two "Lighthouse" tracking stations (cubes)](assets/img/Vive_pre.jpeg){width=30%}


<!-- # ARENA2 Visualization Lab {.columns .fragments style="text-align:center"} -->
# ARENA2 Visualization Lab ![](assets/img/2019-10-16_Arena-0191-nikolas-linke_credit.jpg) {style="color:white"}


# Immersive and Collaborative Visual Analytics

## Immersive Analytics {.fragment}

Visual data exploration inside an immersive virtual environment

<!-- *(@marriott2018immersive, @skarbez2019immersive, @fonnet2021survey)* -->

## Collaborative Visual Analytics {.fragment}
<!-- *The shared use of computer-supported, (interactive) visual representations of data by more than one person with the common goal of contribution to joint information processing activities.*   -->

Joint visual data exploration by more than one person

Can be co-located or not, synchronous or asynchronous

<!-- *(@keel2006collaborative, @heer2008design, @isenberg2011collaborative)* -->


## ARENA2 {.example .fragment}

**Environment for co-located, synchronous collaboration inside a spatially immersive setting.**



# DEVELOPMENT FOR IMMERSIVE ANALYTICS {style="text-align:center"}

# Unreal Engine {.columns}

## {.left}

![](assets/img/UE_Logo_icon-only_black.svg){width=75%}

## {.right}

- Originally a video game engine
- Developed by Epic Games
- Today branded as *"powerful real-time 3D creation tool"*
- Free to use, source-available software
- Huge ecosystem

# Virtual Production

![Virtual production stage **"The Volume"** for The Mandalorian](assets/img/virtual_prod.png)


# Virtual Production Technology

::: {.column width=40%}

![](assets/img/ndisplay-setup.jpg)

:::

::: {.column width=60%}

<h2>nDisplay Plugin</h2>

- Rendering Unreal Engine content in real-time to a cluster of nodes and multiple displays
- Tiled walls, curved screens, CAVEs, Domes (e.g. ARENA2)
- Use motion tracking and input devices (e.g. game controllers) to manipulate camera perspective and movement in scene

:::


# DOING ACTUAL SCIENCE WITH IT

# ![](../assets/img/scientific_workflow.jpg)

# Field Work in Geology {.columns}

## Geological compass {.left}

![Wikimedia: Setup of a modern geological compass after Prof. Clar (Freiberger) ([https://en.wikipedia.org/wiki/Geological_compass](https://en.wikipedia.org/wiki/Geological_compass))](../assets/img/geocompass.jpg)

<!-- -------------------------------------------------------------------------------------------------- -->

## Field Notebook {.right}

![UCL Earth Sciences: "An Idiot's Guide to Fieldwork and Notebooks" by David Dobson ([https://www.ucl.ac.uk/earth-sciences-virtualfieldtrip/fieldskills/fieldsketching.html](https://www.ucl.ac.uk/earth-sciences-virtualfieldtrip/fieldskills/fieldsketching))](../assets/img/fieldnotebook.jpg)

## How to do this under water? {.bottom .fragment}
## Virtual fieldwork in immersive environments {.fragment}


# Cesium

- [https://cesium.com](https://cesium.com)
- Platform for creating 3D geospatial applications and processing georeferenced 3D data

## {style="text-align:center"}
![](assets/img/cesium.png){width=75%}

# Cesium for Unreal

![Cesium for Unreal Pipeline](assets/img/cesium-unreal.png)

# What does this mean?

Create georeferenced virtual and immersive environments which allow to interactively query geospatial data in a way yielding actual scientific insight.

For people playing Buzzword-Bingo right now: Digital Twin

# REPRODUCIBILITY AND PROVENANCE

# The visual analytics workflow {.columns}

##  {.left .fragment}

<br>
<br>

![Research question](assets/img/Picture1.jpg)



## {.center .fragment}

<br>
<br>

![Sensemaking through visual data exploration and analysis](assets/img/Picture2.jpg)


## {.right .fragment}

![Publication of insights and visualization](assets/img/Picture3.jpg)

<!-- ## There is always space for more Visualization Provenance in visual analytics workflows! {.fragment .bottom style="font-size:large"} -->
## If the insights and a static image of the visualization are being published, so should the process! {.fragment .bottom style="font-size:100%"}

[:include](b_Vis_Prov.md)


# References