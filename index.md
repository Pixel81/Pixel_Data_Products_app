---
title: "Data products - BMI calculation"
author: "Pixel81"
highlighter: highlight.js
output: html_document
job: Data Analyst
knit: slidify::knit2slides
mode: selfcontained
hitheme: tomorrow
subtitle: BMI calculation based on weigth and height with shinyapp
framework: io2012
widgets:
- mathjax
- bootstrap
- quiz
- shiny
- interactive
---

## Data products - BMI Calculator

This application is made for the data science specialisation.  
The goal is to made a shiny app working online.  
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

This code show how calculation work.

```r
BMI <- function (weigth,height) 
       as.numeric(weigth) * 10000 / (as.numeric (height) * as.numeric (height))

Weigth <- 80
Height <- 180
BMI_result <- BMI(Weigth, Height)
print(BMI_result)
```

```
## [1] 24.69136
```

--- .class #id 
