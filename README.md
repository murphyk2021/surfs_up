# Module 9
## Surf's Up
---
### Overview
In this module students were introduced to SQLite and Flask.  SQLite and SQLAlchemy is useful because the information is stored on a local server and can be used for very diverse applications.  Flask is also helpful as it will allow us to share our analysis with others on a webpage.  To practice with these new tools we are preparing and analyzing some weather data sent to us by a potential investor in our dream - a Surf 'n Shake shop on the island of Oahu.   

### Results and Summary
The investor, W. Avy set us a .sql file which contained data from 9 satellites which retrieved weather data everyday for several years.  We first assessed the data from the most recent year, 2017.  Once we extracted the data from the most recent year, 2017, we learned that the precipitaton on the island averaged at 0.178 inches of rain.  However, it was quite variable with some months (december, for example) exceeding 6 inches of rain in one day! 


![summary data for one year](https://github.com/murphyk2021/surfs_up/blob/c645df3138c60d6c541251f96b9049676622a14d/Images/precip_data_year.PNG)

We also learned that on most days Oahu is around 71.7 degrees Fahrenheight with the hottest day reaching 85 degrees F and the coldest day dropping to 54.  

![temperature data for one year](https://github.com/murphyk2021/surfs_up/blob/c645df3138c60d6c541251f96b9049676622a14d/Images/temp_data_year.PNG)
![temperature histogram for one year](https://github.com/murphyk2021/surfs_up/blob/c645df3138c60d6c541251f96b9049676622a14d/Images/temp_hist_year.PNG)

To help ease W. Avy's mind that Oahu will be a safe investment all year round we extracted the data for the months of June and December.

During the month of **June:**
 - the average temperature in Oahu is **74.9**
 - the highest recorded temperature was **85**
 - the lowest recorded temperature was **64**

During the month of **December:**
- the average temperature in Oahu is **71**
- the highest recorded temperature was **83**
- the lowest recorded temperature was **56**

![june and december summary data](https://github.com/murphyk2021/surfs_up/blob/c645df3138c60d6c541251f96b9049676622a14d/Images/june_dec_data.PNG)
![june and december violin plots of temperature](https://github.com/murphyk2021/surfs_up/blob/c645df3138c60d6c541251f96b9049676622a14d/Images/violin_plot_temps.PNG)

During the month of **June:**
 - the average rain fall was **0.136**
 - the max rain fall recorded was **4.43**

During the month of **December:**
- the average rain fall was **0.22**
- the max rain fall recorded was **6.42!**

![june and december rain data](https://github.com/murphyk2021/surfs_up/blob/c645df3138c60d6c541251f96b9049676622a14d/Images/precip_hist.PNG)
- 
To further influence W. Avy we may add in our report that the Department of business, economic developmet, and tourism whose data shows that June and December mark the beginning of the two highest grossing tourism seasons of the year in Oahu!   [source](https://www.hawaii-guide.com/files/images/charts/oahu-visitor-arrivals.png). Before moving forward with our surf shop plans we may want to look into the data to determine when hurrican season is and which areas are affected the most.  Additionally, we should look into la nina/el nino data so that we can plan to open in the most profitable time!  
