# whale-and-rival-analysis

"""
# Notes for Instructor Grader (IG), Please

In terms of citations, in general, 99.99% of work presented inspired by office hours with Instructor GS, 
Instructor AN, Instructor KS, tutor (Ms. LT), and refresher notebooks.
help for cumprod method from https://stackoverflow.com/questions/40811246/pandas-cumulative-return-function
help for Boolean risk from  https://www.e-education.psu.edu/geog489/book/export/html/2047 


The student author apologizes profusely for any confusion (the student author is me, 
Franklin Bueno). In order to to jump directly to answers from the Whale Analysis Cells (WAC) by searching
(i.e., simultaneously pressing 'CTRL' and 'F' keys) and searching for WAC (or WAT for Whale Analysis Text or RDM
for ReadMe questions). The student author felt compelled to do this because there were so many questions
interspersed among the README, the starter cells, and the starter markdown.

# Whale Analysis Cell (WAC) Questions
These are questions and/or commands given in specific cells in the starter file. As the student author answers
each one of these questions, the student author notes which WAC question is being answered. The student author 
apologizes for not answering every question in the cells in order...

## Cells in which answers to WAT and RDM questions are given after the answer in this unique cell/file...


# Whale Analysis Text (WAT) Questions
In terms of Whale Analysis Text (WAT) questions, there were seven (7) questions according to the count of the 
student author.

1 Does any portfolio outperform the S&P 500? (of the given whales and algorithms) WAT 1
It is hard to tell anything from the daily returns graph alone.
From the cumulative returns table and graph, the student author is identifying Berkshire and Algo 1 as
outperforming the S&P 500. cell 45

2 Plot the rolling standard deviation of the various portfolios along with the 
rolling standard deviation of the S&P 500 (consider a 21 day window). 
Does the risk increase for each of the portfolios at the same time risk increases in the S&P? WAT 2
Based on the two graphs above only, in general, except for the Tiger anomalies,
in terms of general direction, the portfolios go along with the S&P. Greater risk corresponds with greater standard deviation.
Therefore, in general, the porfolios generally go along with the S&P in terms of risk. cell 60

3 Which returns most closely mimic the S&P? WAT 3
Based on the S&P row, Algo 2 is the closest mimic, Soros is the second closest, Berkshire is the third closest,
Paulson is the fourth closest, Tiger is the fifth closest, and Algo 1 is the farthest away. cell 63


4 Choose one portfolio and plot a rolling beta between that portfolio's returns and S&P 500 returns. 
Does the portfolio seem sensitive to movements in the S&P 500? WAT 4

The student author did beta graphs for Berkshire and for Tiger. Berkshire seemed sensitive to movements in the S&P 500.
Tiger did not seem so sensitive to movements in the S&P 500 in later months. cell 70

5 (After all, if you could invest in one of two portfolios, 
each offered the same 10% return, yet one offered lower risk, you'd take that one, right? WAT 5
Yes, the student author would take the portfolio with the lower risk. cell 73

6 do our algo strategies outperform both 'the market' and the whales? WAT 6
WAT 6

It seems like Algo 1 outperforms both the S&P and all of the whales,
but it also looks like Algo 2 itself underperforms compared with the S&P and Berkshire. cell 73

7 Add your portfolio returns to the DataFrame with the other portfolios and rerun the analysis. How does your portfolio fair?
WAT 7 answered throughout every comparison with the FRANK HEDGE FUND

WAT 7
It was hard to tell from the graph, but the table clearly indicates that the FRANK HEDGE FUND 
brought the third highest cumulative
returns, Algo 1 brought the most, and Berkshire brought the second most... cell 98


WAT 7
Algo 1 has the smallest standard deviation, and FRANK HEDGE FUND has the third largest standard deviation cell 102

WAT 7
Annualized is multiplying everything by the same constant, so FRANK HEDGE FUND is still the 
third highest in terms of standard deviation and therefore the third riskiest... cell 108

WAT 7
FRANK HEDGE FUND seems to follow the S&P in direction, but on a lower scale... cell 111

WAT 7
In terms of beta, FRANK HEDGE FUND seems to be closer to to the S&P than Tiger, but FRANK HEDGE FUND is not 
as close to the S&P as Berkshire
cell 122
WAT 7
FRANK HEDGE FUND has the second best Sharpe ratio, but is still far behind Algo 1 in terms of Sharpe ratio...
cell 126


# README (RDM) QUESTION
README QUESTION - One (1) question did not seem to overlap with the other questions


Create a box plot for each of the returns. Which box has the largest spread? Which has the smallest spread?


1. Create a box plot for each of the returns. Which box has the largest spread? Which has the smallest spread?
From the box plots, it looks like Tiger has the largest spread and Paulson and Algo 2 having the smallest spreads, 
with Paulson most likely
having the smallest spread of all (as may be confirmed in the standard deviation) cell 50



"""