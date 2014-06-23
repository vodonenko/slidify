---
title       : Application performing geometrical integration
subtitle    : Integration geometrically
author      : Roman Vodonenko
job         : Coursera project
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [mathjax]            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Slide 2
# This application allows:
1.  To build a scatter plot of a defined function
2.  To find definite integrals of the function geomtercially

--- .class #id 

## Slide 3

On the first step define the function using computer symbols...
i.e. how you would define it in a programming laguage:

- x^2 for $x^2$
- sqrt(x) for $\sqrt{x}$ etc.


The slider helps to define the number of dots on the scatter plot and the number of chunks to calculate the integral

You should also define boundaries for integration 

--- .class #id

## Slide 4

<img src="assets/fig/unnamed-chunk-1.png" title="plot of chunk unnamed-chunk-1" alt="plot of chunk unnamed-chunk-1" style="display: block; margin: auto;" />
The area under the above graph would be equal to the integral of f(x)  between 0 and 10

--- .class #id

## Slide 5
<img src="assets/fig/unnamed-chunk-2.png" title="plot of chunk unnamed-chunk-2" alt="plot of chunk unnamed-chunk-2" style="display: block; margin: auto;" />
The  difficult task of calculating the integral could be replaced by calculating the area of rectangles. 
If we make more rectangles (add more chunks) our calculations would become more  accurate
