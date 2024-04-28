# Excel-ling

I worked on the Google Data Analytics Capstone Project, Track 1, Case Study 1. I will be diving into the background, my full process of cleaning, analyzing, and visualizing the data, along with my final suggestions and summary of the data. 

# **BACKGROUND**
Cyclistic is a bike-sharing program that features more than 5,800 bikes and 600 docking stations. It offers reclining bikes, hand tricycles, and cargo bikes, making it more inclusive to people with disabilities and riders who can't use a standard two-wheeled bike. It was founded in 2016 and has grown tremendously into a fleet of bicycles that are geotracked and locked into a network of 692 stations across Chicago. The bikes can be unlocked from one station and returned to any other station in the system at any time. 

Previously, Cyclistic's marketing strategy tried to build general awareness and appeal to broad consumers. It has flexible pricing plans: single-ride passes, full-day passes, and annual memberships. Those who purchase single-ride or full-day passes are referred to as casual riders while those who purchase annual memberships are Cyclistic members. 
My Role: In this scenario, I am a junior data analyst at Cyclistic and my team has been tasked with the overall goal (see below) of designing marketing strategies 

Overall Goal: Design marketing strategies aimed at converting casual riders into annual members.
Business Question: "How do annual members and casual riders use Cyclistic bikes differently?"

Below I will be describing my roadmap for this.

Case Study Roadmap 

PROCESS:
Overview: I first analyzed the data separately (each month) in Excel, then used R to analyze the data as a whole (one year). Finally, I created a dashboard in Tableau and used Figma to support the design elements. 

My First tool was Microsoft Excel because I was most familiar with and I could get a general understanding of the data quickly. I did not combine all of the spreadsheets into one because that would've taken more processing power and I would have been a pcless guy lol.

I began downloading the data from divvy-tripdata and turning the .csv files into Excel spreadsheets. I downloaded the most recent year of data which was at the time of starting my project: 

12 Months, Year 2023
January
February
March
April
May
June
July
August
September
October
November
December

Added 4 columns to all of the months:
Created **ride_length** calculated the total ride length for each trip using the start_at column which was: ending time minus starting time. 
Created **day_of_week, Hour, and Timex(Minutes)** and calculated the day of the week for each trip using the start_at column date.
Went over the business task and the information I had at hand and how that could be used to figure out how members and casual riders use the bike service differently

Came up with metrics to look at such as : 
**total number of rides per hour, per day of the month, per season, per day of the week, between member and casual and for different bike types 
Average ride length between members and casual**

For every month in Excel created pivot tables and charts to go with the analysis (this took the longest):

Total Rides per Weekday - calculated the total rides for members and casual and separated it by day of the week; used a cluster column chart
Average Ride Length - calculated the average ride length for members and casual and separated it by day of the week;
Total Rides per Hour -  calculated the total rides for members and casual separated by the time of the day (24hr); 
Total Rides per Day -  calculated the total rides for members and casual separated by the day of the month; 
Total Rides per Bike Type - calculated the total rides for members and casual separated by Bike type;

I also created a Google Docs Notes list where I wrote down the exact steps for each month (had a checklist) and included my insights for each month.

Well after reading all this you must be getting bored. Then Let's get to the visualization part

So here's my first chart ![image](https://github.com/imporu/Excel-ling/assets/161977105/9bf61e97-e92f-4643-856f-450918cda348)

