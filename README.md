# Stock-Analysis

Overview of Project: 

Background

Steven is working as a financial analyst for his parents. He has collected data on 12 stocks over the course of 2017 and 2018. This data includes the daily volume, high, low, and closing price of each stock. Steven will use this data to determine which stocks would be the best for his parents to invest in. For example, stocks with a higher daily volume have a greater probability of keeping to their intrinsic value than stocks with a lower daily volume. In turn, those stocks would be a safer investment. Of course, stocks showing a strong record of consistent growth would be more likely to grow in the future. 
	
My Task

Being the “VBA expert” that I am, Steven has asked me to write some VBA script to display the key characteristics of each stock in a readable chart. The code I originally came up with worked but was inefficient. It may have a hard time converting and displaying data for a larger group of stocks. Thus, I had to refactor my code. Refactoring is the process of editing code to display the code more eloquently and have the code run more efficiently. 
	
Analysis

After refactoring my code, I added a timer function to both the original code and the refactored version. This timer function displays a pop-up box after the code has ran expressing how long it took for the program to run. This allows me to see how much faster the refactored code runs in comparison to the original code 

Results:

2017

After running my code for 2017 and 2018, we can see notable differences in how the groups stocks performed in each given year. In 2017, almost all the stocks saw positive returns. Eleven out of the twelve in fact. Notably, nine of the twelve stocks preformed better than the S&P 500. Four of the stocks even had gains of over 100%. 

2017 Data Chart 

https://github.com/jkhera83/Stock-Analysis/blob/main/Resources/VBA_Challenge_2017.png

	


	
2018

However, in 2018, almost all the stocks saw negative returns with the only exceptions being ENPH and RUN. In fact, ENPH and RUN both saw gains of over 80%. However, ENPH realized less gains in 2018 then in 2017. Run, on the other hand, realized almost 80% more gains in 2018 when compared to its year-to-end growth percentage in 2017. This fact may be of importance to Steven and his parents. 

2018 Data Chart










Timer

The pop-up timer displayed significant differences between the run time for the original code and the refactored code. In fact, the refactored code ran in less than a second while the original code took a walloping 36 seconds to run. 

Refactored Code Timer    

https://github.com/jkhera83/Stock-Analysis/blob/main/Resources/VBA_Challenge_2017.png

Original Code Timer 

https://github.com/jkhera83/Stock-Analysis/blob/main/Screenshot%20(7).png












Summary: 
	
Refactoring code has its advantages and disadvantages. The major advantage of refactoring code is that often you can make your code run more efficient by taking fewer steps and thus using less memory. In my case, refactoring allowed my code to run 36 times faster! While refactoring, you can also improve the “logic” of your code to make it more readable in the future. However, the major disadvantage to refactoring code is that it takes time. It may prove to be the case that the time saved with the more efficient, refactored code is offset by the time spent refactoring the code itself. 
	
When refactoring the original VBA script, I found myself frustrated. It often felt that the time spent refactoring the code was not worth the time that would be saved by making it run more efficiently (I mean… if it runs, It Runs!). However, a computer should never take 36 seconds just to crunch some numbers. With how much it costs to own a computer, I could never put up with that. After refactoring the code and seeing how much quicker it ran (in less than a second), I could clearly see that the advantages outweighed the disadvantages.  
