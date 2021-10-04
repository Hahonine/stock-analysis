# Analysis of Stocks

## Overview of Project

### Purpose

The purpose of this analysis is to determine which stocks of the selected list would be best for future investment. To achieve this goal, we wrote a VBA script that does the heavy lifting for us and tied it to a button on the spreadsheet.

## Results

### Stock Analysis Results

The result of our analysis of the stocks in the dataset is conclusive. ENPH and RUN are the only 2 stocks to do well in both 2017 and 2018. RUN and TERP are the only 2 stocks to have done better in 2018 than in 2017. Knowing both of these things allows us to conclude that RUN is the only stock worth investing in, assuming future years follow the same trend.

### Code Refactor Analysis

Our refactor from the original VBAscript didn't save a meaningful amount of runtime. However, the refactor allowed us to incorporate the conditional formatting which removed the need for a formatting button. We also refactored the code to allow for greater expansion with less debug overhead. This will greatly improve the ability of the script to handle an increase in the number of data or the number of tickers being analyzed.

##Summary

Refactoring code is always a tradeoff of programming and debug time spent versus coding goals achieved. By spending more programming and debug time, you can reduce the time spent running the code, or make the code more readable, or reduce the source code complexity, or expand the sourcecode for future expandability. 

The upside of refactoring code is in how it allows you to plan for the future in whichever way is most beneficial for the programmer. The downside of refactoring code becomes obvious when a change breaks the script or leads to serious downtime to debug the changes. Any time you alter something that already functions is a time you risk breaking that function for an unknown amount of time. Additionally, time spent refactoring code is not time spent developing new features or debugging existing code that isn'tperfectly oeprational.
