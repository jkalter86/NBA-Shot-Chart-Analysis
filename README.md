# NBA-Shot-Chart-Analysis #

I am a data analyst looking to expand my data science capabilities who also happens to be a huge NBA fan. I therefore decided to create projects where I align that goal and passion. The first project I decided to focus on involves detailed shot chart visualizations. The end goal of this project is to find the ideal location for the three-point line using shot chart data from the NBA API provided by https://github.com/swar

•	In part one of my project I use Python, Pandas and Numpy to extract player data into individual team dataframes to create detailed visualizations of shot chart data, making it quick and easy to see how a particular team and its most volume shooters are performing at all twelve areas on the court

•	In part two of my project I incorporate Plotly to create scatterplots with basketball court visualizations that display shot charts with the volume and % accuracy at all twelve areas of the court for each team in comparison to the rest of the league

•	Added a defensive shot chart component to display how well each team is defending each position on the court

•	I am working on using both the offensive and defensive shot charts to recommend ideal three-point line locations for all thirty teams


## Roster DataFrame output from Detailed_NBA_ShotChart_DataFrame.ipynb

• Created Columns representing 14 specific spots on the court and their league Percentile Ranks while also including total columns and their league Percentile Ranks for 2pt, 3pt and Overall Total for each player

• For each location, I pulled the average attempts and only included those players who have attempted at least that average.
The final chart only includes those players who attempted at least the average for total shot attempts

• Used the "coolwarm" colormap in the Percentile columns to show visually how well a player is shooting by looking through the rows and how well the team is generally shooting in each location by looking through the columns

• Created a specific function to highlight in gold those percentages that are in the Top Ten for the league in each location

• Can run for each team; outputting the current roster and either current or historical shot data

• Below is the LA Clippers Chart for the 2019-20 season so far:


![Alt text](https://github.com/jkalter86/NBA-Shot-Chart-Analysis/blob/master/LA%20Clippers.png)

## Scatter Plot output from Team - Visual_ShotChart-Offensive & Defensive.ipynb
• Detailed offensive & defensive shot chart of every NBA team; with average distances made(offensive) and made against(defensive) from three (Above the Break) and overall two

• Below are the offensive & defensive shotcharts for the Lakers and Rockets for the 2019-20 season so far:

![Alt text](https://github.com/jkalter86/NBA-Shot-Chart-Analysis/blob/master/Los%20Angeles%20Lakers.png)
![Alt text](https://github.com/jkalter86/NBA-Shot-Chart-Analysis/blob/master/Houston%20Rockets.png)
