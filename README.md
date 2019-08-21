# Tableau-Citi-Bike-Analytics
Citi Bike Program Analytics with Tableau

## Background

![Citi-Bikes](Images/citi-bike-station-bikes.jpg)

Since 2013, the Citi Bike Program has implemented a robust infrastructure for collecting data on the program's utilization. Through the team's efforts, each month bike data is collected, organized, and made public on the [Citi Bike Data](https://www.citibikenyc.com/system-data) webpage.

However, while the data has been regularly updated, the team has yet to implement a dashboard or sophisticated reporting process. City officials have a number of questions on the program, build a set of data reports to provide the answers.

* How many trips have been recorded total during the chosen period?

* By what percentage has total ridership grown?

* How has the proportion of short-term customers and annual subscribers changed?

* What are the peak hours in which bikes are used during summer months?

* What are the peak hours in which bikes are used during winter months?

* Today, what are the top 10 stations in the city for starting a journey? (Based on data, why do you hypothesize these are the top locations?)

* Today, what are the top 10 stations in the city for ending a journey? (Based on data, why?)

* Today, what are the bottom 10 stations in the city for starting a journey? (Based on data, why?)

* Today, what are the bottom 10 stations in the city for ending a journey (Based on data, why?)

* Today, what is the gender breakdown of active participants (Male v. Female)?

* How effective has gender outreach been in increasing female ridership over the timespan?

* How does the average trip duration change by age?

* What is the average distance in miles that a bike is ridden?

* Which bikes (by ID) are most likely due for repair or inspection in the timespan?

* How variable is the utilization by bike ID?

## Visualizations

* A static map that plots all bike stations with a visual indication of the most popular locations to start and end a journey with zip code data overlaid on top.

* If you're working with a merged dataset: a dynamic map that shows how each station's popularity changes over time (by month and year) -- with commentary pointing to any interesting events that may be behind these phenomena.

## Citi Bike Program Analysis

* After creating and analyzing our visualizations, there were many phenomena to be uncovered.

* The first being that the trips for the most used bikes are often started on or around the same stations, this may indicate that we need to increase our supply of bicycles in these areas. Adding more bikes to these stations will allow more users to have a bike available as well as preventing the same bikes from enduring heavy usage which will increase our repair fees, or worse, the risk of user injury.

* Another phenomenon that was uncovered from our visualizations, is that most of our riders are between the ages of 27 and 40 with a median age of about 37. However, there are some red flags raised as it appears that we do not confirm age in any way and that the user can say they were born in any year. This was noticed when we had multiple users over 100 years old riding bikes. This is extremely unlikely and caused that data to be filtered. It may be wise to start having users validate their age so we do not have invalid data or even have underage children lying about their age to ride our bikes.

* The final phenomenon that I want to recognize is that the most popular start times are at 8 AM and 6 PM. This makes sense as it is similar to when rush hour occurs. People take a bike as they are going to work in the morning and then again when they leave work in the evening. The bump around 6 PM could also be from students leaving class for the day.