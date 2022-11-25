# Bike-Sales-Project

This project uses Excel to clean data, create pivot tables from cleaned data, create charts from pivot tables, and then assemble a dashboard with some demographic and customer findings.
The dataset used in this project contains demographic data on 1,026 individuals, including:
* Marital status
* Gender
* Income
* Children
* Education
* Occupation
* Whether or not they are a home owner
* Number of cars they own
* Commute distance
* Region
* Age
* Whether or not they purchased a bike

After getting to know the data, my first step was to remove the duplicates. Then, I wanted to convert the data in the Gender column from "M" and "F" to "Male" and "Female", so that it would be easier to understand in a visualization. I also standarized the currency in the Income column.
Since a large range of ages are represented in this data, and I wanted to create easy-to-understand visuals, I created age brackets by using a nested IF statement to break the ages into three (VERY) broad categories.

Once my data was more usable, I created three pivot tables to later turn into visualizations. All three of these tables compare people who did buy a bike to people who did not:
* Relationship between customer gender and income
* Frequency of each customer age bracket
* Length of customer commute

After assembling the three charts into a dashboard, I added 3 slicers to further explore marital status, region, and education, and their impact on customer purchase of a bike.

The finished product helps us answer questions about:
* Impact of customer gender and income differences on purchase of bike
* Impact of age bracket on purchase of bike
* Impact of commute distance on purchase of bike

If you're interested in trying your hand at this project, check out [Alex the Analyst's video.](https://youtu.be/opJgMj1IUrc)
Thanks for reading!
