# Module_9_SQLite_Flask
SQLite query and Flask


# 1. Overview of the statistical analysis:

This project required the analysis of temperature data for the months of June and December in Oahu, in order to determine if a surf and ice cream shop business is sustainable year-round.

Using weather data from the hawaii.slite file, we pulled historical tempurture date for June and December using SQAlchemy queries to run our statistical analysis on. We looked at the time period from 2010 to 2017.

# 3. Results:
  - From the graphs below, we can see that June temps ranged from a max of 85 to a min of 64 with the median at 75.
  - December temps ranged from a low of 56 to a high of 83 with the median at 71. A little cooler than in June, but still nice.
![image](https://user-images.githubusercontent.com/86166117/137532278-9a37cdf0-9f63-40f5-9aa7-b48fb8c4685f.png)
    
![image](https://user-images.githubusercontent.com/86166117/137532326-52f45914-c7f7-4474-a019-625e6baebc2b.png)

![image](https://user-images.githubusercontent.com/86166117/137532602-c424b9c6-5a9d-42fe-bb7c-1efe75594558.png)

![image](https://user-images.githubusercontent.com/86166117/137532538-a4dd995a-0139-4b7b-9a3e-4d652e4777c2.png) 


# 3. Summary:
From the data presented above, June temps with a median of 75 and December with a median of 71, indicates that this would be a great spot for a surf and ice cream shop.

In order to verify that the weather was truly optimal, we would suggest running more analysis on the weather data. Specifically the following queries:
  - Analyze all months in the data set, not just June and December
  - Look at precipitation over the time period for each month
