# HOMEWORK-1 :  **U.S. Voters (2012)**
Using the PivotTable created in the U.S. Voters case study, complete the following:
1.	How many states had a Voter Population % below 55%? Which states?
2.	How many confirmed voters in CA were over 65 years old in 2012? What percentage does that represent out of the total confirmed voters in CA? What percentage out of the confirmed voters in the entire country?
3.	Show both Citizen Population and Confirmed Voters by Age, as % of Column Total. What percentage of the citizen population do 45 to 64 year olds represent? What percentage of the confirmed voter population?   
4.	Create a new calculated field named "Voter Turnout" (Confirmed Voters/Registered Voters), formatted as a percentage with 1 decimal point. Which state had the highest voter turnout rate? What about among 18-24 year old voters specifically?
5.	As a politician seeking to improve voter turnout rates among young adults (18-24), which particular states would you target first?

# HOMEWORK- 2 : **San Francisco Salaries**
Using the PivotTable created in the San Francisco Salaries case study, complete the following:
1.	Filter and sort the Pivot to show the 5 employees who earned the highest Base Pay in 2011. Who were they?
2.	Add a calculated field named "% Other Pay" (Other Pay/Total Pay), formatted as a percentage with 1 decimal. How many job titles earned only Other pay in 2012?
3.	Among employees with >=$100k Base Pay in 2012, Did any employee earn more than 50% of their salary from Other Pay? If so, who?
4.	Clear all filters and pull in Job Category and Job Title as row labels (Titles sorted alphabetically), then group any titles including the word "Curator" into a new category called "Curator". How many employees held some sort of Curator position in either 2012 or 2013? Among those, who earned the highest average base pay?

# HOMEWORK- 3 : **Shark Attack Records**
Using the PivotTable created in the Shark Attack case study, complete the following:
1.	Show the count of attacks by country -- which 3 countries had the highest number of reported attacks over the past 5 years (2012-2016)? During this period, what % of reported attacks occurred in Spain?
2.	Drag the "Area" field to the PivotTable row labels, change the Report Layout to Outline, and filter to show the top 5 areas by count of Case Number, by country. Where in South Africa were shark attacks most frequently reported over the past 5 years?
3.	Replace "Area" with "Type" and show the Count of Case Number values as % of Parent Total for each country. What % of attacks in New Zealand were unprovoked? How many cases?
4.	Filter the Pivot for the USA only, and create a PivotChart to show the count of shark attacks by "Area". Use a column chart, and hide all field buttons. Try changing the chart type to a Donut or Bar Chart instead.
5.	What was Darren Good doing when he was attacked? When did this happen? (Note: I did not edit this record)

# HOMEWORK- 4 :  **Stock Market Data**
Using the PivotTable created in the Stock Market case study, complete the following:
1.	Create a calculated field named "Daily Spread" (High - Low), formatted as currency with two decimal places. On which date in the sample did Amazon (AMZN) see the largest price spread? (note: you may have to remove the Daily Change field)
2.	Sort dates oldest to newest, and conditionally format the Daily Spread field as a Color Scale, from white (lower values) to green (higher values). Since a large price spread isn't necessarily good or bad, edit the color scale to show shades from white to blue (instead of green).
3.	Drag in another instance of Volume, and show values as Difference From the previous date. When did Google (GOOG) see the largest day-over-day gain in trading volume? The largest drop?

# HOMEWORK- 5 :  **Baseball Team Stats**
Insert a NEW PivotTable using the Baseball Team Stats data, and answer the following:
1.	Create a view showing RS and RA by Team, then create calculated fields named "Net Runs" (RS - RA) and "HR per Game" (HR/G). Which team had the highest Net Run total over the entire sample? What about just the 2015 season?
2.	Update the Pivot to show data for the Red Sox by year. Which years did they win the Division (DivWin)? The Wild Card (WCWin)? The World Series (WSWin)?
3.	Show home runs (HR) by year, for the entire sample (all teams), and drag in a second instance as the % Difference From the previous year. In which season did overall home run totals decrease the most Y-o-Y?
4.	Insert a PivotChart to show Net Runs by year (as columns), with a slicer for Team. Add HR per Game as a line on the secondary axis, and compare the correlations for different teams. How well does HR per Game align with Net Runs?

# HOMEWORK- 6 :  **San Diego Burrito Ratings**
Create a NEW PivotTable from the San Diego Burrito Ratings data, and answer the following:
1.	In your new PivotTable, compare average ratings for Tortilla, Temp, Fillings, Synergy, and Wrap Quality, by Location
2.	Drag in the sum of the "# of Reviews" field and apply a value filter to only show locations with at least 2 ratings. How many locations recorded more than 2 ratings?
3.	Create a calculated field named "Average Total Score", which correctly averages the five scores by location
4.	Add a second instance of Average Total Score and show the values as a Rank based on location. Among those with 2+ reviews, which location is ranked #7?
5.	Add a Color Scale to the Average Total Score field and sort descending. Which location has the lowest score? The highest?
6.	Drag in Yelp Rating as an average, add a Color Scale, and compare against the Average Total Score field. How closely do the two fields align?

# HOMEWORK- 7 :  **Daily Weather Conditions**
Using the PivotTable created in the Daily Weather Conditions case study, answer the following:
1.	How many days in 2016 were categorized as Clear vs. Rain vs. Snow? (use the Conditions field)
2.	What was the average temperature on clear days vs. snowy days? What about the average max temperature?
3.	Update your view to show the # of Days by Month (primary row labels) and Conditions (secondary row labels), and add show the # of Days as the % of the month as a whole. What percent of September days are clear?
4.	Remove the second instance of # of Days, move Conditions to the column labels, and update the Show Values As calculation to % of Row Total. How often did it snow in January 2016, as a percentage of the month?
5.	Remove grand totals and visualize the data as a 100% Stacked Column chart. In how many months of 2016 did it not snow at all? 

# HOMEWORK- 8 :  **Spartan Race Facebook Posts**
Using the PivotTable created in the Spartan Race case study, complete the following:
1.	Create a new view showing the # of Posts by Date of Post. On which date did Spartan Race post most often? What types of posts were they?
2.	Which date showed the highest total engagement volume? Highest engagements per post? Which post drove the strongest reponse on that date?
3.	Create a new calculated field named "Sharability" (Shares / Total Engagements). Which post types tend to be most "sharable"? What time of day do people tend to share most?
4.	Create a new calculated field named "Active Engagements" (Shares + Comments), then modify the formula to measure Active Engagements per Post. What time of day are users LEAST likely to actively engage with Spartan Race Facebook posts? How many active engagements per post during that time of day?


