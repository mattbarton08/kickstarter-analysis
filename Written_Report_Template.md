# Kickstarting with Excel

## Overview of Project

### Purpose
In this project I analyzed campaigns posted to Kickstarter to look for trends that would be helpful to know for the client, a hopeful playwrite looking to raise enough money to fund her first play.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
I  created a pivot chart containing the number of successful, failed, and cancelled campaigns sorted by the month they launched. I included filters for the category to look specifically at theater campaigns and year so that I could look at one year at a time. Time in months is used for the x-axis and the number of campaigns is used for the y-axis.

![Outcomes by Launch Date Chart](https://i.imgur.com/alQ65Ui.png)

### Analysis of Outcomes Based on Goals
I created table with Kickstarter campaigns goals ranging from $0 all the way to $50,000 and up. I then added columns for successful, failed, and cancelled campaigns and used the COUNTIFS function to pull the count for each cell from the main data page. I then added columns for the percentages of successful, failed, and cancelled campaigns for each goal range using a simple quotient function. Lastly, I created a line chart using the goal ranges for the x-axis and the percentage for the y-axis.
![Outcomes Based on Goals](https://i.imgur.com/asI2jxZ.png)

### Challenges and Difficulties Encountered
I had to play around with the data a lot as I haven't used Excel a lot in the past. Most of the functions were new to me as were pivot tables and charts, so it took some trial and error to make the data look the way it should.

## Results

### Outcomes Based on Launch Date
The month with the highest rate of successful theater campaigns was May, which would be the month I would recommend launching the client's campaign. October had the highest number of failed campaigns and December had the lowest number of successful campaigns, which tells me that anywhere from October-December would probably not be a good time to launch a Kickstarter campaign.

- What can you conclude about the Outcomes based on Goals?

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?
