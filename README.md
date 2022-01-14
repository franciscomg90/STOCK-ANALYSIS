# Stock-analysis
**Green Energy Stock Analyisis for Steve and his family.**

**Overview***

In order to help Steve with his research we have used a database with 12 different green stocks which through coding it's being processed, ordered and calculated to achieve the performance of each stock during 2017-18 and assist Steven and his parents to make better investment decisions. The object of this challenge is to use all the VBA abilities learned in the module 2 to get an efficient code that processes the stock information with the less time and less waste of memory possible. Finally, it should be user friendly to be used by common people as Steve parents that focus on the results of the analysis and not that much about the code, for this we created a pair of buttons to easily execute and clear the calculations.

![Buttons](https://github.com/franciscomg90/Stock-analysis/blob/main/BUTTONS.PNG)

**Results of the stock performance 2017-18**

In first instance I processed the information of a single stock (DQ) in order to establish a good coding framework to work with, this allowed me to see if the final calculations were showing what I expecting of them, then building indexes and refactoring the code I applied the same calculations for the hole stocks sample in a more efficient and faster way than using the the initial code for each stock.

![DQ Analysis](https://github.com/franciscomg90/Stock-analysis/blob/main/DQAnalysis.PNG)

Given the results of the analysis as you can see below, it shows a sector with high volatility in the individual stocks which could make great gainings but also big losses. I can imagine that it's expected this kind of stocks be the future but as it is a new sector and need to gain credibility, the liquidity at that moment should be quite low and this causes big movements, maybe if Steve makes this analysis between several indexes instead of individual stocks he could have a better overview of the market and sectors relative value.

![Stocks_17_18](https://github.com/franciscomg90/Stock-analysis/blob/main/STOCKS%20PERFORMANCE%2017-18.png)

About coding. Refactoring by definition "is a disciplined technique for restructuring an existing body of code, altering its internal structure without changing its external behavior", I made this with the inicial code for the allstock analysis to make a more efficient code using new indexes and calculation in arrays to improve time and memory. The results are quite good as it shows the timer.

BEFORE REFACTORING

![TIMER1](https://github.com/franciscomg90/Stock-analysis/blob/main/2017%20sin%20refactorar.png)  ![TIMER2](https://github.com/franciscomg90/Stock-analysis/blob/main/2018%20sin%20refactorar.png)

AFTER REFACTORING

![TIMER1.1](https://github.com/franciscomg90/Stock-analysis/blob/main/2017%20time.png) ![TIMER2.2](https://github.com/franciscomg90/Stock-analysis/blob/main/2018%20time.png)

![REFACTORED1](https://github.com/franciscomg90/Stock-analysis/blob/main/REFACTORED%201.1.PNG)
![REFACTORED2](https://github.com/franciscomg90/Stock-analysis/blob/main/REFACTORED%202.2.PNG)


 
**Statements**
Given the previous analysis I would recommend Steve and his parents to take in count that deversifying a fortfolio is a better way to achieve positive results in investments. Even if the returns in the green stock sector seem to be great, it's a sector with extremely high volatility and I would say also it has low liquidity and that's why the movements in prices are quite big. I would recomend to make an analysis of relative value to compare this sector to others to know the fair price and maybe invest in an ETF that replicate the index insted of individual stocks and then preponderate to beat the benchmark index as several funds do.

Adventages of refactoring
Refactoring has many advantages as I mentioned before, one is time as it is evident on the results I presented, two is less waste of memory while you're computer is executing other programs, but it has also other benefits such as having a compacted, clean and readable code for you and other users. This makes it easier when you need to review, change and  fix some variables or characteristics of the analysis. 

Original code vs refactored code
As you see in the results the new refactored code seems to be much more cleaner than the original and if you see a bit deeper you can understand that the original code used to calculate each conditional for each stock insted of using the previous and retake it from a step forward and make the performance calculation for each stock. Some times less is more, faster, cleaner and more efficient.

**Bibliographic citation**
https://dictionary.cambridge.org/dictionary/english/refactoring
