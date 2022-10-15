## Python

![Python 3.7](https://img.shields.io/badge/Python-3.7-blue.svg)

===========

This repository includes all my personal notes taken during the different courses and books.
Books contained in this repository (buy books - Invest in knowledge and support creators.):

 - Data Science Bookcamp: You can buy the book [[here](https://www.manning.com/books/data-science-bookcamp)]
 
 
## Statistical concepts - Interview Questions

### in your own words, what do the p-values indicate ? 
It tells us how statistically significant a hypothesis is agains observer data. The lower the **p-values** the better. the limit to be considered significant is **p < 0.05**.  

   - p > 0.1 --> No evidence agains the null hypothesis.  
   - 0.01 < p < 0.05 --> Moderate evidence agains the null hypothesis.  
   p < 0.001 Very strong evidence agains the null hypothesis.  

**Null Hypothesis** = Two possibilities are the same.


### What is Conditional Probabilities ?

Simply the probability that something will happend, scaled by whatever knowledge we alread have about the event.



## Time Series Analysis and Forecasting

![Python 3.7](https://img.shields.io/badge/Python-3.7-blue.svg)

===========

This repository includes all my personal notes taken during the different courses and books.

 
## Time Series Inteview Questions.

#### What is meant by the term White noise ?

A Time series with White noise is a sequence of random numbers that cannot be predicted.

#### What is referred to as "Random Walk" ?

Random Walk is a tool taht can help use to understand the predicatility of our time series problem.

#### What is the difference between Random Walk and White noise ?

Ranom Walk is differnt from a list of random numbers because the next value in the sequence is a modification of the previous value in the sequence.

#### What is autocorrelation ?

Autocorrelation is the correlation between each observation and the observation at previous time steps.

#### What is sationary in TS ?

#### What indicate the Dickey-Fuller  test ?

The null hypotesis from Fuller test is that the Time Sereis is non-stationary, therefore a p > 0.05 will confirm the null hypotesis.

#### In which components can you decompose a Time Series ?

I will make the distintion between "Systematic" wich have consistence and recurence and can be described and modeled and "non-systematic" components which can not be modeled.

- Systematic: Trend, level and Sesionality
- Non-Systematic: nosie

#### what is the advantage of identifying the trend in a TS ?

Can be positive to identify which model we are interes in.
In some cases it may be that removing the trend simplifies the model and improves performance.

### What is Seasonality in TS and why is importan ?

Seasonality is a cycle that repeats over the time such as month or year. Identify and understand the seasonal component can help in two ways.
 - Clear Signal: Identify and removing seasonal component could incurr in a clear relationship between input and output variables.
 - More Information: Additional information about Seasonalit can provide new information to the model performance.
 
 
 





