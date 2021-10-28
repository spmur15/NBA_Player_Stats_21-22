# NBA Player Stats 21-22
basketball-reference.com

Python code to scrape every current NBA player's current season data from basketball-reference.com. 
Gets 140+ columns with all advanced stats offered on basketball-reference.com
Includes these stats: per game, totals, advanced, advanced shooting, adjusted shooting, per 36 min, and per 100 possessions.

Running the python script get_NBA_Player_Data_BR.py will scrape the data from basketball-reference.com and download a .csv file with the data.
The same code is in NBA_21-22.ipynb but broken up for easier reading. There is also some visualizations and a function to easily create a labeled scatter plot of NBA players from the data.

Uses libraries requests, pandas, bs4, and matplotlib
