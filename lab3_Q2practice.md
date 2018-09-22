Lab3 \_Q2\_Practice to create a new Markdown Document
================
Sabrina Kakei Tse
September 21, 2018

This document lists out things I found interesting from 511 this week.
----------------------------------------------------------------------

``` r
# converting/coercing objects into different form in R

as.character(8.89)
```

    ## [1] "8.89"

``` r
as.numeric("8.89")
```

    ## [1] 8.89

As a beginner to coding, I am more intrigued by R than by Python because of the ease of applying it. For example, if I have to square all the elements in a list, I have to set up a function to wrap a for-loop function in Python in order to do that:

### Step 1 in Python

``` python
def square(list):
  list=[]
  for x in list:
    list.apphend(x ** 2)
  
  return (list)
```

### Step 2 in Python

``` python
a = [1,2,3,4,5]
square(a)
```

But all of these can be done in one step in R (MIND-BLOWN - that explained why Vincenzo walked away from the stage after he did the demo and said " Just that", as if he just "mic-dropped"" in our Thursday class):

``` r
a <- c(1,2,3,4,5)
a^2
```

    ## [1]  1  4  9 16 25

Note that the `echo = FALSE` parameter was added to the code chunk to prevent printing of the R code that generated the plot.
