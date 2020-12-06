# Project 1: Query Project

## Abstract 


In this project, the static tables in the dataset san_francisco : bikeshare_stations, bikeshare_status, bikeshare_trips are investigated to determine the 5 most popular commuter trips among bike share trips operated by Lyft Bay Wheels. In addition, recommendations for offers are raised based on the study of dataset.


This project consists of 3 parts

- In Part 1, Google BigQuery is applied to explore the dataset. 

- In Part 2, the Linux command line is applied for futher study of the dataset, to determine commuter trips. 

- In Part 3, query from a Jupyter Notebook in virtual machine in the cloud. The most 5 popular commuter trip routines are listed. Recommendations for offers are raised with the aid of visualization work. 

*folder data is for csv files storage, folder personal record is for author's personal recording purpose*

---

## Problem Statement

- As a data scientist at [Lyft Bay Wheels](https://www.lyft.com/bikes/bay-wheels), I am working to increase ridership with offering deals through the mobile app.


- Through this project, I have answered these questions: 

  * What are the 5 most popular trips that are called "commuter trips"? 
  
  * What are my recommendations for offers?
  
## Tool Used

- Google BigQuery

- Google cloud virtual machine 

- Jupyter Notebook, Pandas, Matplotlib

---


## Project Outcome

- Definition of commuter trips

  * Subscriber type of the trip is subscriber.
 
  * Duration of trip is no longer than 45 minutes (starts and ends on the same day).
 
  * Start and end stations of trip are different. 
 
  * Trips happen on weekdays (further investigation is required if considering working shift on the weekends)
  
  
- The most popular routines
   
   * From **2nd at Townsend** to **Harry Bridges Plaza (Ferry Building)**
   
   * From **Harry Bridges Plaza (Ferry Building)** to **2nd at Townsend**
   
   * From **San Francisco Caltrain 2 (330 Townsend)** to **Townsend at 7th**
   
   * From **Embarcadero at Sansome** to **Steuart at Market**

   * From **Embarcadero at Folsom** to **San Francisco Caltrain (Townsend at 4th)**
   

- Summary of recommendations 

  * Season membership
  
    * 3 Seasons membership
   
    * Winter season cash back
    
  * Weekend membership

    * Two-day/weekend pass
        
    * Special weekend version of montly/annual membership
  
    * Special weekday version of montly/ annual membership
    
  * Peak hours discounted trial 
 
---       

## Link to the reports

[Project Report](Project_1.ipynb)




