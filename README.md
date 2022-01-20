# W205 (Data Engineering) 
Project 1: Query Project

- In the Query Project, I practiced writing SQL quiries while learning about
  Google Cloud Platform (GCP) and BiqQuery. Given the problem statement below, I answered key business-driven
  questions using public datasets housed in GCP. All the work was performed using the web UI (BiqQuery) and
  the command-line tools, and worked them into Jupyter file (Report.ipynb).

#### Problem Statement

- You're a data scientist at Lyft Bay Wheels (https://www.lyft.com/bikes/bay-wheels), formerly known as Ford GoBike, the
  company running Bay Area Bikeshare. You are trying to increase ridership, and
  you want to offer deals through the mobile app to do so. 
  
- What deals do you offer though? Currently, your company has several options which can change over time.  Please visit the website to see the current offers and other marketing information. Frequent offers include: 
  * Single Ride 
  * Monthly Membership
  * Annual Membership
  * Bike Share for All
  * Access Pass
  * Corporate Membership
  * etc.

Through My own exploratory data analysis (EDA) I answered the following questions:

  * What are the 5 most popular trips that you would call "commuter trips"? 
  
  * What are your recommendations for offers (justify based on your findings)?

-Because there was no column labeled "commuter trip". I needed need to do quite a bit of data exploration using SQL queries to determine your own definition of a communter trip.  In data exploration process, I found a lot of dirty data, that was cleaned or filtered out. 

- Likewise to make my recommendations, I needed to do data exploration, cleaning or filtering dirty data, etc. to come up with the final queries that will give you the supporting data for your recommendations. 

-The final report.ipynb also demonstrates the use of Pandas, and Matplotlib libraries. 

---

## Data

- (BigQuery tables used) **san_francisco** :

  * bikeshare_stations

  * bikeshare_status

  * bikeshare_trips

- The dynamic tables are found in the dataset **san_francisco_bikeshare**


### Part 1: Examples of Business Questions answered. 

- What's the size of this dataset? (i.e., how many trips)

- What is the earliest start date and time and latest end date and time for a trip?

- How many bikes are there?

- What is the average trip_duration for subscribers and customers?

- What's the most number of trips for 1 bike?

- How many trips are in the morning vs in the afternoon?  

- What are the top 5 "Customer" trips and average ride duration? 
