# Pulled off School Bookshelves: the Sweeping Book Removal Wave

## Goal:
Analyze and visualize the situation of book ban across the United States.

## Findings:
The past academic year has seen an unprecedented surge in book bans, reaching the 10,000 plus springboard for the first time, a significant jump from the 3,362 records of the previous year. State-wise, Florida and Iowa turned out with the most bans in the 2023-2024 school year. Book bans in these two states reeled from state legislation, taking together effect with initiatives from local districts. 

## Process of Data Collection:
1. Download the Food Access Research Atlas datasets for both 2019 and 2015 from Food Access Research Atlas: https://www.ers.usda.gov/data-products/food-access-research-atlas.
2. Based on the four distance categories — half a mile, one mile, 10 miles and 20 miles — to a food resource, set up 7 Excel tables (with one 2019 sheet and one 2015 sheet) including columns that count population with low food access at each distance degree for the 7 racial groups.

## Process of Data Analysis:
1. Data Cleaning:
a) For the 7 Excel tables, cut out missing population data on low food access.
b) Filter 2015 data sheets to only include rows with the same Census Tract as 2019 data sheets.

2. Add up the total population with low access population at half a mile, one mile, 10 miles and 20 miles.
3. Create dictionaries to store both the 2015 and 2019 data for each distance degree.
4. Combine the 2015 and 2019 dictionaries and turn them into dataframes.
5. For each racial group, upload resulting dataframes to DataWrapper to plot "Grouped Bars" charts.
6. Look up for increase and or decrease in population with low food access from 2015 to 2019.

## Skills/Approaches in Use:
1. Excel - data collection
2. Python - Pandas: data cleaning and analyzing
3. Python - Treemap making
4. DataWrapper: map plotting
5. HTML: Webpage with scrollytelling style

## Looking Ahead:
1. Chart Type Selection: I'm still thinking about how to better visualize the 7 racial groups on one chart or fewer charts to create a more digestable, side-by-side comparison of their low food access population change from 2015 to 2019.
2. Consideration of Other Variables: If I had more time, it would be interesting to take households' access to vehicles into account as well and see how it works with distance in miles to affect racial groups.
3. Research: Search for policies/subsidies in 2015 and 2019 to better understand possible reasons for the still worse low food access situation for Black or African Americans and better situation for Native Hawaiians and other Pacific Islanders, and American Indians or Alaska Natives.
