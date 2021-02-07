# Surfs_up

## Overview of the statistical anlysis: 
  
A potential investor in our new venture was looking for additional information about temperature trends before backing the opening a surf shop. Specifically, the investor wants temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round.


  ## Resources
  - Data Sources:  schools_complete.csv, students_complete.csv, clean_students.csv
  - Software:  Anaconda 4.9.2, Jupyter Notebook 6.0.3 , Python 3.7.6, SQLalchemy
  - Using:  Pandas, NumPy, SQLalchemy extensions and functions


## Results: 

### Key differences in weather between June and December:

- The average (mean) temperature is 74 degrees in the month of June and 71 degrees in the month of December (rounded to the nearest whole number)
- The standard deviations is 3.26 in June and 3.75 in December meaning the temperature varies a bit more in december (rounded to the nearest hundredth)
- The minimum temperature was 64 degrees for June, while December had a minimum of 56 degrees. 
- Both months had similar maximum temperatures.  The max for June was 85 degrees and the max for December was 83 degrees.
- The difference in teperature distribution across percentiles/ quartiles was similar for both months.

- ** Note there are fewer temperature readings for December than there are for June (1700 / 1517 for June/ December respectively)
 
![June_Summary_Stats](https://github.com/PatriciaCB1/School_District_Analysis/blob/main/Original_District_Summary1.png)


![December_Summary_Stats](https://github.com/PatriciaCB1/School_District_Analysis/blob/main/Revised_District%20Summary.png)


##Summary:

###High-level Summary 
Based on the temperature analysis alone for June and December, it appears that while it is somewhat cooler in December, the location is viable for surfing and ice cream at these times of year.  Both months have average temperatures in the 70s 

In order to fully assess suitability of the location, I would recommend we run the following to enhance our climate analysis:
- run analysis for all months (not just June/ December) as other months may show more variability
- analyze by year to see if there are any years that are outliers with extreme differences
- run analysis other factors such as precipitation for the same months
- plot our analysis for easier comparison using Matplotlib
- due to global warming perhaps trend the temp and precipitation - run predictive analytics to understand what future weather patterns/ features might emerge
