---
title: Ecohydraulics - Fuzzy Models
weight: 5
---

We move into fuzzy inference systems this week as another more flexible, less sensitive and more powerful version of habitat suitability models when compared with their habitat suitability curve driven counterparts.  

------
# Resources

## Lecture & Slides

<div class="row small-up-2 medium-up-2">


  <div class="column">
    <div class="card">


      <div class="card-section">
        <h4>Fuzzy Habitat Suitability Models - Lecture </h4>
        <div class="responsive-embed"> 

<iframe width="560" height="315" src="https://www.youtube.com/embed/videoseries?list=PL0ZiZg4rilzL7-6hcB59WgV38Vp7wzyyF" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<br>

</div>
<i class="fa fa-clock-o" aria-hidden="true"></i> 1 hour and  23 minutes <i class="fa fa-youtube-play" aria-hidden="true"></i> total <br> First three suggested (~48 minutes); Last 35 minutes case study for CHaMP specifics (optional)
      </div>
    </div>
  </div>

  <div class="column">
    <div class="card">


      <div class="card-section">
        <h4>Slides</h4>
    <div align="center">
        	<a href="https://s3.us-west-2.amazonaws.com/etalweb.joewheaton.org/Courses/Ecohydraulic/2022/WATS6900_Ecohydraulics_2020_Module_05_FIS.pdf" target="_blank"><img src="{{ site.baseurl }}/assets/images/lectures/2022_Ecohydraulics_Module05.png"></a>
        	</div>
        
        <br><br> <i class="fa fa-file-pdf-o" aria-hidden="true"></i> <a href="https://s3.us-west-2.amazonaws.com/etalweb.joewheaton.org/Courses/Ecohydraulic/2022/WATS6900_Ecohydraulics_2020_Module_05_FIS.pdf" target="_blank">Module 5  - Slides</a>
        
      </div>
    </div>

  </div>
</div>

--------------
## Homework Assignment

You are going to build (from scratch) a fuzzy inference system for a spawning habitat suitability model for steelhead (based on your "expert" judgement). We're not seeking the perfect model as much as we are building famliarity with the steps in building the FIS and applying it to specific reach under a specific flow condition (represented by a steady state hydraulic simulation from one reach). 

### 1. Build Inference System & Specify Membership Functions
We started this homework in class. You were asked to come to class (see <a href="https://youtu.be/qTzwbiibtZs?t=318">lecture</a>) with a Google Sheet spreadsheet with a table representing your inference system.
- Open up Google Sheets in Browser
- Make an inference system (i.e. rule table) for a two input fish habitat model for spawning steelhead
- Use inputs & categories of:
  - **Depth**: Shallow, Medium, Deep
  - **Velocity**: Slow, Medium, Fast
- Use output of Habitat Suitability with categories of Poor, Moderate, Good. 	
Note - _You can add more categories or tweak the above, but you will need to adjust number of rules._

You will submit a shared-link to your Google Sheet.

### 2. Translate your FIS into a real FIS
The [GCD](http://gcd.riverscapes.xyz) has a [FIS Library](http://gcd.riverscapes.xyz/Help/customize-menu/fis-library.html) that uses the same standard as the [Matlab Fuzzy Logic Toolbox](https://www.mathworks.com/products/fuzzy-logic.html). Similar libraries exist for R (e.g. [FuzzyR](https://cran.r-project.org/web/packages/FuzzyR/index.html)) and Python (e.g. [SciKit-Fuzzy](https://pythonhosted.org/scikit-fuzzy/overview.html)). 

In the [video below](https://youtu.be/BamrMa6oLOE) <i class="fa fa-youtube-play" aria-hidden="true"> </i>, we show you how to do this using the text editor in the FIS Library of GCD (you can also do it in any text editor). **CAUTION**, the FIS needs to be formatted exactly the same way and extra spaces or breaks will cause it to crash. For this reason, we edited an existing [`TS_ZError_PD_SLP_deg.fis`](https://raw.githubusercontent.com/Riverscapes/fis-dem-error/master/BySurveyType/TS/TS_ZError_PD_SLPdeg.fis) for a DEM error model just to get us started on proper syntax. 

You will not need to submit your `*.fis` text file as when you sumbit a zip file of your GCD project, it will contain a copy of the file. 

### 3. Apply your FIS to a real CHaMP Survey of a Real Site

<div class="row small-up-2 medium-up-2">


  <div class="column">
    <div class="card">


      <div class="card-section">
        <h4>Instructions for running your FIS in GCD</h4>
    <p>
    This tutorial is for using <a href="http://gcd.riverscapes.xyz/">GCD</a> and <a href="http://rave.riverscapes.xyz">RAVE</a> AddIns to ArcGIS 10.X. You can use the GCD StandAlone to get model to work, and forgo the GIS symbology (you can manually symbolize this). You will need a <a href="">free account</a> that you create on <a href="http://data.riverscapes.xyz">data.riverscapes.xyz</a> and request access to the <a herf="https://data.riverscapes.xyz/#/AsotinIMW">Asotin Warehouse</a>. 
    </p>
    <ol>
        		<li>Download a CHaMP Topo Survey from <a herf="https://data.riverscapes.xyz/#/AsotinIMW">Asotin Warehouse</a>. See <a href="https://youtu.be/zC4VomCv38c">this video <i class="fa fa-youtube-play" aria-hidden="true"> </i></a> if you need a reminder as to how.</li>
        <li>Download a CHaMP hydraulic model for the exact same visit (i.e. same survey year and site). </li>
        <li> Load your *.fis file into the GCD FIS Library.</li>
        <li> Make a new GCD project.</li>
        <li> Add your DEM from the Topo project to the GCD project. </li>
        <li> Add your depth and velocity rasters as associated surfaces to the DEM.</li>
        <li> Calculate and "Error Surface" using your FIS and the depth and velocity rasters as inputs to run your model.</li>
       </ol>
        
      </div>

</div>
  </div>
   <div class="column">
    <div class="card">


      <div class="card-section">
        <h4>Building a Fuzzy Ecohydraulic Model </h4>
        <div class="responsive-embed"> 

<iframe width="560" height="315" src="https://www.youtube.com/embed/BamrMa6oLOE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<br>

</div>
<i class="fa fa-clock-o" aria-hidden="true"></i> 18 minutes <i class="fa fa-youtube-play" aria-hidden="true"></i> total <br> Tutorial on using GCD to "run" your FIS
   </div>
    
  </div>
</div>
</div>

You will turn a zipped up copy of your [GCD project](http://gcd.riverscapes.xyz/Concepts/projects.html) with the ecohydraulic model and results in it. 

### 4. Answer the Following Questions

1. Does your model produce coherent results (spatially) that make sense? Explain why or why not.
2. How would you calculate total weighted useable area for your simulation? (optional to calculate it)
3. How would you explore if habitat suitability is changing at the Asotin CHaMP site you chose?

### What to turn in:

1. Please include a 1-2 page  write up summary. Explain what you did, and include (a) figure(s) that shows your inputs (velocity and depth maps) as well as your output. In the summary answer the above questions. 
2. Also submit a shared-link to your Google Sheet.
3. Submit a zip file of your GCD project.   

-------------
## Alternative Method using Habitat Model Software

<a href="https://habitat.northarrowresearch.com/"><img class="float-right" src="{{ site.baseurl }}/assets/images/pics/HSM_NAR.png"></a> Another way to complete both the assignment above and apply some habitat suitability curves is to use the [Habitat Model Software](https://habitat.northarrowresearch.com/), which we had [North Arrow Research](https://northarrowresearch.com/) develop back in 2015. 

<a href="https://habitat.northarrowresearch.com/"><img src="{{ site.baseurl }}/assets/images/pics/HSM_Screenshot.png"></a>

The stand-alone has no mapping interface, but allows you to work with `*.csv`, `*.shp` shapefiles, or rasters as inputs and outputs, and allows the specification of your own FIS models (also has some pre-loaded) as well as HSCs and HSIs if you want to use those. In the video below, I was unable to get the rasters to work, but was able to get the CSVs to work. This software also allows easy batching of multiple habitat models for the same runs. 

<div class="resoponsive-embed">
<iframe width="560" height="315" src="https://www.youtube.com/embed/6lnihvvGLJo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

Post any issues you [find here](https://github.com/NorthArrowResearch/habitatmodel/issues).
