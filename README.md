# Description of Design Process
I read the input files first to understand how to connect the dataset with each other like the provided dataset for streets, pumps, deathdays and death age sex. Read the supporting page to understand the overall view of cholera outbreak in London.

1. I created the streets chart from the provided streets.json file.
2. Included the location of pumps using the given data for given pumps.csv file with pumps location.
3. Included majot streets names and plotted the Landmarks likes Workhouse and Brewery.
4. Plotted death by age and gender on streets map using input file deaths_age_sex.csv. Provided radio button for easy user navigation on the streets map.
5. Plotted the count of deaths per day line chart with x-axis representing the dates and y-axis representing the total deaths.
6. The radio button shows style color to represent the data. For example, for representing gender used blue and for female used palevioletred.
7. Different color coding is used for different age groups.
9. Established linking on hover of line chart, the streets chart will show the points where the deaths took place till the partcular date selected.


# Justification of Design Decisions
1. Left chart shows the streets and location of pumps, brewery and deaths in these locations. 
   Gender radio buttons: On select of either male and female radio button, individual deaths in these category will show up. On selection of Both, both male and female    deaths will be shown.
   Age radio buttons: On select of different age groups like 0-10, 11-20, 21-40, 41-60, 61-80, 80+ radio button, individual deaths in these categories will show up. On    selection of All Ages, deaths in all age groups will be shown.
2. Hover functionality of the streets chart shows the age group and gender irrespective of the radio button selection.

Below chart shows snapshot of All Ages, tells us whether the person died in that gae group is male or female and where that death tool place. Example, we can see that the highlighed death happened near Rupert Street and it was identified at Female in her later 80s.

![Streets map when All Ages is selected](https://github.com/nupsing/Visualization_Project1/blob/main/images/StreetsChart.png)

3. Right chart shows the count of deaths per day.

Below chart shows snapshots of cummulative deaths on the streets chart when a particluar point is selected on the line chart. Also, from this we can get an approximate idea when the desath took place. For Example, in image 1 the death point was not showing up when the user selected Sep 01 and it started showing up when Sep 02 is selected in image 2. From this instance, it can be infered that this death tool place between Sep 01 and Seop 02.

![Particular Death point identification when Sep 01 is selected](https://github.com/nupsing/Visualization_Project1/blob/main/images/LineChartImage1.png)

![Particular Death point identification when Sep 02 is selected](https://github.com/nupsing/Visualization_Project1/blob/main/images/LineChartImage2.png)

4. I have used GitHub pages functionality to host D3 html page.
5. For Documentation, I have used mark down format, a readme.md has been created in my gitHub repository itself and it's link is accessible via a button from my Visualization.
6. We can see that the maximum deaths during August 31, 2022 and September 5th, 2022. And the peak deaths happened on September 1st, 2022.
Below image shows count of deaths per day plotted using Tableau which matches the results shown in final D3 vizualization. For example:- The death count on September 1st, 2022 is 143.

![Death Count By Date](https://github.com/nupsing/Visualization_Project1/blob/main/images/Tableau_LineGraph.png)


References: 
https://en.wikipedia.org/wiki/1854_Broad_Street_cholera_outbreak
https://d3js.org/
https://charlesreid1.com/wiki/D3
https://bost.ocks.org/mike/nest/
https://www.tutorialsteacher.com/d3js/loading-data-from-file-in-d3js
	
