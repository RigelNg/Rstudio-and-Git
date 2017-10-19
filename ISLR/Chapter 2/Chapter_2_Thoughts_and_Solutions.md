# Chapter 2 Thoughts and Solutions
Rigel  
October 10, 2017  



## Introduction to Statistical Learning Chapter 2 - Thoughts and Solutions
#Questions 1
 
I think the word "generally"" is quite important here.

a) Large n and small p, we would expect a more flexible method to provide a better fit because it is fitting the data more closely without having the effect of overfitting increasing the error as much. 


b) Large p and small n, we would expect a LESS flexible method to provide a better fit because it is more robust and therefore less likely to overfit. 

- In other words, the decrease in bias would be bigger than the increase in variance when n is huge and p is small. THis relationship is reversed if the condition is reversed. 

Note: IF p>n there won't be a unique solution for least square so it wouldn't even work. 

THink of solving x+y+z = 10 and 2x+3y+4z = 25

c) if the true underlyinig relationship is non - linear, this would mean we expect a linear method to perform badly at the predicting. 

d) The variance of the error is high which suggest there is a lot of noise, a more flexible method will tend to overadjust to these noises and thus provide a model that would overfit the data. A less flexible will be more robust to overfitting and thus perform better in this instance. (SEE Experiment folder)





## Question 2

####Note: We tend to refer to problems with a quantitative response as regression problems, while those involving a qualitative response are often referred to as classi???cation problems

a) CEO's salary is quantitative and thus this is a regression problem. Since we are interested in the relationship between n and p, this can be treated as an inference problem. n = 500, p = profit, number of employees, industry (3)

b) The response, success and failure is a qualitative and thus it is a classification problem, we are interested in the outcome and thus this can be treated as a prediction problem as well. n = 20, p = priced charged, marketing budget, competition price, and ten other variables ~ p = 13.

c) the response is quantitative so this is a regression problem. THis is also a prediction problem as we try to predict the future market rates.  n = 52 , p = % change in dollar, % change in us market,% change in british market, % change in german market. p = 4

## Question 3



## Question 4

###Classification

Note:: Classification problems is when the response is qualitative other than quantitative - Prediction is when we create f(x) and uses it onto new data points. Inference is when we try to understand f(x)

4.1.1) Classifying what type of cancer a patient have given their genes data. This is a prediction problem, genes data is the features and the response is types of cancer. 

4.1.2)We can transform this into a inference problem if we try to understand which genes mutation causes which type of cancer



4.2.1) Classifying Email spam base on words in the email, the features are the words, and reponse is Yes/No on the spam. ()

4.2.2)We can transform this into an inference problem if we try to understand which words causes an email to be classified as spam.

4.3.1) Classifying different words from amplitude recorded from a device. (Speech Recognition)

4.3.2) We can transform this into an inference problem if we try to understand how different movement in the amplitude turns into different words.

###Regression

4.4.1)

###Clustering


 








Note that the `echo = FALSE` parameter was added to the code chunk to prevent printing of the R code that generated the plot.



