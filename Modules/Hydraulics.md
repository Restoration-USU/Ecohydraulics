---
title: Hydraulics
weight: 2
---

# Background

We need a basic understanding of fluvial hydraulics for the purposes of how they define physical habitat for fish. For this lecture we really need to understand just enough physics (well fluid mechanics really) to be dangerous enough to interpret where the characterization of hydraulic habitat (i.e., velocity and depth patterns) occurs and how it matters to fish. Normally, to get to the point of running hydraulic models (likely as a senior in a civil engineering program) you would traditionally need the following prerequisites before being able to take a "Hydraulics" or "Open Channel Flow" class where you might run a one-dimensional hydraulic model:
- Fluid Mechanics, which typically requires prerequisties of:
  - Statics &  Dynamics, which require prerequisites of:
    - Physics (Mechanics) - Understand force balances (i.e. hydraulics as a driving forces and resisting forces problem)
    - Differential Equations & Linear Algebra (i.e., Advanced Calculus) to follow the derivations of equations of motion and solve systems of equations    

And even then, you probably still would not be taught how to run a two-dimensional or three-dimensional hydraulic model (as are now typically used in ecohydraulics). Since most of you do not have three years to take all these courses, we will do a really rough treatment to get you the basics. 

In the same way that you might describe the weather based on measures of precipitation and temperature (with climate descrbing long-term tendencies and paterns), in open channel flow (i.e. a free surface as opposed to pressurized flow in pipes) treatments hydraulics we can define aquatic habitat based on measures of flow fields of velocity vectors and spatial paterns of water depth.   

------
# Resources

## Lecture & Slides

I have a similar problem in my [WATS 5150 - Fluvial Geomorphology](https://riverscapes.github.io/Fluvial-Geomorphology/) class where most students need to understand hydraulics for its application to understanding the topic at hand - in that case fluvial geomorphology.  I present a similarly distilled version of hydraulics there. In Fluvial Geomorphology [Module 5](https://riverscapes.github.io/Fluvial-Geomorphology/Course_Topics/module-05) a very geomorphic-centric coverage of hydraulics is provided. That is, in the same way here we are interested in hydraulics for what it means to provision of aquatic habitat for biota, in that treatment we are interested in how that governs the fluid motion from the perspective of what can do geomorphic work.  Here I use a different set-up (i.e., intro), but the same core treatment of the subject.

<div class="row small-up-2 medium-up-2">


  <div class="column">
    <div class="card">


      <div class="card-section">
        <h4>Hydraulics Lecture </h4>
        <div class="responsive-embed"> 

<iframe width="560" height="315" src="https://www.youtube.com/embed/videoseries?list=PL0ZiZg4rilzLbJr8un8KylreiwApfYH54" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<br>


</div>
<i class="fa fa-clock-o" aria-hidden="true"></i> 1 hour and  34 minutes <i class="fa fa-youtube-play" aria-hidden="true"></i>
      </div>
    </div>
  </div>

  <div class="column">
    <div class="card">


      <div class="card-section">
        <h4>Slides</h4>
    <div align="center">
        	<a href="https://s3.us-west-2.amazonaws.com/etalweb.joewheaton.org/Courses/Ecohydraulic/2022/WATS6900_Ecohydraulics_2020_Module_02.pdf" target="_blank"><img src="{{ site.baseurl }}/assets/images/lectures/2022_Ecohydraulics_Module_02.png"></a>
        	</div>
        
        <br><br> <i class="fa fa-file-pdf-o" aria-hidden="true"></i> <a href="https://s3.us-west-2.amazonaws.com/etalweb.joewheaton.org/Courses/Ecohydraulic/2022/WATS6900_Ecohydraulics_2020_Module_02.pdf" target="_blank">Module 2  - Slides</a>
        
      </div>
    </div>

  </div>
</div>



## 2020 Slides
[<img class="float-right" src="{{ site.baseurl }}/assets/images/lectures/2020_Ecohydraulics_Week_02.png">](https://s3-us-west-2.amazonaws.com/etalweb.joewheaton.org/Courses/Ecohydraulic/2020/Lectures/WATS6900_Ecohydraulics_2020_Week02.pdf)

- <i class="fa fa-file-pdf-o" aria-hidden="true"></i> [Week 2: Introduction to Hydraulics](https://s3-us-west-2.amazonaws.com/etalweb.joewheaton.org/Courses/Ecohydraulic/2020/Lectures/WATS6900_Ecohydraulics_2020_Week02.pdf) 

----
## Good References on Hydraulics

### Introductory Treatments of Hydraulics

#### "The Flow" from Wilcock et al. (2009) Sediment Transport Primer
In Wilcock et al.'s (2009) treatment of "The Flow" on pages 20-24 is a nice, approachable, concise and traditional treatment of one-dimensional hydraulics:

-  Wilcock P, Pitlick J, Cui Y. 2009. [Sediment transport primer: estimating bed-material transport in gravel-bed rivers]. Department of Agriculture, Forest Service, Rocky Mountain Research Station: Fort Collins, CO

#### Chapter Five from "Geomorphic Analysis of River Systems"

Skim [Chapter 5](https://ebookcentral-proquest-com.dist.lib.usu.edu/lib/usu/reader.action?docID=1032536&ppg=81)   of Fryirs & Brierley (2013) on "Impelling and Resisting Forces in River Systems", which some of you will have already read from Fluvial Geomorphology. 

- Fryirs KA, Brierley GA. 2013. [Geomorphic Analysis of River Systems: An Approach to Reading the Landscape (Links to an external site.)](https://www.wiley.com/en-au/Geomorphic+Analysis+of+River+Systems%3A+An+Approach+to+Reading+the+Landscape-p-9781405192743), First Edition. Blackwell Publishing Ltd.: Chichester, U.K.

-------

### Dingman (2008)
- <a href="https://global.oup.com/us/companion.websites/9780195172867/"><img class="float-right" src="{{ site.baseurl }}/assets/images/covers/dingman_cover.jpg"></a> Dingman SL. 2008. [Fluvial Hydraulics](https://books.google.com/books?id=Y0ORT-1sFDgC&pg=PA8&dq=fluvial+hydraulics&hl=en&ei=Qzb0TNTvKKCBnAekv6mQCw&sa=X&oi=book_result&ct=result&resnum=1&ved=0CDQQ6AEwAA#v=onepage&q&f=false). Oxford University Press: New York, 576 pp.  ISBN-13: 978-0195172867 
  - You can read two chapters (not all) of the text as a Google Book [here](https://books.google.com/books?id=Y0ORT-1sFDgC&pg=PA8&dq=fluvial+hydraulics&hl=en&ei=Qzb0TNTvKKCBnAekv6mQCw&sa=X&oi=book_result&ct=result&resnum=1&ved=0CDQQ6AEwAA#v=onepage&q&f=false).
  - The book comes with some [downloadable materials here](https://global.oup.com/us/companion.websites/9780195172867/).
  - The book is available on reserve in the library.

### Bates, Lane & Ferguson (2005)
-  <a href="https://global.oup.com/us/companion.websites/9780195172867/"><img class="float-right" src="{{ site.baseurl }}/assets/images/covers/Bates.jpg"></a> Bates PD, Lane SN and Ferguson RI (Eds). 2005. Computational Fluid Dynamics: Applications in Environmental Hydraulics. Computational Fluid Dynamics. John Wiley & Sons, Ltd, 540 pp. DOI: [10.1002/0470015195](https://dx.doi.org/10.1002/0470015195)
  - EBook from Our Library
  - You can read some of the text as a Google Book [here](http://books.google.com/books?id=1cNoyZO1FEYC&printsec=frontcover&dq=Computational+Fluid+Dynamics:+Applications+in+Environmental+Hydraulics&source=bl&ots=2jxFphLj4R&sig=bZZXuiHFHxMvrdBrammUEM5IxBM&hl=en&ei=cEH9TPTvB6XtnQehsMDICg&sa=X&oi=book_result&ct=result&resnum=4&ved=0CDwQ6AEwAw#v=onepage&q&f=false).

### Chanson (2004)
- <a href="https://global.oup.com/us/companion.websites/9780195172867/"><img class="float-right" src="{{ site.baseurl }}/assets/images/covers/Chanson.gif"></a> Chanson H. 2004. [The Hydraulics of Open Channel Flow: An Introduction](http://www.sciencedirect.com/science/book/9780750659789). Elsevier Butterworth Heinemann: Oxford, 585 pp.
  - Available from our library in hardcopy
  - You can read some of the text as a Google Book here
  - We will read some of the chapters out of here as assigned reading
  - Download (for purchase) PDFs of the chapters here
  - Glossary & List of Symbols from Chanson (2004; above) pp. xx - xlvii (view most of it [here](http://www.sciencedirect.com/science/book/9780750659789)) 

### Chow (1959)
- Chow, V.T. (1959) [Open-Channel Hydraulics](http://web.ipb.ac.id/~erizal/hidrolika/Chow%20-%20OPEN%20CHANNEL%20HYDRAULICS.pdf). New York : McGraw-Hill, 680 pp.


   


-----
## More In Depth Slides

### Old Fluvial Hydraulics Class
In the old [Fluvial Hydraulics & Ecohydraulics](http://fluvial.joewheaton.org/) class, a more thorough introduction is provided with following topics:
1. [Equations of Motion](http://fluvial.joewheaton.org/2014-course-topics#TOC-Equations-of-Motion)
2. [Velocity Profiles & Flow Resistance](http://fluvial.joewheaton.org/2014-course-topics#TOC-Velocity-Profiles-Flow-Resistance)
3. [Introduction to Energy & Hydraulic Jumps](http://fluvial.joewheaton.org/2014-course-topics#TOC-Introduction-to-Energy-Hydraulic-Jumps)
4. [Introduction to 1D Modeling - Energy and Gradually Varied Flow](http://fluvial.joewheaton.org/2014-course-topics#TOC-Introduction-to-1D-Modeling---Energy-and-Gradually-Varied-Flow)
5. [1D HEC RAS Modeling](http://fluvial.joewheaton.org/2014-course-topics#TOC-1D-HEC-RAS-Modeling)
6. [2D Hydraulic Modeling](http://fluvial.joewheaton.org/2014-course-topics#TOC-2D-Delft3D-Hydraulic-Modelling)



## CHaMP Specific Resources

- Nahorniak M, Wheaton J, Volk C, Bailey P, Reimer M, Wall E, Whitehead K, Jordan C. 2018. How do we efficiently generate high-resolution hydraulic models at large numbers of riverine reaches? Computers & Geosciences 119 : 80–91. DOI: [10.1016/j.cageo.2018.07.001](https://dx.doi.org/10.1016/j.cageo.2018.07.001)

## Reading Hydraulics

Some geese surfing the Glenwood wave... they're clearly reading hydraulics just to have fun:
<div class="responsive-embed">
<iframe width="560" height="315" src="https://www.youtube.com/embed/xQfSx6zEey0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>