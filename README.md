# Stock Analysis Code Refactor and Peformance Measures
---
## Project Overview
### Purporse of Analysis
Our client Steve, wants to expand the stock dataset in order to include the entire stock market over the last few years. In order to makes sure that our code is effecient to handle this amount of data we decided to refactor our script in order to collect the same information more efficiently by:
- taking fewer steps 
- using less memory
- improving the logic of the code to make it easier for future users to read
---
## Results 
### Stock Performance (2017-2018)
Overall stocks in 2017 did better than stocks in 2018.
- 11 Stocks had a positive return in 2017 with 4 (DQ, ENPH, FSLR, SEDG) having a return over 100%
- 12 Stocks had a negative return in 2018 with DQ havng the lowest return of 62%
--- 
### Original Script vs Refactored Script execution times  
The Refactored Script's execution time far exceeded that of the original script for both years (2017 & 2018)
- The Original Script had an execution time of roughly 4 seconds and the Refracturned Stript had an execution of about 0.7 seconds 
![VBA_Challenge_2017.png](https://github.com/Cmarescot/Stock-Analysis-/blob/644c6580ccc500cb96486b9566489daf6c92358e/Resources/VBA_Challenge_2017.png)
---
## Summary 
### Advantages of Refactoring code
Advantages of refactoring code include:
- shorter execution times 
- more effecient code 
- improved readability 
- utlizing less memory
### Disadvantages of Refactoring code 
- can sometimes mess up code and prevent it from running properly
- brainstorming and debugging that be a little tricky 
### Impact on Original Script 
In regards to the advantages and disadvantaged of the two different scripts. One disadvantage of the original script is that it provided no flexibility for the user (Steve) to get insights on broarder ranges of stocks. The script was tailored specifically for the 12 stocks that we had but not more than that. With the new script , more stocks can be added by making small changes and in a fraction of the time. Some of the disadvantages that I came across while refactoring the scipt were errors in the code and brainstorming how to make the code run more effeciently. 
