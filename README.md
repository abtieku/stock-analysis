# VBA of Wall Street
## Overview
### Purpose and Background
The purpose of this analysis is to assist Dago in making his macro run faster. He is currently adivising his parents on what stocks to purchase. As a test, he is only running it through 3013 stocks, and before he runs it through all stocks, he wants to make it run faster. 

The first spreadsheet I did was to loop through and find ones that have a higher ending cost than starting close, and a high percentage of gain. The second spreadsheet was to make the code run faster.

With both spreadsheets, I programmed in a timer to tell how much time it takes to do each. My sample did not have all stocks in it, hopefully Dago can run it on the whole stock market to come up with the statistics for his parents on all stocks to buy.

My dataset only consists of 3013 stocks. In the future, we will do it on more:

## Results
### First Analysis
The first analysis looped through them all and did xyz. The 2017 stocks came out like this:  

[Outcomes Based on Goal](./resources/VBA_Challenge_2017.png)  

2018
[Outcomes Based on Goal](./resources/VBA_Challenge_2018.png)  



The timer on the original clocked in at xx

So the new one went faster.

### Second Analysis
The second one looped through them all and came out faster. Here's what it looked like:  
Include code


![](./resources/VBA_Challenge_2017.png)  


Why did the new one go faster? Because we used Index instead and that made all the difference.

## Summary
### Advantages and Disadvantages of Refactoring Code - General
Advantages can be: 
* Code can be more straight-forward, less complex, and easier to maintain.

### Advantages and Disadvantages of Refactoring Code - This Project
*Disadvantages can be:
* Time-consuming and not worth the time and money.
* There is a chance for mistakes and the losing sight of the purpose of the code. It may need to be re-tested.



