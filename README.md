
# Hotel Booking Analytics

Explore a rich dataset of hotel bookings from 2015 to 2017, encompassing city and resort establishments. This valuable trove includes detailed booking records, cancellations, guest profiles, and key metrics. Our goal? Extract insights to boost hotel revenue.

Join us on an analytical journey to uncover hidden trends and patterns driving bookings and cancellations. With actionable recommendations, hotels can optimize revenue streams and enhance operational efficiency. Let's unleash the potential of this data to maximize hotel revenue and guest satisfaction!


## Tools Used
Programming Language : Python

Libraries used : Pandas, Numpy, Matplotlib, Seaborn

NoteBook : Google Colab

Dataset

* Total number of rows in data: 119390
* Total number of columns: 32
## Data Cleaning and Feature Engineering

1) Handling null values

Null values in columns company and agent were replaced by 0. 

Null values in column country were replaced by 'others'.

Null values in column children were replaced by the mean of the column.
 
2) Removing Duplicate rows
All duplicate rows were dropped.

3) Converting columns to appropriate data types
Changed data type of children, company, agent to int type.

4) Renaming the columns
The adr column was renamed for better understanding to average_daily_rate

5) Removing outliers
One outlier was found in the average_daily_rate column. Dropping them.

6) Creating new columns
Creating new column Total_stay by adding stays_in_weekend_nights+stays_in_week_nights.
Creating new column Total_members by adding adults+children+babies.
## Key Insights
 
1) In conclusion, the majority of hotel bookings are for city hotels, suggesting that allocating the most targeting funds towards these establishments would be strategically sound.

2) Additionally, it's crucial to note that the peak booking months fall between May and August, coinciding with the summer period. Therefore, focusing marketing efforts and resources during these months can capitalize on heightened demand and maximize returns on investment.

3) City hotels account for approximately 61% of all bookings, while Resort hotels make up the remaining 39%. This distribution indicates that City hotels experience higher booking volumes compared to Resort hotels, making them the busier option among the two.

4) Since the majority of guests originate from Western European countries, it's advisable to allocate a significant portion of our budget towards targeting this region.