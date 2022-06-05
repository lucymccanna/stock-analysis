# stock-analysis
Module 2 - VBA 

## Overview of Project
VBA was used to automate the analysis of twelve different green energy stocks. The Total Daily Volumes and Annual Returns were calculated using conditionals and for loops, and color formatting was applied to enhance the visual appearance of the data.

## Results
In 2017, the annual return for 11 out of the 12 selected stocks was positive, with DQ having the highest performing stock at 199% return. The following year, only 2 of the 12 stocks had positive returns, ENPH and RUN (see Images 1 and 2). 

**Image 1:** 2017 All Stocks Analysis
![This is an image](https://github.com/lucymccanna/stock-analysis/blob/e1bdd7156cc18728c8aab478dfe6a4571b7307dc/Resources/AllStocks_2017.png)

**Image 2:** 2018 All Stocks Analysis 
![This is an image](https://github.com/lucymccanna/stock-analysis/blob/e1bdd7156cc18728c8aab478dfe6a4571b7307dc/Resources/AllStocks_2018.png)

The original code ran the 2017 analysis in 0.9375 seconds. After refactoring the code, the analysis for 2017 ran in 0.1445313 seconds. Similarly, the original analysis for 2018 ran in 0.9609375 seconds and the refactored code ran in 0.1601563 seconds.  
    
**Image 3:** 2017 Original Analysis Execution Time 
![This is an image](https://github.com/lucymccanna/stock-analysis/blob/5338c14cdf3ebb2a18028deefeaaf1ebcd9127f6/Resources/2017originalanalysis_runtime.png)

**Image 4:** 2018 Original Analysis Execution Time
![This is an image](https://github.com/lucymccanna/stock-analysis/blob/5338c14cdf3ebb2a18028deefeaaf1ebcd9127f6/Resources/2018originalanalysis_runtime.png)


 **Image 5:** 2017 Refacctored Analysis Execution Time 
![This is an image](https://github.com/lucymccanna/stock-analysis/blob/e1bdd7156cc18728c8aab478dfe6a4571b7307dc/Resources/VBA_Challenge_2017.png)


**Image 6:** 2018 Refactored Analysis Execution Time:  
![This is an image](https://github.com/lucymccanna/stock-analysis/blob/e1bdd7156cc18728c8aab478dfe6a4571b7307dc/Resources/VBA_Challenge_2018.png)



## Summary

Refactoring code is a good practice to clean up existing code. It can make code neater and more concise, however it may also lead to new errors or issues within the code. 
In this analysis, the refactored code ran significantly faster. 
