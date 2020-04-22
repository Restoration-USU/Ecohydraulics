---
title: Riverscapes Network Models
weight: 10
---

# Background

## Synopsis of Topic
Network models of riverscapes are what are required to be able to support life cycle modeling at the population scale and act as network co-variates to upscale site-scale information. In this topic we introduce some of the tools available to support these efforts. 

------
# Resources

## 2020 Slides
[<img class="float-right" src="{{ site.baseurl }}/assets/images/lectures/2020_Ecohydraulics_Week_12.png">](https://s3-us-west-2.amazonaws.com/etalweb.joewheaton.org/Courses/Ecohydraulic/2020/Lectures/WATS6900_Ecohydraulics_2020_Week12.pdf)

- <i class="fa fa-file-pdf-o" aria-hidden="true"></i> [Week 12: Riverscape Network Models](https://s3-us-west-2.amazonaws.com/etalweb.joewheaton.org/Courses/Ecohydraulic/2020/Lectures/WATS6900_Ecohydraulics_2020_Week12.pdf) 

## 2020 Lectures

### Reminder of What we need
In this < 5 minute video we position network modelling in the context of the broader ecohydraulics motivation of this class. 

<div class="responsive-embed">
<iframe width="560" height="315" src="https://www.youtube.com/embed/W50OGuGu4Dc" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>
### Network Scale Assessments

#### VBET – Valley Bottom Extraction Tool

The valley bottom is the entry point to understanding a riverscape. Fortunately, we have a tool, which approximates the mapping of this with freely available national data. Currently, [VBET](http://rcat.riverscapes.xyz/Documentation/Version_2.0/VBET/2-VBET.html) is  buried in [RCAT](http://rcat.riverscapes.xyz/), but that is [changing](https://github.com/Riverscapes/vbet) within the year. A high level overview is provided in this 6 minute video:

<div class="responsive-embed">
<iframe width="560" height="315" src="https://www.youtube.com/embed/B92jH50kfn8" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

#### Confinement Tool
The entry point in [River Styles]({{ site.baseurl }}/Modules/RiverStyles) reach typing is valley setting. Valley setting is more than just the valley bottom, it is differentiated based on degree of lateral confinement. The [Confinement Tool](http://confinement.riverscapes.xyz/)  is currently its own tool, but has also been part of the [Geomorphic Network Assessment Tool](http://gnat.riverscapes.xyz/). This circa 13 minute video presents the confinement tool as applied in the O'Brien et al. (2019) paper. 

<div class="responsive-embed">
<iframe width="560" height="315" src="https://www.youtube.com/embed/O5-01y2MWCU" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

#### RCAT – Riparian Condition Assessment Tool
An example of one way we can look at riverscape condition and geoindicators of geomorphic condition is looking at riparian conditions. The  [Riparian Condition Assessment Tool - RCAT](http://rcat.riverscapes.xyz/) is one of the network tools available to assess different components of riparian condition as explained in this < 10 minute video:

<div class="responsive-embed">
<iframe width="560" height="315" src="https://www.youtube.com/embed/om9xYoMps5g" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

#### BRAT – Beaver Restoration Assessment Tool
In many riverscapes, beaver dams can have a profound impact on riverscape condition, and subsequently fish capacity and survival. The [Beaver Restoration Assessment Tool - BRAT](https://brat.riverscapes.xyz) is one of the network tools available to assess the capacity of the network to support dam building activity by beaver.

<div class="responsive-embed">
<iframe width="560" height="315" src="https://www.youtube.com/embed/XPs61RUnYVY" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

### Riverscapes Consortium – Where we’re going
<a href="https://riverscapes.xyz"><img class="float-left" src="https://riverscapes.xyz/assets/images/rc/RiverscapesConsortium_Logo_Black_BHS_200w.png"></a>
The current reality of the state of network models, is that a) the entire process to support life cycle modelling as envisioned in the Wheaton et al. (2017) paper is only partially realized. In other words, many of the network co-variates required are manually produced network layers. Part of what the [Riverscapes Consortium](https://riverscapes.xyz) has been working on is building the capacity to support this process with its tools.

For this class, watch this:
<div class="responsive-embed">
<iframe width="560" height="315" src="https://www.youtube.com/embed/eAtfxtVrm3c" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

#### What is the Consortium?
In this less than five minute video we introduce the Riverscape Consortium.
<div class="responsive-embed">
<iframe width="560" height="315" src="https://www.youtube.com/embed/mfyhjVfECf4" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

#### Riverscape Consortium Tools & Standards
In this 20 minute video we introduce how the Riverscape Consortium sets standards for [tool development](https://riverscapes.xyz/Tools/) and the idea of [tool-grade](https://riverscapes.xyz/Tools/#model-discrimination). This is important to understanding and managing expectatons around what a tool can do, versus what it could be able to do with investment in development and deployment.

<div class="responsive-embed">
<iframe width="560" height="315" src="https://www.youtube.com/embed/wcT4vSZmQa0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

#### Riverscape Projects 
We developed a data standard for packaging up riverscapes analyses (i.e. outputs of any RC compliant tool) into [riverscapes projects](https://riverscapes.xyz/Tools/Technical_Reference/Documentation_Standards/Riverscapes_Projects/). This five minute video explains the basics.

<div class="responsive-embed">
<iframe width="560" height="315" src="https://www.youtube.com/embed/YvWwaFFzulo" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

#### RAVE
One of the real advantages of having [riverscapes projects](https://riverscapes.xyz/Tools/Technical_Reference/Documentation_Standards/Riverscapes_Projects/), is the ability to share that data with GIS users for them to explore in GIS. We do this with a simple Add-In to GIS called [RAVE](http://rave.riverscapes.xyz/). We take a test-drive of RAVE in this < five minute video:

<div class="responsive-embed">
<iframe width="560" height="315" src="https://www.youtube.com/embed/9gFvuRWC2AI" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

#### Riverscape Dataset Status Ideas
In the same way that expectations need to be managed for Riverscape Tools, it is important to provide metadata context for datasets. In this 8 minute video, we lay out some concepts we're exploring with respect to [dataset status](https://riverscapes.xyz/Data_Warehouses/#dataset-discrimination):
<div class="responsive-embed">
<iframe width="560" height="315" src="https://www.youtube.com/embed/msBhCp6vCsc" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

#### Riverscape Consortium Warehouses
The Riverscapes Consortium organizes and serves data via [data warehouses](https://riverscapes.xyz/Data_Warehouses/) . These data warehouses provide access to both the underlying data (packaged in [riverscapes projects](https://riverscapes.xyz/Tools/Technical_Reference/Documentation_Standards/Riverscapes_Projects/)) as well as making these data explorable via warehouse explorers or interactive web maps. In this 8 minute video, we show off what these warehouses buy you in terms of housekeeping and reaching broader audiences. 

<div class="responsive-embed">
<iframe width="560" height="315" src="https://www.youtube.com/embed/iuYYsJiTQRI" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

### Take Aways
Here we wrap up the Network Tools discussion.
<div class="responsive-embed">
<iframe width="560" height="315" src="https://www.youtube.com/embed/7MgmiNbCfzk" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

--------
## Reading

<a href="https://www.zotero.org/groups/2441047/ecohdraulics_wats_6900/collections/77RC26IK"><img class="float-left" src="{{ site.baseurl }}/assets/images/logos/Zotero.png"></a>  See [Ecohydraulics Literature - Zotero collection](https://www.zotero.org/groups/2441047/ecohdraulics_wats_6900/collections/77RC26IK)  hosted on Zotero and available for download. 

- Gilbert JT, Macfarlane WW, Wheaton JM. 2016. The Valley Bottom Extraction Tool (V-BET): A GIS tool for delineating valley bottoms across entire drainage networks. Computers & Geosciences 97 : 1–14. DOI: [10.1016/j.cageo.2016.07.014](https://dx.doi.org/10.1016/j.cageo.2016.07.014).
- Macfarlane WW, Wheaton JM, Bouwes N, Jensen ML, Gilbert JT, Hough-Snee N, Shivik JA. 2017. Modeling the capacity of riverscapes to support beaver dams. Geomorphology 277 : 72–99. DOI: [10.1016/j.cageo.2016.07.014](https://dx.doi.org/10.1016/j.geomorph.2015.11.019).
- O’Brien GR, Wheaton JM, Fryirs K, Macfarlane WW, Brierley G, Whitehead K, Gilbert J, Volk C. 2019. Mapping valley bottom confinement at the network scale. Earth Surface Processes and Landforms : esp.4615. DOI: [10.1002/esp.4615](https://dx.doi.org/10.1002/esp.4615).
- William W. Macfarlane, Jordan T. Gilbert, Martha L. Jensen, Joshua D. Gilbert, Peter A. McHugh, Nate Hough-Snee, Joseph M. Wheaton, Stephen N. Bennett. 2016. Riparian vegetation as an indicator of riparian condition: detecting departures from historic condition across the North American West. Journal of Environmental Management DOI: [10.1016/j.jenvman.2016.10.054](https://dx.doi.org/10.1016/j.jenvman.2016.10.054).


## Other Resources

In lecture we discussed both [BRAT](http://brat.riverscapes.xyz) & [RCAT](http://rcat.riverscapes.xyz) as examples for geoindicators for condition and recovery potential. 

<div align="center">
	<a class="button alert" href="http://brat.riverscapes.xyz"><img src="{{ site.baseurl }}/assets/images/BRAT_Logo-wGrayTxt.png"></a>
	<a class="button alert" href="http://rcat.riverscapes.xyz"><img src="{{ site.baseurl }}/assets/images/RCAT_Logo-wTxt.png"></a>
</div>