# Streamline_Logistics_Solutions_Analysis

### Project Overview

Streamline logistics solutions is a logistics company that process, receive and deliver customer orders. Streamline carry out activities such as inventory management, order processing, picking and packing products, and shipping them to customers. Recently, at Streamline logistics, they've been several pressing challenges within order fulfilment process such as mounting order backlogs and customer frustration about delay in deliveries.

### Data Sources

The primary dataset used for this analysis is the "delivery.xlsx" file, containing detailed description of order ID, order timestamp, drivers ID, vehicle info, delivery address, current address of driver, delivery time (mins), delay (mins), customer feedback, route, delivery zone, allocation rules and timestamp for tracking.

### Tools

- Microsoft Excel
 - Data Cleaning and Preparation | Data Analysis | Dashboard

### Data Cleaning and Preparation

In the preparation stage, the following tasks was peformed
1. Data loading, cleaning, exploration and questioning.
2. Irrelevant Columns was removed and relevant ones was added which include:
- Customer delivery city
- Driver efficiency
- Driver status
- Delay status and customer delay status

### Exploratory Data Analysis (EDA)

EDA of streamline logistics solution help us gain insight into drivers that are more utilized than others and also the efficiency of the drivers in relation to their delivery time. The following was observed:
1. Streamline logistics solutions has a total number of 1500 orders to be delivered to customers within 8 days, from September 1st - September 8th.
2. Streamline logistics solutions has 100 drivers with some drivers more utilized than others.
3. Streamline logistics have 5 cities in 3 zones to deliver orders to. 

### Data Analysis

1. There are 767 orders currently in progress while 733 orders has been completed.
2. The average trips for drivers was 16 trips. Drivers with average trip of less than 16 are under utilized.
3. The average delay time for customers to get their orders was 15 minutes. So, customers delayed for more than 15 mins are extremely delayed.
4. Zone 1 has the highest number of orders with 519 orders while zone 3 has the lowest number of orders.
5. The delay status of orders shows 712 orders were delayed even though they are completed. 742 orders are currently in progress and are delayed.
6. The average delivery time to deliver orders to vary across cities. City B has the highest average delivery time of 513.16 minutes while city D has the lowest average delivery time of 149.70 minutes.
7. Driver 34 has the highest number of delay in minute and he is also utilized, having gone on 25 trips in 8 days.
8.  September 3rd has the highest delivery day from September 1st to September 8th.
9.  There are 529 negative feedback, 490 neutral feedbacks and 481 positive feeback from customers.

### Dashboard

There is a streamline logistics solutions dashboard which shows a clear visual representation of the analyzed data.

### Recommendation
1. In order to prevent excess delay minute especially from drivers that are utilized, going on more trips for delivery, e.g. D34 with the highest number of delay minute and utilized for going on 25 trips. Underutilized drivers with high efficiency should be utlized more.
2. Also, as more negative feedbacks came from delay minute due to driver's efficiency and the type of vehicle used to ply rouutes, the following should be done:
   - On route 5, TRUCK B with the highest number of on time delivery in relation to average driver's efficiency should be made to pass through route 5 more.
   - On route 4, VAN A with the highest number of on time delivery in relation to average driver's efficiency should be made to pass through route 4 more.
   - On route 3, VAN A with the highest number of on time delivery in relation to driver's efficiency should be made to pass through route 3 more.
   - On route 2, BIKE C with the highest number of on time delivery in relation to average driver's efficiency should be made to pass through route 2 more.
   - On route 1, TRUCK B with the highest number of on time delivery in relation to average driver's efficiency should be made to pass through route 1 more.
