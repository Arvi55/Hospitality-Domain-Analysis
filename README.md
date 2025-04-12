#  Project Background

AtliQ Grands is a well-established chain of five-star hotels operating across major cities in India, with over 20 years of presence in the hospitality industry. However, in recent years, the brand has been facing a decline in both market share and revenue, particularly in the luxury and business hotel segments. This drop is primarily attributed to increased competition, evolving customer preferences, and ineffective decision-making at the management level.

The goal of this project is to analyze operational and performance data to identify key areas of improvement. Through data-driven insights, we aim to help AtliQ Grands optimize revenue, improve occupancy, and strengthen its competitive position in the market.




#  Data Structure & Initial Checks
The AtliQ Grands database consists of five tables:

- dim_date
- dim_hotels
- dim_rooms
- fact_aggregated_bookings
- fact_bookings

Together, these tables contain a total of **134,590** records.

Below is the Entity Relationship Diagram (ERD) that illustrates how these tables are interconnected:

![App Screenshot](https://github.com/Arvi55/Hospitality-Domain-Analysis/blob/main/ERD%20diagram.png?raw=true)


# Executive Summary


**Overview of Findings**

Despite operating in prime locations, AtliQ Grands is experiencing a stagnation in revenue growth. Weekly revenue remains stuck between ₹79M–₹96M on weekdays and ₹36M–₹43M on weekends, showing limited upward movement.

Moreover, occupancy rates have consistently stayed below 70%, with the past two weeks dropping sharply to just 51%, indicating a demand gap or operational issue.

Lastly, the Average Daily Rate (ADR) has plateaued in the ₹12K range, reflecting little pricing optimization or value addition.

The next section will explore deeper KPIs and uncover strategic opportunities to boost performance.


Below is the overview page from the PowerBI dashboard.

![App Screenshot](https://github.com/Arvi55/Hospitality-Domain-Analysis/blob/main/dashboard_overview.png?raw=true)



**Revenue Trends:**
   - During weekdays, the highest revenue generated was ₹97 million in the june (5th week), while the lowest was ₹79 million, observed in multiple weeks, including the last two week of july. This indicates steady performance with minimal fluctuations during weekdays.

-  For weekends, the revenue peaked at ₹44 million in the june (2nd week) , with the lowest point recorded at ₹35 million in the june (4th week), suggesting that weekends bring in slightly lower revenue compared to weekdays.

- In all three months, Mumbai emerged as the leading city by revenue, contributing ₹660 million out of a total of ₹1.69 billion, which accounts for 39% of the overall revenue. Bangalore followed with ₹415 million in revenue

   ![App Screenshot](https://github.com/Arvi55/Hospitality-Domain-Analysis/blob/main/Revenue%20Trends.png?raw=true)


 **Occupancy Trend**

- The average occupancy rate across all properties stands at 57.8%, which is relatively low compared to industry standards and other hotel chains. This highlights an opportunity to optimize booking and marketing strategies.

- Interestingly, Delhi recorded the highest occupancy rate at 60.4%, yet it contributed the lowest revenue among major regions, with only ₹290.9 million. This suggests that while rooms are being filled, the revenue per booking may be lower due to pricing or room type distribution.

- Weekends show a significantly higher occupancy rate of 62.6%, compared to 55.8% on weekdays, indicating that holidays and weekends are busier periods for bookings, possibly driven by leisure travel.

   ![App Screenshot](https://github.com/Arvi55/Hospitality-Domain-Analysis/blob/main/occupancy.png?raw=true)


 **ADR & RevPAR Analysis**

- The Average Daily Rate (ADR) is around ₹16,000, while Revenue per Available Room (RevPAR) is ₹10,500. The significant gap between these two metrics indicates that occupancy is not optimal, pulling down potential revenue.

- While ADR remains mostly stable across the months, RevPAR shows high variation. This inconsistency highlights that room rates aren’t the issue—occupancy fluctuations are driving changes in revenue efficiency.

- Formula to Understand the Relationship:

  *RevPAR = ADR× occupancy Rate*

This means that even with a high ADR, a low occupancy rate can significantly lower the RevPAR. Improving occupancy while maintaining ADR is key to boosting revenue efficiency.

![Alt1](https://github.com/Arvi55/Hospitality-Domain-Analysis/blob/main/RevPar%20&%20ADR.png?raw=true) 

 
**Room Types Analysis**

- Elite Rooms generate the highest revenue among all room types, followed by Premium Rooms, making them the top-performing categories.

- While the ADR (Average Daily Rate) for Elite Rooms is ₹12K+, and for Standard Rooms it’s ₹8K+, the difference in DSRN (Daily Sellable Room Nights) is surprisingly small — only about 200 rooms.

- This indicates that Elite Rooms, despite higher pricing, are nearly as in-demand as Standard Rooms. Therefore, increasing the share of Elite Rooms can significantly boost overall revenue with minimal impact on occupancy.

- Additionally, the realisation rate is 70%, meaning only 70% of the expected revenue is being captured per room. Improving room mix and reducing unnecessary discounts—especially for high-end rooms—can help maximize revenue realisation.

 ![Alt1](https://github.com/Arvi55/Hospitality-Domain-Analysis/blob/main/Room%20types.png?raw=true) 

 

**Average Rating & Cancellation Insights**

- The average rating of Atliq Grand is 3.7, which is lower than most of its competitors. A higher rating is often linked to greater customer trust, repeat bookings, and improved revenue potential.

- 7 out of the top 10 hotel chains by revenue boast ratings of 4+, emphasizing that higher ratings directly correlate with higher revenue. Investing in improving guest experiences could lead to significant revenue growth.

- The average cancellation percentage is 24.5%, which is too high. High cancellations not only impact occupancy rates but also reduce revenue predictability and create inefficiencies in room allocation.

![Alt1](https://github.com/Arvi55/Hospitality-Domain-Analysis/blob/main/rating%20&%20cancellation.png?raw=true) 

# Recommendations

 
- **Improve Customer Ratings:-**
Atliq Grand’s average rating of 3.7 is relatively low. Enhancing guest experience through better service, improved room quality, and added amenities can help increase ratings to 4+, which directly correlates with higher bookings and revenue.

- **Maximize Revenue from Elite Rooms:-**
Elite Rooms have a higher ADR compared to Standard Rooms. Increasing the availability of these higher-priced rooms during peak times or offering exclusive packages can drive more revenue, especially given their higher profit margins.

- **Reduce Cancellation Rates:-**
With a 24.5% cancellation rate, Atliq Grand can improve revenue stability by introducing stricter cancellation policies and offering non-refundable booking options or incentives for guests to commit to their bookings.

- **Capitalize on Weekends:-**
Weekends have a higher occupancy rate (62.6%) compared to weekdays (55.8%). Implementing weekend-specific promotions or deals could further boost bookings during these busy periods and increase overall revenue.

- **Focus on High-Rev Cities:-**
Mumbai, contributing 39% of the total revenue, is a key market. Strengthening marketing efforts in high-performing cities like Mumbai and Bangalore with targeted offers or partnerships can help drive more bookings and expand market share in these regions.

 - **Implement Data-Driven Pricing Strategies:-**
A more data-driven approach to pricing and forecasting can help optimize room rates and availability. Using historical data, competitor analysis, and demand forecasting can help Atliq Grand maximize revenue during both high and low-demand periods.







