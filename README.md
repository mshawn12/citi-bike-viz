# citi-bike-viz
Leveraging Tableau to create data visualizations &amp; dashboards for Citi Bike data
## Background
Congratulations on your new job! As the new lead analyst for the New York Citi BikeLinks to an external site. program, you are now responsible for overseeing the largest bike-sharing program in the United States. In your new role, you will be expected to generate regular reports for city officials looking to publicize and improve the city program.

Since 2013, the Citi Bike program has implemented a robust infrastructure for collecting data on the program's utilization. Each month, bike data is collected, organized, and made public on the Citi Bike DataLinks to an external site. webpage.

However, while the data has been regularly updated, the team has yet to implement a dashboard or sophisticated reporting process. City officials have questions about the program, so your first task on the job is to build a set of data reports to provide the answers.

## Analysis 
- Citi Bike Trip Data was obtained from the <a href="https://s3.amazonaws.com/tripdata/index.html">Citi Bike NYC</a> website
- A combination of Geo Maps, Bar Graphs, Line Graphs, and Pie Charts were used to visualize the data and highlight interesting trends.
- Depending on the visualization, certain data, such as Station Name and Measure Values, were added to the Details. Other Marks such as Color, Size, and Tooltips were used to better tell the story of individual visualizations. 
- Dashboards were created to group together related visualizations such as Start Stations & End Stations as well as Gender comparisons
- A Story was created to order all visualizations in a natural progression as well as a manner that helps break down the data into relevant pieces

## Findings
- Average Trip Duration by Birth Year from 1899-1997 seems to have been at its highest from the late 1930s to the early 1950s and was generally on the decline for the last 40 years of data collection, with the exception of 1995 where it hit its peak. 
<img src="https://github.com/mshawn12/citi-bike-viz/blob/main/images/avg_duration_by_birthyear.png?raw=true">
- On average, the data shows that females have longer trip durations than males
<img src="https://github.com/mshawn12/citi-bike-viz/blob/main/images/avg_duration_by_gender.png?raw=true">

## Instructions

### Before You Begin
- Save this assignment to your Tableau Public account rather than GitHub.
- If you haven't already, make sure to create a Tableau Public accountLinks to an external site..
- The free tier of Tableau only lets you save to their public server. So, each time you save your file, it will be uploaded to your Tableau Public profile.
- You can load and continue working on the same workbook.
- When you finish your assignment, you will submit the URL to your Tableau Public workbook along with any additional files used in your analysis.

### Instructions
Your task in this assignment is to aggregate the data found in the Citi Bike Trip History Logs and find two unexpected phenomena.

1. Design 2–5 visualizations for each discovered phenomenon (4–10 total). You may work with a timespan of your choosing. Optionally, you can also merge multiple datasets from different periods.
    - The following are questions you may wish to answer. Do not limit yourself to these questions; they are suggestions for a starting point. Be creative!
        - How many trips have been recorded in total during the chosen period?
        - By what percentage has total ridership grown?
        - How have the proportions of short-term customers and annual subscribers changed?
        - What are the peak hours when bikes are used during the summer months?
        - What are the peak hours when bikes are used during the winter months?
        - Today, what are the top 10 stations in the city for starting a journey? Based on data, why do you hypothesize these are the top locations
        - Today, what are the top 10 stations in the city for ending a journey? Based on data, why?
        - Today, what are the bottom 10 stations in the city for starting a journey? Based on data, why?
        - Today, what are the bottom 10 stations in the city for ending a journey? Based on data, why?
        - How does the average trip duration change by age?
        - What is the average distance in miles for a bike trip?
        - Which bikes (by ID) are most likely due for repair or inspection in the timespan?
        - How variable is the utilization by bike ID?

2. Use your visualizations (not necessarily all of them) to design a dashboard for each phenomenon. The dashboards should be accompanied by an analysis explaining why the phenomenon may be occurring.

3. Create one of the following visualizations for city officials:
    - Basic: A static map that plots all bike stations with a visual indication of the most popular locations to start and end a journey, with zip code data overlaid on top.
    - Advanced: A dynamic map that shows how each station's popularity changes over time (by month and year). Again, with zip code data overlaid on the map.
    - The map you choose should also be accompanied by a write-up describing any trends that were noticed during your analysis.

4. Create your final presentation:
    - Create a Tableau story that brings together the visualizations, requested maps, and dashboards.
    - Ensure your presentation is professional, logical, and visually appealing.

### Sharing Your Work
To share your work, save your workbook to Tableau Public and submit the URL so that your TAs can grade it.

Save by using shortcuts (CTRL + S or CMD + S), or by clicking "File" then "Save to Tableau Public."
<img src="https://static.bc-edx.com/data/dl-1-2/m18/lms/img/05-save_workbook.jpg">

After saving, the visualization will be uploaded to your profile, which will automatically open in a new browser window. Adjust the settings of your new visualization by clicking the gear on the toolbar and toggling where to show the visualization and to allow access.
<img src="https://static.bc-edx.com/data/dl-1-2/m18/lms/img/05-tableau_public_viz_settings.jpg">
