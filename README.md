# tableau-drug-study

Author:  Erin James Wills, ejw.data@gmail.com  

![Analysis of Mouse Drug Data](./images/drug-efficacy-tableau.png)  
<cite>Photo by [Louis Reed](https://unsplash.com/@_louisreed?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText) on [Unsplash](https://unsplash.com/s/photos/lab-rat?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText)</cite>  

<br>  

## Overview  
This repo includes a tableau analysis of a drug efficacy study comparing the effects of multiple cancer treatment drugs within a population of cancer inoculated mice.  A tumor was grown in each mouse such that each mouse in the study had a 45 mm**3 tumor at day zero of the study.  Measurements of the tumor volume and cancer spread (metastatic sites) were taken every 5 days until the study concluded after 45 days.  Initial goals were to compare the treatment outcomes by analyzing the volume and metastatic site growth and any outliers over the course of the study.  A second review was added to the analysis to more critically examine potential reasons that two drugs performed better than the other treatments.  A third review will also be added in the future that will consider the outcomes relative to the placebo population included in the dataset.     

<br>  

## Technologies  
*  Tableau

<br>

## Methods  
*  Scatter plots
*  Line charts 
*  Line charts with errorbars  
*  Bar charts   
*  Stacked bar charts
*  Histograms
*  Box plots  
*  Determination of outliers
*  Central Tendency
*  Linear Regression  

<br>

## Data Source  
*  The datasource is unknown, exepct that Trilogy Education Services may have generated the dataset for their bootcamps.  
*  The data set consists of two files that contain information about the mice used in the study and tumor volume and metastatic site measurements taken throughout the 45 day study.  There are 249 mice specimens and 1893 specimen measurements.  
*  The data can be accessed in the `data` folder as well as an older pair of files containing less information.  

<br>  

## Setup and Installation  
1. Open the `DrugTreatments_v2022.1.twbx` in Tableau
1. Data can be found in the https://github.com/ejw-data/matplotlib-drug-eval repo.  



<br>

## Analysis  

> This analysis includes the results of two reviews.  

From the initial review of data, it appeared that two drug treatments showed promising outcomes.  Capomulin and Ramicane were the only two drugs that showed a decrease in tumor size (Fig.1, Fig.4) and reduced rates of development of metastatic cancer sites (Fig.2). The mouse survival rate was also much better for these drugs (Fig.3).  From this data, Capomulin and Ramicane were determined to be `potential` target drugs for this cancer.   

After receiving additional information about each mouse and further investigation, the previous conclusions, are now doubted.  After looking at the mouse populations, the mice used for Capomulin and Ramicane had one similarity that none of the other treatment or control groups had - lower weight mice.  The age distribution did not seem to influence the outcome of the study; although, some of the ages did seem somewhat low.  The average weight for mice treated with Capomulin had on average a 24.7 gram intial weight and the mice treated with Ramicane had a 24.6 gram average weight.  All other groups of mice had an average weight of 27.2 or greater.  The distribution of weights showed a distinct difference (Fig.5, Fig.6).  The number of metastatic sites compared to initial mouse weight (Fig.7) also showed significant differences compared to the other mice.    It is uncertain if the drug or initial weight or a combination of the two factors caused a reduction in tumor volume and reduced cancer spread.  

Further analysis will be performed using the control group (placebo group).


<figure>

![Metastatic Sites](./images/dashboard_example.png)

<figcaption>Fig.1 - Drug Treatment Dashboard (DRAFT)</figcaption>
</figure>
<hr>

<br>

