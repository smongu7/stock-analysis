# Module 2 Analysis
## Overview of Project
The purpose of this project was to practice refactoring code. In order to do this, we were given a scenario in which an individual (Steve) was helping his parents look at several different stocks to determine the best ones in which to invest. We looked at the returns of the same stocks over a two year period (2017-2018). To see the returns, we created code that calculated the return for each stock. Using the creation of a button and appropriate code, we also allowed for Steve-- or any end-user, for that matter-- to input which year he wanted to run his analysis on.
## Results
I created the analysis by following the instructions step-by-step, as can be seen in the code:

![vba_code](https://user-images.githubusercontent.com/94420548/149050156-a2bc12f1-3655-42e7-b0a3-2a7cd09132f1.png)
![vba_code_2](https://user-images.githubusercontent.com/94420548/149050232-2772a90d-acc2-4316-8775-132b232bf096.png)


The following image is the analysis of stocks in the year 2017:

![Stock_analysis_2017](https://user-images.githubusercontent.com/94420548/148861041-744177bd-1a5c-424b-b41c-e832d8a11da0.png)

The following image is the analysis of stocks in the year 2018:

![Stock_analysis_2018](https://user-images.githubusercontent.com/94420548/148861078-96616807-6bc3-40cd-a046-080a5b267fbb.png)

Based on the data we have, I would advise against investing in almost all of these stocks. RUN and ENPH are the only ones that have a positive return of investment both years. There are a couple-- SEDG and VSLR-- that did very well in 2017 and only dropped a little bit in 2018 that indicate they may be slightly less high risk than a stock like DQ, which was up nearly 200% in 2017 but dropped to -62% in 2018. Stocks with drastic rises and falls like this are typically high risk. I would like to see returns on investments of the stocks over a 5-10 year period to get a better picture of the general trend of each of the stocks. Let's say that some of the stocks that were negative in 2018 were only negative in 2018 during a 5-10 year period. In this scenario,  they are probably relatively lower risk than the stocks that alternate every year between positive and negative returns. 
## Summary
Perhaps the biggest advantage of refactoring is that it can decrease the runtime of a macro. Addtionally, the code will be more organized and easier to follow. It allows one to clean up redundant comments and allows for the code to more easily followed by someone who didn't create the code. However, refactoring code can be time consuming. Thus, if one is short on time, refactoring can be a disadvantage. Additionally, because refactoring can be time consuming, it can take longer than writing or rewriting the code from scratch. In the case of our stock analysis for Steve's parents, refactoring decreased the runtime of the macro. This was probably the biggest advantage. Additionally, it helped me to outline what I was going to accomplish with the code. It helped me keep track of what code I had already completed when I came back to work on it after walking away and it helped me to remember what I needed to do next. The refactoring also helped me to follow what the code was doing when I was rereading it from the beginning.
