---
title       : Coursera Class Project
subtitle    : Drug and Alcohol Death Rates in the US
author      : Pam Markt
job         : Data Analyst
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Drug and Alcohol Deaths in the United States

Much has been reported in the news concerning the growing epidemic of drug and alcohol use in the United States.

Have you ever wondered....

1. How many deaths occur each year due to drug and alcohol use?
2. In which areas of the US is drug and/or alcohol use the most impactful as a cause of death?
3. Have drug and alcohol deaths become more or less prevalent over the past several years?
4. How does your state compare to others in terms of drug and alcohol induced deaths?
5. Are certain racial groups impacted more by drug and alcohol deaths than others?

---

## US Death Rates from Drugs and Alcohol, by State

The data for this analysis was obtained from the Centers for Disease Control and Prevention, National Center for Health Statistics. Underlying Cause of Death 1999-2014 on CDC WONDER Online Database, released 2015. Data are from the Multiple Cause of Death Files, 1999-2014, as compiled from data provided by the 57 vital statistics jurisdictions through the Vital Statistics Cooperative Program. 

You can access this data directly here:
   http://wonder.cdc.gov/ucd-icd10.html 

---  

## Choropleth Maps
This app uses a choropleth map to visualize the prevalence of drug and alcohol induced deaths in 50 US states. Choropleths provide a quick and easy way to compare rates between different states. 

<img src="assets/fig/unnamed-chunk-1-1.svg" title="plot of chunk unnamed-chunk-1" alt="plot of chunk unnamed-chunk-1" style="display: block; margin: auto;" />
The data can be sliced in a variety of ways:

1. by Race (White, Black or African American, American Indian or Alaskan Native, Asian or Pacific Islander
2. by Cause (Alcohol-Induced deaths, Drug-Induced deaths, Both Alcohol and Drug Induced Deaths
3. by Year (current data includes 2012 - 2014)

--- 

Now try using the app -- 

You can access the app here:

http://pmarkt.shinyapps.io/DrugsandAlcohol

Detailed r code is available here:

http://github.com/pmarkt/DevelopingDataProducts
    
*Thanks for using my app!*

