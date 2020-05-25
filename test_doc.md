test\_doc
================
Jae Won Suh
22/05/2020

## R Markdown

This is an R Markdown document. Markdown is a simple formatting syntax
for authoring HTML, PDF, and MS Word documents. For more details on
using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that
includes both content as well as the output of any embedded R code
chunks within the document. You can embed an R code chunk like this:

``` r
summary(cars)
```

    ##      speed           dist       
    ##  Min.   : 4.0   Min.   :  2.00  
    ##  1st Qu.:12.0   1st Qu.: 26.00  
    ##  Median :15.0   Median : 36.00  
    ##  Mean   :15.4   Mean   : 42.98  
    ##  3rd Qu.:19.0   3rd Qu.: 56.00  
    ##  Max.   :25.0   Max.   :120.00

## Including Plots

You can also embed plots, for example:

![](test_doc_files/figure-gfm/pressure-1.png)<!-- -->

Note that the `echo = FALSE` parameter was added to the code chunk to
prevent printing of the R code that generated the plot.

![](test_doc_files/figure-gfm/speed_dist-1.png)<!-- -->

New code\!

``` r
# This is generating 10 numbers from a standard normal distribution
rnorm(10)
```

    ##  [1]  0.8057807 -1.5022644 -1.3313605 -0.6154944  0.6018403 -1.3408382
    ##  [7]  1.0989302 -0.2878928  0.5562174  0.5753227
