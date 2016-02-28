---
title       : Data products - BMI calculation
subtitle    : BMI calculation based on weigth and height with shinyapp
author      : Pixel81
job         : Data Analyst
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [mathjax]            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Data products - BMI Calculator

This application is made for the data science specialisation.  
THe goal is to made a shiny app working online.  
My product is a simple BMI calculator, based on the weigth and height of the user.

--- .class #id 

## BMI calculation - Usage
The application is very simple to illustrate the computation.  
1. Put your weigth with the cursor (in kg, between 40 and 200)  
2. Put your height also, with the second cursor (in centimeters, between 100 and 250)  
3. The server is reactive, so it give you instantanly the BMI result  
4. You can compare the result with a classification done by the inventor of the BMI.

--- .class #id 

## BMI calculation - Formula
The BMI calculation is based on weigth and height of the user.  
$$ 1000 * weigth / heigth^2 $$  
with  
- weigth in kilogram  
- height in centimeters


--- .class #id 

## BMI calculation - Example


--- .class #id 