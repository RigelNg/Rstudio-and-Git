# Chapter 2 Thoughts and Solutions
Rigel  
October 10, 2017  



## Introduction to Statistical Learning Chapter 2 - Thoughts and Solutions
#Questions 1
 
I think the word "generally"" is quite important here.

a) Large n and small p, we would expect a more flexible method to provide a better fit because it is fitting the data more closely without having the effect of overfitting increasing the error as much. 


b) Large p and small n, we would expect a LESS flexible method to provide a better fit because it is more robust

- In other words, the decrease in bias would be bigger than the increase in variance when n is huge and p is small. THis relationship is reversed if the condition is reversed. 

Note: IF p>n there won't be a unique solution for least square so it wouldn't even work. 

THink of solving x+y+z = 10 and 2x+3y+4z = 25

c) if the true underlyinig relationship is non - linear, this would mean we expect a linear method to perform badly at the predicting. 





## Including Plots

You can also embed plots, for example:



Note that the `echo = FALSE` parameter was added to the code chunk to prevent printing of the R code that generated the plot.
