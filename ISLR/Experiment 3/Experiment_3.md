# Experiment 4
Rigel  
October 14, 2017  



## R Markdown

This is an R Markdown document. Markdown is a simple formatting syntax for authoring HTML, PDF, and MS Word documents. For more details on using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that includes both content as well as the output of any embedded R code chunks within the document. You can embed an R code chunk like this:


```r
set.seed(1)

y = runif(200,0,100)
x = rnorm(200,y,1)

plot(x,y)
```

![](Experiment_3_files/figure-html/cars-1.png)<!-- -->

