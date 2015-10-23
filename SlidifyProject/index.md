---
title       : Higher Horse Power Lower the MPG
subtitle    : My App for Guessing MPG
author      : Sudeep
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Introduction

1. This app alows the user to guess the gas consumption of a car based on the power required.
2. Higher power means higher use of gas and lower MPG.
3. Power of the cars are determined by the horsepower required.
4. Number of cylinders in cars are also closely related to the power- bigger the horse power higher is the cylinder.

--- 

## The app

Here is the simple description of my app

1.  The out put is graphical and interactive.
2.  You can choose your horsepower requirement in the slider-The redline shifts 3.  accordingly.
4.   The blue line is the represents the average MPG for the given horsepower.
5.   The intersection between the red line and blue line can be easily seen.


---

## The Data


Source of data is the 'mtcars' available with R.

1.  I used the data to make my app.
2.  The graph displayed is based on this data

```r
min(mtcars$hp); max(mtcars$hp) 
```

```
## [1] 52
```

```
## [1] 335
```

```r
min(mtcars$mpg); max(mtcars$mpg) 
```

```
## [1] 10.4
```

```
## [1] 33.9
```

---

## Uses of the app

I tried to keep it simple and intutive to make is usefull as a first rough estimate. It is elaborated below.


1.  It can be used to guess the gas consumption for your horsepower requirement.

2.  Higher horsepower may be required if you want your car to haul big load and if you travel long distances frequenty.

3. Lower horspower can be sufficiently enough for you, if you are in town, require efficiency and lower gas bills.



----
## The link to my app

This is a link to my app.


Please use it and see how it works.



https://sudeep.shinyapps.io/SecondApp





