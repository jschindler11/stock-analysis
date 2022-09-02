# Stock Analysis

## Overview of Project

### Purpose
The purpose of this analysis is to use stock data from two years (2017 and 2018) to determine total daily volume and the annual percentage return of 12 different stocks. We refractered our VBA code to increase our execution time.
## Results
In 2017, 11 of our 12 stocks yielded a positive annual return. Only TERP yielded a negative annual return. In 2018, 10 of our 12 stocks yielded a negative annual return. Only ENPH and RUN yielded a positive annual return.
Before we refractered our VBA code, the code ran at 0.5859375 seconds to analyze our 2017 stocks and 0.578125 seconds to analyze our 2018 stocks. After we refractered our VBA code, these times decreased to 0.08984375 for 2017 and 0.09765625 for 2018 - both about 6 times faster.
## Summary
1. Advantage of refractering code: Removed redundancies and duplications allow the code to be more effective and, in turn, run faster
   Disadvantage of refractering code: Inaccurate refactoring could introduce new bugs and errors into the code
2. Refractering our original VBA script allowed our code to run six times as fast. Our data set was relatively small, but if it was a much larger data set,    six times faster would be significant. 
   During the process of refractoring, new bugs were created and had to be dealt with in order for our refractered code to run.
