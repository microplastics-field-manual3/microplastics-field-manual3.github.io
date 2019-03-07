---
layout: home
permalink: /case-study
title: "Case Study: Surveying a Marine Park in Tasmania"
excerpt: ""
image:
  feature: /banners/10_banner.jpg
---
{% include toc.html class="toc-left" h_min=2 h_max=2 %}

To illustrate some of the technical aspects of the design process, we plan a basline survey design for the Governor Island Marine Reserve off Bicheno on the East Coast of Tasmania to establish the status of biota. There are no zones of interest in this example, as the survey is not designed to test a management action (or other source of variation). The marine reserve is geographically complex with boundaries governed by natural land formations. The depth profile of the reserve is decreasing away from the land-based boundary, and there is less ‘shallow’ regions in the reserve than ‘deep’ ones.

 

We will present three designs. The first is a plain (vanilla) spatial design where all sites within the reserve are equally likely to be sampled. The second design intentionally samples shallow sites more often as these sites are likely to be more heterogeneous and diverse than their deeper water counterparts. The third type of design is when there are legacy (reference) sites in the area that should be resampled as it is considered important to create a time-series for this reserve. The spatial balance should then account for the locations of these legacy sites when finding the new sites. For more details on how to perform this third type of design, please see the *MBHdesign* vignette (by loading the *MBHdesign* package into R and typing vignette(‘MBHdesign’). Another good place to look is the paper describing the method: Foster et al. (2017). The inclusion of legacy sites in this example is somewhat artificial, as we have to first choose the legacy sites to incorporate. However, we hope that the process is illustrative., and stress that it mimics the consequences of real sampling with legacy sites – first the legacy sites are chosen randomly and then the new sites are chosen randomly around them (with spatial balance).

 

The example here is performed in R, an open source statistical platform. Importantly, there are other free and licensed software and programming languages that can also be used, depending on your proficiency and what is available to you. Some of the code may, at first glance, look a little daunting. Well, that’s R for you. Most of the lines written here are for plotting purposes and for reading in data. Since this is a document, we have taken some care with how the plots appear. This produces pretty(er) pictures but it also produces longer and more detailed code. Users should feel free to use the code below as a template, but please don’t blindly do so without thinking if the actions of the code is appropriate for your data. If you do re-use code, then please run checks to see if the code has done what you think that it ought to.

 

If you are new to R, then you could try to get an introduction by one of the many online tutorials (e.g.[ https://cran.r-project.org/doc/manuals/R-intro.html](https://cran.r-project.org/doc/manuals/R-intro.html)). That particular one is likely to be like R helpfiles (helpful but takes time) and it could be quite *dense*. Another option is the excellent book Venables and Ripley (2002), which introduces you to R *and* gives a good introduction to some types of data analysis. Other recommended introductions to R include: Crawley (2007); de Vries and Meys (2015). However, these are just suggestions, you should shop-around until you find a reference/tutorial that is at-your-level and in no time at all you will be reading in data, analysing it, plotting it, and summarising results.