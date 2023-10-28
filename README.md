Data Analysis : 120 Years Of Olympis History -Python

**Intoduction**
This is an Exploratory Data Analysis project to analyze the modern Olympic Games, including all the Games from Athens 1896 to Rio 2016.
This analysis provides an opportunity to ask questions about how the Olympics have evolved over time, including questions about the participation and performance of women, different nations, and different sports and events.

**Data Source**
The dataset is collected from here. The dataset contains two files: athlete_events.csv and noc_regions.csv.
The file athlete_events.csv contains 271116 rows and 15 columns. Each row corresponds to an individual athlete competing in an individual Olympic event (athlete events). The columns are:

ID - Unique number for each athlete
Name - Athlete's name
Sex - M or F
Age - Integer
Height - In centimetres
Weight - In kilograms
Team - Team name
NOC - National Olympic Committee 3-letter code
Games - Year and season
Year - Integer
Season - Summer or Winter
City - Host city
Sport - Sport
Event - Event
Medal - Gold, Silver, Bronze, or NA
The file noc_regions.csv contains 230 rows and 3 columns. Each row corresponds to an individual region. The columns are:

NOC (National Olympic Committee 3 letter code)
region
notes
**Python Web App**
This project is deployed on Streamlit Community Cloud. You can access the web app here.
Note: All the graphs and charts are interactive. You can hover over the graphs and charts to get more information. You can also download the graphs and charts in png format.

**Features of the Web App**
The web app provides a brief overview of the dataset. It provides users to choose between 4 options to explore the dataset. The options are:

1.Medal Tally
2.Overall Analysis
3.Country-wise Analysis
4.Athlete-wise Analysis
1.**** Medal Tally***
This section provides the medal tally of all the countries that have participated in the Olympics. The medal tally is displayed in a table format. The table can also be filtered by selecting the Country Name and Year from the dropdown list.

2. **Overall Analysis**
This section provides the overall analysis of the Olympics. It provides information like:

Top Statistics of the Olympics (Edition, Hosts, Sports, Events, Nations, Athletes)
1.No. of countries participating in the Olympics over the years (Line Graph)
2.No. of events organized over the years (Line Graph)
3.No. of athletes participating over the years (Line Graph)
4.Correlation between the no of Events for each and every Sport w.r.t Year (Heatmap)
5.Table of top 15 athletes who have won the most number of medals in the Olympics. This table can also be filtered by selecting the Sports Name from the dropdown list.
3. **Country-wise Analysis**
This section provides a country-wise analysis of the Olympics. It contains a dropdown list where user can select Country Name, based on that the section will display the following information:

1.Medal Tally over the years for that country (Line Graph)
2.In which sport does the country excel the most (Heatmap)
3.Top 10 athletes of that country (Table)
4. **Athlete-wise Analysis**
  This section provides an athlete-wise analysis of the Olympics.

1.Distribution of Age of the athletes for Winning Medals (Curves)
2.Distribution of Age w.r.t Sports only who have won Gold Medals (Curves)
3.Gender Ratio with Height vs Weight of the Athletes. Here users can select a Sport as per their choice from the dropdown list. (Scatter Plot)
4.Men Vs Women Participation Over the Years (Line Graph)


Here Some screenshot :-

![image](https://github.com/shivam2001s/OlymAnalytiXpert/assets/136186606/7529b544-d5af-4a68-b97d-3da28e03d8d9)


![image](https://github.com/shivam2001s/OlymAnalytiXpert/assets/136186606/3c73bd74-ed47-46f1-b209-382a454b9949)


![image](https://github.com/shivam2001s/OlymAnalytiXpert/assets/136186606/a77a42ce-97f7-4d31-b66f-6d5c698913d2)


