                                                        # Bike-sales-dashboard

# Introduction:

This project involved a comprehensive analysis of bike sales data to identify key consumer trends and preferences in the bike market. The data, structured across 13 columns, provided a detailed view of customer demographics, socioeconomic status, and purchasing behaviors.

# Dashboard

![Picture3](https://github.com/vkvasan944/Bike-sales-dashboard/assets/135627385/ee6bd093-fda8-4316-ba53-78fac9637b08)



# Data Preparation and Transformation:

**Duplicate Removal** : We began by removing duplicates, eliminating 26 duplicate entries and retaining 1000 unique records.

**Data Cleaning**: The 'Marital Status' and 'Gender' columns were standardized for clarity ('M' to 'Married', 'S' to 'Single', 'F' to 'Female', and 'M' to 'Male').

**Formatting**: The 'Income' column was set as Currency type, and decimal places were removed.

**New Column Creation**: An 'Age Groups' column was introduced, categorizing ages into 'Old', 'Middle Aged', or 'Adolescent' based on an Excel formula.

**Value Modification**: In the 'Commute Distance' column, '10+ Miles' was changed to 'More than 10 Miles' for better interpretation.


# Pivot Table Analysis and Visualization:

**Gender and Income Analysis** : Pivot tables revealed that both male and female customers who purchased bikes had higher average incomes than those who did not.

**Commute Distance and Purchase Behavior**: A line chart showed fewer bike purchases with increasing commute distances.

**Age Group and Purchase Behavior**: Analysis indicated that middle-aged customers were most likely to purchase bikes, with adolescents being the least likely.

**Occupation and Purchase Behavior**: A bar chart revealed professionals as the largest group of bike purchasers, with clerical workers being the least likely.

**Children and Purchase Behavior**: A pie chart showed that customers with no children were the largest segment of bike purchasers.


# Dashboard Enhancement with 'Reset' Button:

To augment the user experience on the dashboard, a 'Reset' button was implemented through a macro. This button is specifically programmed to reset all slicers, swiftly reverting them to their original, unfiltered state. To ensure seamless functionality and synchronization across the dashboard, a 1-second delay was strategically incorporated into the macro using VBA. This delay allows for the full application of slicer changes, thereby enhancing the dashboard's overall interactivity and efficiency in data analysis.


# Insights Gained:

**Bike Purchase by Children Count**: A decline in bike purchases was observed with an increase in the number of children.

**Purchase Count by Occupation**: Professionals dominate bike purchases, highlighting potential unmet needs in the manual worker segment.

**Purchase Count by Age Group**: Middle-aged customers are key purchasers, with a decline in the old age group.

**Purchase Count by Commute Distance**: Shorter commute distances correlate with higher bike purchases.

**Average Income by Gender**: Males who purchased bikes generally had higher incomes, suggesting income influences bike purchasing decisions.


# Conclusion:

These insights can guide marketing strategies, such as targeting individuals with no children or engaging manual workers and those with longer commutes. Understanding income dynamics can also assist in pricing strategies and product placement. The use of pivot tables, charts, and slicers provided a dynamic and detailed view of the data, enabling informed decision-making for targeting and customer engagement in the bike market.
