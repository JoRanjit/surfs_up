# June and December Climate Analysis

### This project analyses the temperature data for the months of June and December in Oahu, Hawaii.
### This will help the customer to determine if his business idea is sustainable year-round.

#### For this analysis, we used python and Sqlite database - "Hawaii.sqlite" with weather data stored in 2 tables:
    * measurement
    * stations
    
##### The analysis is performed using the Python SQL toolkit and ORM mapper : SQLalchemy.

 Step #1 June temperature Data collection:
            
   * Created a list of temperatures recorded in June from the 'Measurement' table
      ![June Temp List]( https://github.com/JoRanjit/surfs_up/blob/main/images/June_temp_list.PNG)
        
   * Created a dataframe of June temperatures from the above list
   
      ![June Temp DataFrame]( https://github.com/JoRanjit/surfs_up/blob/main/images/June_temp_dataframe.PNG )
        
   * Generated the summary  statistics of June temperatures using describe() method.
   
      ![June temp statistics]( https://github.com/JoRanjit/surfs_up/blob/main/images/June_temp_summary_stats.PNG) 
        
 Step #2: December temperature Data collection:        
    
   * Created a list of temperatures recorded in December from the 'Measurement' table

       ![December Temp List]( https://github.com/JoRanjit/surfs_up/blob/main/images/Dec_temp_list.PNG)
        
   * Created a dataframe of December temperatures from the above list
   
        ![December Temp DataFrame]( https://github.com/JoRanjit/surfs_up/blob/main/images/December_temp_dataframe.PNG)
        
   * Generated the summary  statistics of December temperatures using describe() method.
   
       ![December temp statistics]( https://github.com/JoRanjit/surfs_up/blob/main/images/Dec_temp_summary_stats.PNG)
        
##### Findings:   
    
   *  Average temperature remains a very pleasant 71 thru' 74 degrees around the year. 
      ---  This is an ideal weather - not too hot or not too cold. With some marketing and advertising campaigns - ICE cream sales should see some good business. 
   *  But max temperatures could go upto 85 degrees in June and 83 degrees in December. 
      ---   This means ICE cream sales are going to spike in summer due to these hot temperatures. The ideal weather for an ICE Cream shop.
   *  Slight disadvantage on the dataset is that June dataset has about 1700 recordings, while December is only about 1500.
      ---   This means that the December data may not be as accurate as June data, but still good enough to get a good analysis.
    
##### Improvements:  

   *  The analysis should also include the rain-fall/precipitation information which would help the customer make more informed decisions as the 
      Ice cream sales might be lower during rainy season.
   *  Analysis spans 6-7 years of data starting from 2010. This dataset could be narrowed down to pull more recent year's data, which will be more accurate than this wide date- range.
   *  Use histograms to view the trend of the  temperature and precipitation over the time period. With a good understanding of the temperature and rainfall patterns over the years - customer could predict the Ice cream sales trend accordingly.
