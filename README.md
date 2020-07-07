# HackerRank Scraper
This code scrapes the leaderboard data of a given HackerRank contest, given contest URL, using selenium webdriver 
and saves the leaderboard data to a csv file called "hr_leaderboard.csv". It can both scrape ACM type leaderboards as 
well as list view leaderboards found commonly in HackerRank. The column names are same as HackerRank headers, 
and questions are named Q[question number] for ACM type leaderboards. There is a maxPage limit set to 14; however, 
this limit can be lifted easily by setting maxPage to a arbitrarily large number. In some cases, such as low 
bandwidth and slow internet speed, script may fail to retrieve data. Rerunning the code will solve the problems in 
most of the cases.
