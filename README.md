# Pulled off School Bookshelves: the Sweeping Book Removal Wave

Goal:
Compare and see how the low food access situation has changed across 7 racial groups (American Indians or Alaska Natives, Asians, Black or African Americans, Hispanic or Latino, Native Hawaiians and other Pacific Islanders, White and people with other or multiple race) from 2015 to 2019.
Findings:
While low food access appeared on the mend for most racial groups since 2015, a growing number of Black or African Americans still faced challenges accessing food resources in 2019. Native Hawaiians and other Pacific Islanders, as well as American Indians or Alaska Natives, came with the most notable improving shifts.
Process of Data Collection:
1. Download the Food Access Research Atlas datasets for both 2019 and 2015 from Food Access Research Atlas: https://www.ers.usda.gov/data-products/food-access-research-atlas.
2. Based on the four distance categories — half a mile, one mile, 10 miles and 20 miles — to a food resource, set up 7 Excel tables (with one 2019 sheet and one 2015 sheet) including columns that count population with low food access at each distance degree for the 7 racial groups.
Process of Data Analysis:
1. Data Cleaning:
a) For the 7 Excel tables, cut out missing population data on low food access.
b) Filter 2015 data sheets to only include rows with the same Census Tract as 2019 data sheets.
2. Add up the total population with low access population at half a mile, one mile, 10 miles and 20 miles.
3. Create dictionaries to store both the 2015 and 2019 data for each distance degree.
4. Combine the 2015 and 2019 dictionaries and turn them into dataframes.
5. For each racial group, upload resulting dataframes to DataWrapper to plot "Grouped Bars" charts.
6. Look up for increase and or decrease in population with low food access from 2015 to 2019.
Skills/Approaches in Use:
1. Excel - data collection
2. Python - Pandas: data cleaning and analyzing
3. HTML: Webpage building
4. DataWrapper: plotting
Looking Ahead:
1. Chart Type Selection: I'm still thinking about how to better visualize the 7 racial groups on one chart or fewer charts to create a more digestable, side-by-side comparison of their low food access population change from 2015 to 2019.
2. Consideration of Other Variables: If I had more time, it would be interesting to take households' access to vehicles into account as well and see how it works with distance in miles to affect racial groups.
3. Research: Search for policies/subsidies in 2015 and 2019 to better understand possible reasons for the still worse low food access situation for Black or African Americans and better situation for Native Hawaiians and other Pacific Islanders, and American Indians or Alaska Natives.

