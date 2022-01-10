# stock-analysis
## Overview
Investing in the stock market can be a risk.  It is important to evaluate trends of different companies you are interested in investing in so that you can make the best choice and see the highest return on investment.  In this analysis we will see year over year returns to determine which company has been most successful.
###### Analysis
In this analysis we ran stock data for multiple different companies in the years 2017 and 2018.  
![](/Resources/Capture1.png)
![](/Resources/Capture2.png)
Based on the findings above, you can see that overall, 2017 was a much more successful year than 2018.  2017 had positive returns for all but one company, and the company that had a negative return was less than 10%.  2018 was the opposite.  Only two companies had a positive return during this year.  Both companies with a positive return were over 80%.  The two companies that were positive for both years were ENPH and RUN.  In 2017 ENPH’s return was 129.5% and 81.9% in 2018.  In 2017 RUN’s return was 5.5% and 84.0% in 2018.  Based on this I would recommend ENPH as the company to invest in, as the data shows they have the highest return year to year.  
![](/2017.png)
![](/2018.png)
By refactoring this code and using a ticker index which is set equal to 0, tickerindex = 0, the system is able to loop through all data to find the requested outputs and then do the same for the next ticker, tickerindex = tickerindex + 1.  This also allows the system to run more efficiently.
###### Summary
 -An advantage to refactoring code is that we can adjust when needed.  We are easily able to add new parts to our existing code that can make it more useful.  
 -It can be a disadvantage if you are unable to achieve your goal and you spend extensive time trying to add in the changes, when it may have been more efficient to start from scratch.  
 In this case, the advantage to refactoring was cutting down on the execution time.  A disadvantage was functions became long with the addition of the ticker index.
