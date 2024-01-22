## Module_5_challenge

This assignment asks you to imagine launching a fintech consulting firm. The firm focuses on helping local communities and has just landed its first large contract with a local credit union. The chief technology officer of the credit union wants you to develop an app with two major functions: 1) assess monthly budgets and 2) forecast a retirement plan comprised of stocks, bonds, and cryptocurrencies. 

PART 1: PERSONAL FINANCE PLANNER
Part one focuses on creating a financial planner that will inform us if our savings portoflio is enough to serve as an emergency fund. We know the portfolio holds 1.2 bitcoin and 5.3 etheruem. We fetch real-time price data and find that the portfolio owns $49,569.60 in Bitcoin and $12,909.69 in Etheruem. The portfolio also owns 50 shares of SPY (S&P 500 index) and 200 shares of AGG (Aggregate Bond Index). We go on to fetch real-time data on these and find they are worth $24,121.50 and $19,604.00, respectively. The monthly income is $12,000 and the emergency fund is required to be three times larger than the income. Our code let's us know, "Your savings of $106204.787 are greater than your emergency fund goal of $36000. Congrats on having enough money!"


PART 2: RETIREMENT PLANNING
Part two requires us to forecast five hundred simulations of SPY and AGG data to find the range in which an initial investment could be worth in thirty years. The first step is to gather five years worth of SPY and AGG data. We run the five hundred simulations and find the lower and upper confidence intervals. These lower and upper limits inform us that "there is a 95% chance that an initial investment of $20000 in the portfolio over the next 30 years will end within in the range of $46,426.25 and $799,466.92." Quite the variance!


CODE SOURCE

The code was derived from class activities and questions answered by peers; the questions regarded how to hide my API keys and how to fun the simulation correctly. I also worked with Kimberly Rodriguez in part two. We found that our MCForecastTools file needed updating, hence the issues simulating.


TECHNOLOGIES

There are no major technologies used in this assignment. It was done on a Jupyter Notebook with Python coding language and used the pandas, dotenv, alpaca trade api, and  MCForecastTools libraries.