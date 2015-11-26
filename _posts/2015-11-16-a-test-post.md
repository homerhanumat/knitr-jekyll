---
layout: post
title:  "A Test Post"
date: 2015-11-17 17:39:32
published: true
tags: [testing]
output:
  html_document:
    mathjax:  default
---

This is an R Markdown document. Hello. Markdown is a simple formatting syntax for authoring HTML, PDF, and MS Word documents. For more details on using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that includes both content as well as the output of any embedded R code chunks within the document. You can embed an R code chunk like this:


{% highlight r %}
summary(cars)
{% endhighlight %}



{% highlight text %}
##      speed           dist       
##  Min.   : 4.0   Min.   :  2.00  
##  1st Qu.:12.0   1st Qu.: 26.00  
##  Median :15.0   Median : 36.00  
##  Mean   :15.4   Mean   : 42.98  
##  3rd Qu.:19.0   3rd Qu.: 56.00  
##  Max.   :25.0   Max.   :120.00
{% endhighlight %}

You can also embed plots, for example:

![plot of chunk unnamed-chunk-2](/knitr-jekyll/figure/source/2015-11-16-a-test-post/unnamed-chunk-2-1.png) 

Note that the `echo = FALSE` parameter was added to the code chunk to prevent printing of the R code that generated the plot.

How about some math?

$$
\vec{u} \cdot \vec{v}
$$

is a dot product.  How about inline?  $$ \vec{u} \cdot \vec{v} $$.  That works.  Not as the kramdown documentation says.