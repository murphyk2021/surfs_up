# Module 9: Surf's Up with Advanced Data Storage and Retrieval
## An Introduction to SQLite and Flask
---
### Overview
In this module students were introduced to SQLite and Flask.  SQLite is useful because the information we are accessing is stored on a local server and can be used for very diverse applications.  Flask is also helpful as it will allow us to share our analysis with others on a webpage.  To practice with these new tools we are preparing and analyzing weather data sent to us by a potential investor in our dream - a Surf 'n Shake shop on the island of Oahu.   

### Results and Summary
The investor, W. Avy sent us a .sql file which contained data from 9 satellites responsible for retrieving weather data everyday for several years.  Once we extracted the data from the most recent year, 2017, we learned that the precipitaton on the island averaged at 0.178 inches of rain.  However, it was quite variable with some months (December, for example) exceeding 6 inches of rain in one day! 


![summary data for one year](https://github.com/murphyk2021/surfs_up/blob/c645df3138c60d6c541251f96b9049676622a14d/Images/precip_data_year.PNG)

We also learned that on most days Oahu hovers around a comfortables **71.7 degrees Fahrenheight** with the hottest day reaching 85 degrees F and the coldest day dropping to 54.  

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

We can visualize the temerapture distributions in the following graphs.  Although it is safe to say that December is typically cooler than June, there is a fair amount of overlap and it can still get quite warm!

![june and december violin plots of temperature](https://github.com/murphyk2021/surfs_up/blob/c645df3138c60d6c541251f96b9049676622a14d/Images/violin_plot_temps.PNG)

During the month of **June:**
 - the average rain fall was **0.136**
 - the max rain fall recorded was **4.43**

During the month of **December:**
- the average rain fall was **0.22**
- the max rain fall recorded was **6.42!**

![june and december rain data](https://github.com/murphyk2021/surfs_up/blob/c645df3138c60d6c541251f96b9049676622a14d/Images/precip_hist.PNG)

- - -
## Moving Forward
To further influence W. Avy we may add in our report that the Department of business, economic developmet, and tourism reports that June and December mark the beginning of the two highest grossing tourism seasons of the year in Oahu!   [source](https://www.hawaii-guide.com/files/images/charts/oahu-visitor-arrivals.png). 

Before moving forward with our surf shop plan, it may behoove us to take a peak at the predictive climate data for the area based on the current climate change information as well as the affect of la nina and el nino on the hurricane season in Oahu.  We may even be able to see a cyclical pattern in the data we have now as a result of those changes in the wind and sea sruface temperatures!
