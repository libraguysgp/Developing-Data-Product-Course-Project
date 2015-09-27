Developing Data Products - Course Project
========================================================
author: Kelvin Tan
date: 28 September 2015

Basic Introduction to ggplot
========================================================

This presentation is being created as part of the peer assessment for the coursera developing data products class. The assignment is geared toward ensuring the following concepts were well understood by the students

- **shiny** to build data product application
- **R-Presentation or slidify** to create data product related presentations

The Application
========================================================
To display the understanding of using **shiny** to build an application, a simple application called **Basic Introduction to ggplot2** has been developed and deployed at: 
https://libraguysgp.shinyapps.io/DevelopingDataProductsProject

The application allows the user to:

1.Modify the choice in any of the 5 selection widgets

2.Observe how the displayed plot changes

3.Observe the updated ggplot command displayed beneath the plot, which can be copied/pasted directly into R 

The Data
========================================================
type: sub-section

This application provides an interactive basic introduction to plotting with the ggplot2 package available in R. The application uses the mpg fuel economy data from 1999 and 2008 for 38 popular models of car. The application provides 5 selection widgets to choose the geometry type of the plot, the x variable, the y variable, the colour variable, and the facet_wrap variable.


Source code for the project is available on the [GitHub](https://github.com/libraguysgp/DevelopingDataProductsProject).

Data
=====================

```r
summary(cars)
```

```
     speed           dist       
 Min.   : 4.0   Min.   :  2.00  
 1st Qu.:12.0   1st Qu.: 26.00  
 Median :15.0   Median : 36.00  
 Mean   :15.4   Mean   : 42.98  
 3rd Qu.:19.0   3rd Qu.: 56.00  
 Max.   :25.0   Max.   :120.00  
```

Slide With Plot
========================================================

![plot of chunk unnamed-chunk-2](Developing_Data_Product_Course Project_Presentation-figure/unnamed-chunk-2-1.png) 
