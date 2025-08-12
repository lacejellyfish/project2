# Project 2
### Objective: Setup a web scraping pipeline to scrape data from at least five pages from https://www.basketball-reference.com/. 
* Place the data in a pandas DataFrame,
* Clean the data, if necessary
* Perform data analysis that answers a minimum of four questions about the data.
* Answers should be given programmatically as output and at least two questions should have answers demonstrated via a plot, utilizing Seaborn.
* Plot analysis should include data labels, and a title that summarizes your conclusion, and styling should be applied.
* Restriction: Crawl/request delay of 3 seconds must be followed as per robots.txt on basketball-reference.com.

## Files:
* Part 1: Webpages used, data questions asked, data cleaning plan, and robots.txt restrictions (.DOCX file)
* Part 2: Webscraping, data cleaning, data analysis, and plotting (.ipynb - Jupyter Notebook file)

### We will scrape data to answer the following questions:
1. How has LeBron James’ scoring efficiency (TS%, PER) changed over the last 10 years?
2. Which teams in the eastern conference had the best win-lose percentage and how does it correlate with opponent points per game?
3. In the 2024-25 season, how does the Lakers' performance compare to their opponents? Judge stats like field goal percentage, total rebounds, and total points.
4. Which coaches of the 2024-2025 season had the highest win ratio?
5. What impact do the Round 1 2024 draft members with the top 10 points-per-game have on their team wins? Assess points per game (PTS), assists (AST), and win shares (WS) among the top 10 points-per-game draft players. 


### We will be using the following webpages:
1. Lakers 2024-25 Season https://www.basketball-reference.com/teams/LAL/2025.html
2. 2024-25 Season Summary (includes Eastern Conference) https://www.basketball-reference.com/leagues/NBA_2025.html
3. Lebron: https://www.basketball-reference.com/players/j/jamesle01.html
4. 2024-2025 Coaches: https://www.basketball-reference.com/leagues/NBA_2025_coaches.html
5. 2024 NBA Draft: https://www.basketball-reference.com/draft/NBA_2024.html

## Citation:
* cloudscraper library is imported from Python Project: https://pypi.org/project/cloudscraper/
* This library was used to bypass anti-bot pages in order to successfully perform webscraping.
