# AIRPLANE CRASHES AND FATALITIES SINCE 1908 
![Dashboard](https://github.com/Mr-Art-coder/Aircrashes-Data-Visualization/blob/main/Dashboard.JPG)

----

# Introduction

This is a Project on Airplane Crashes and Fatalities Since 1908. In this visualization, the numbers of the following which include, location, fatality onboard, fatality on the ground, people aboard, people who escaped, and the numbers of operators were determined using cards while other analyses were made using different visuals.

-----

# Problem Statement
![Statement](https://github.com/Mr-Art-coder/Aircrashes-Data-Visualization/blob/main/Problem%20Statement.png)

In the 30Daysoflearning course organized by Microsoft, a dataset was given which consists of data on airplane crashes and fatalities since 1908 with the task to tell a visual story from this Data. The motive behind this project is to analyze and visualize some key details about the perilous crashes which seized the lives of people, to find out the highest fatality rate, the operator involved, the date, time numbers of people aboard during the fatality, and the number of people who escaped death.
After a critical examination of the dataset, I was able to come out with the following questions which were later visualized: 
-	What is the totality of people onboard in all the crashes?
-	What is the totality of the people who were aboard and went with the crashes?
-	What is the totality of the people who were not aboard but were killed on the ground during the crashes?
-	Has anybody escaped death before?
-	How many locations and operators are in the data?
-	Which operator has the highest record of crashes
-	Where was the location where the major crash occurred, and what time and year did major crashes occur?

All these questions were answered after a thorough analysis and visualization of the data

----

# Data Sourcing

The data was cloned from the 30daysoflearning GitHub repository which was originally gotten from Kaggle website. The data which is in CSV format consists of a dimension table that contains all the information needed.

----

# Data Transformation
![Power Query](https://github.com/Mr-Art-coder/Aircrashes-Data-Visualization/blob/main/Power%20Query.JPG)

The data contains 13 columns which include, Date, Time, Location, Operator, Flight, Route, Type, Registration, Cn/in, Aboard, Fatalities, Ground, and Summary.
The transformation started by using the first row as a header, then # was removed from the spelling of Flight and Cn/in was changed to Serial Number for easy understanding of the data.
In the flight column, all – values were removed. A new column was added, for example, this was achieved by inserting day, month, and year from the Date column. Also, to find the number of people who escaped the crashes, a new column was added named Escaped.

----

# Analysis 
![Operator Page](https://github.com/Mr-Art-coder/Aircrashes-Data-Visualization/blob/main/Operator%20Page.JPG)

To derive the conclusion and have to concreate dashboard that answers all our questions, two pages were used to analyze the data using different visuals with different names, the Operator page and Location page.

![Location Page](https://github.com/Mr-Art-coder/Aircrashes-Data-Visualization/blob/main/Location%20Page.JPG)

Numbers of people aboard, numbers of fatalities, numbers of causalities on ground, numbers of people who escaped, etc. were analyzed by Operator on the operator page, while the aforementioned was analyzed by Location on the operation page. Slicer was used to analyze the two pages by Type and date

----

# Visualization
Different visuals were used in the project, cards, line chart, stacked chart, donut chart, and ribbon chart were used to analyze and visualize in the Operator page whiletreemaprd, tree map, line, and clustered column chart, and stacked bar chart were used to analyze and visualize in the Location page

----

# Findings 
![Dashboard](https://github.com/Mr-Art-coder/Aircrashes-Data-Visualization/blob/main/Dashboard.JPG)
Since 1908, Aeroflot Operator recorded the highest number of fatalities of 7156 people which also caused the death of 28 people on the ground in all the years of crashes. Only 1714 people escaped the crashes out of 8870 aboard. This Operator had involved in 179 crashes.
The highest number of causalities, in a year, happened in Tenerife, Canary Islands where 583 lives were lost out of 644 people who were aboard 61 people escaped. This crash occurred in 1977 at 17:07 (6:07 pm). The flight types involved were Boeing B-747-121 and Boeing B-747-206B operated by Pan American World Airways and KLM respectively. Both aircraft crashed in Las Palmas in Tenerife. They were diverted to the location because of a bombing.

----

Hi, I'm on [Twitter](https://twitter.com/AdegunleRT) and [Linkedin](https://www.linkedin.com/in/adegunleraphael/)



