# Stock Analysis Project
## Description
The purpose of this project is to build an user friendly tool for analysis of stocks for potential investment. It began with a limited scope to analyze return series of a single stock. However, the investor wanted to develop a comparison of the available stocks satisfying specific niche qualit,y in this case "green stocks" i.e. environmentally responsible investments. The original analysis tool was designed to handle a small universe of such stocks and worked well for limited data. However, it was not optimized to analyze large datasets. So the code is enhanced (refactored) to otimize performance and analyze large dataset in reasonable time.
Refactoring enhances coding several ways including
* Removes unnecessary portions of the code
* Simplifies code structure to ease cooperation between different portions of an application
* Properly implements object-oriented and functional programming principle
* Shrinks the size and weight of elements in the code

## Analysis
The return series data consists of daily data including openin price, closing price, trade volume, and intra dau high and low prices. The data is summarized in annual returns for the potential longer horizon investment. In any case, it is difficult to make an informed investment decision from daily data as daily volatilities are typically higher than longer term sustained volatility. Data for 2017 and 2018 are summarized as annual returns for selected green stocks for consideration. Following tables show the returns for 20217 and 2018:

![Stock Returns 2017](https://github.com/mbandyo/stock-analysis/blob/main/Resources/Stock%20Returns%202017.png)    ![Stock Returns 2018](https://github.com/mbandyo/stock-analysis/blob/main/Resources/Stock%20Returns%202018.png)

As is clear from the tables most stocks did well in 2017, but dismally in 2018. Esepecially the stock of interest DQ, posted highest returns in 2017, but had the largest negative returns in 2018 in the list of selected stocks. The analysis provides knowledge to potential investors to make informed decision.
The original unfactored code as well as the factored code provide the same result. 
## Results
The runtimes for the original code and factored code for 2017 and 2018 are shown below
### 2017:
![Unfactored Code Run Time 2017](https://github.com/mbandyo/stock-analysis/blob/main/Resources/Original%20Run%20Time%202017.png)    ![Factored Code Run Time 2018](https://github.com/mbandyo/stock-analysis/blob/main/Resources/VBA_Challenge_2017.png)
### 2018:
![Unfactored Code Run Time 2018](https://github.com/mbandyo/stock-analysis/blob/main/Resources/Original%20Run%20Time%202018.png)   ![Factored Code Run Time 2018](https://github.com/mbandyo/stock-analysis/blob/main/Resources/VBA_Challenge_2018.png)

It is clear from the above that the run times were less for the refactored code for both years. It is not a perceptible difference in this case as the list is very short. However, if this analysis is run for a longer list of stocks, the performance improvement would be apparant. Refactoring enhanced performance and optimized code execution.
