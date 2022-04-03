# Stock Analysis Challenge

## Overview of Project
The clients are currently only investing in Daqo New Energy (DQ) since they're passionate about green energy. They believe that as fossil fuels get used up the world will rely more and more on alternative energy productions. The objective of the project is to analyse the yearly volume and return to know the performance of not only DQ stock but other green energy stocks so the client can compare to other stocks and diversify their investment. Additionally, the analysis must run efficiently as the datasets get larger so as the VBA programmer the code must be refactored to minimze processing time. 
## Results

1. The stock performance between 2017 and 2018 is presented by a combo graph of bar graph for the ticker and year and a line graph for the return. 
    a) DQ stock that the client is currently investing had a positive return in 2017 but dropped significantly in 2018 with an increase of daily volume. 
    b) The stocks that performed better with a solid return and an increase in daily volume are ENPH and RUN.
    c) Recommendation for client:
        i) Consider diversifying investment to ENPH and RUN.
        ii) Analyze trends by adding 2019 to 2020 stock performance to validate if the two year trend is maintained. 
    ![Alt text](https://github.com/Jimena-QM/stock_analysis/blob/main/Stock%20Performance%202017%202018.png "Stock Performance")
2. Analysis of original vs refactored 
    a) Refactored code ran more efficiently with a 92.7% improvement for 2017 and 93.1% for 2018. 
    ![Alt text](https://github.com/Jimena-QM/stock_analysis/blob/main/Performance_Imp_Original_Refactored.PNG "Performance Orig vs Refactored"
    b) Refactored code had two new variables set for ticker_index and ticker_volume. Also, start price and ending price were modified from double to single variables. Setting the variables and modifying the length of the variables reduces processing time. 
    Original Variables
    ![Alt text](https://github.com/Jimena-QM/stock_analysis/blob/main/Original_Variables.PNG "Original Variables")
    Refactored Variables
    ![Alt text](https://github.com/Jimena-QM/stock_analysis/blob/main/Refactored_Variables.PNG "Refactored Variables")
    c) Eliminated the if statement that added the volume by creating a ticker_index
    Original
    ![Alt text](https://github.com/Jimena-QM/stock_analysis/blob/main/Original_TotalVol.PNG "Original If for Total Vol")
    Refactored
    ![Alt text](https://github.com/Jimena-QM/stock_analysis/blob/main/Refactored_TotalVol.PNG "Refactored removed If for Total Vol")
    d) In refactored code a for loop as added to output the final calculations through arrays, making the process more efficient. 
    ![Alt text](https://github.com/Jimena-QM/stock_analysis/blob/main/Refactored_Arrays_ForLoop.PNG "Refacotred Array For Loop")
## Summary
1. What are the advantages or disadvantages of refactoring code?
    a) Refactoring code is advantageous since it promotes cleaner code that is more organized and easier to interpret. Refactoring can also improve efficency in run time. 
    b) Disadvantages of refactoring code are that we can inadvertently introduce bugs and it may take more time than we have to allocate.   

2. How do these pros and cons apply to refactoring the original VBA script?
Refactoring made the code run more efficient, easier to read and cleaner. It also gives the coder the tiem to review the code and find ways to make the code more efficient. The disadvantage is that it took additionaly time to refactor and if the program had a deadline I might have left the code as is in order to meet the deadline and spend a bit more time analyzing the results to give the client more insights instead of time efficiency.  

