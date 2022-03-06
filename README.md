# Stock Analysis

## <u> An Overview of the project </u>
Analysis on stock data to help Steve and his parents determine whether investing in the stock 'DQ' was the right choice or to determine any better alternatives. 
To achieve this goal, we look into the 2017 & 2018 stock databases. Using VBA, we will pull and clean all the necessary data that will be used for our analysis.

## <u> Results </u>
Running our date through the code written in VBA, we can come to a few conclussions:
* Running the 2017 database through our code, intitially you may think investing in DQ may be a good option as it yeilded the highest return percentage. However, Looking at the volume at which it was traded, it came in last with the least volume traded. This helps indicate whether a stock's prices will continue to surge. This is later confirmed in the analysis for 2018 database as it yielded the worst return percentage and least volume traded. In conclusion, DQ is not a great stock in invest in long time.
* The optimal stock to invest in that produces the greatest chances of success is ENPH. This is best shown in our analysis as both years, it yields relatively high percentage returns and maintains a very high trade volume!

Looking at the original code vs the refractor coder we can see a few differences:
* The main differences between the code is the efficiency at which it runs. The refactored code runs faster the original one. As we can, in the images below, the refractored run time is relatively signficantly faster than the original code.
* The difference in time can be attributed to the efficient use of arrays. Using arrays helps reduces the need of reassigning variables constantly as we just add information to an array.

### 2017 Database Analysis
![2017_photo](images/2017_photo.png)

### 2018 Database Analysis
![2018_photo](images/2018_photo.png)

### Original code
![2017_runtime](images/2017_runtime.png)

### Refactored code
![2017_runtime_r](images/2017_runtime_r.png)

## <u> Summary </u>
In summary, refactoring our code, we have determined a better stock to invest in and created a more efficient code. 
