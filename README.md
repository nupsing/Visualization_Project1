# Description of Design Process
I read the input files first to understand how to connect the dataset with each other like the provided dataset for streets, pumps, deathdays and death age sex. Read the supporting page to understand the overall view of cholera outbreak in London.
Reference: https://en.wikipedia.org/wiki/1854_Broad_Street_cholera_outbreak
1. I created the streets chart first and included the location of pumps using the given data for pumps location.
3. Selected the colors for workhouse and brewery based on color coding palette.
4. Tried to plot a seperate chart for gender and number of deaths per gender.
5. Plotted the count of deaths per day line chart with x-axis representing the dates and y-axis representing the total deaths.
6. The labels shows variables and colors used to represent the data. For example, for representing gender used blue and for female used orange.
7. Different color coding is used for age groups.
8. Included the given data of gender and age deaths in streets chart.
9. Tried to establish linking on hover of line chart, the streets chart will show the points where the deaths took place.


# Justification of Design Decisions
1. Left chart shows the streets and location of pumps, brewery and deaths in these locations.
2. Right chart shows the count of deaths per day.
3. I have used GitHub pages functionality to host D3 html page.
4. For Documentation, I have used mark down format, a readme.md has been created in my gitHub repository itself and it's link is accessible via a button from my Visualization.
5. We can see that the maximum deaths during August 31, 2022 and September 5th, 2022. And the peak deaths happened on September 1st, 2022.
Below image shows count of deaths per day plotted using Tableau which matches the results shown in final D3 vizualization. For example:- The death count on September 1st, 2022 is 143.

![Death Count By Date](https://github.com/nupsing/Visualization_Project1/blob/main/images/Tableau_LineGraph.png)
