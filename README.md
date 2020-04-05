# NBA-Shot-Chart-Analysis #
Used Python and Pandas to extract player data from NBA API into individual team dataframes

Pulled data from NBA API provided by https://github.com/swar

Created Columns representing 14 specific spots on the court while also including total columns for 2pt, 3pt and Overall Total

Then created the columns for Percentile Rank & League Rank for each location.

For each location, I pulled the average attempts and only included those players who have attempted at least that average.
The final chart only includes those players who attempted at least the average for total shot attempts

Used the "coolwarm" colormap in the Percentile columns to show visually how well a player is shooting by looking through the rows and how well the team is generally shooting by looking through the columns

Created a specific function to highlight in gold those percentages that are in the Top Ten for the league in each location

## Below is the LA Clippers Chart for the 2019-20 season so far:

![Alt text](https://github.com/jkalter86/NBA-Shot-Chart-Analysis/blob/master/LA%20Clippers.png)
