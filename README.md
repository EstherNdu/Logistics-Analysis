# Logistics-Analysis

Transportation and logistics play a critical role in ensuring the seamless movement of goods across regions. This project presents an analysis of delivery performance with a focus on key logistics metrics such as On-Time Delivery Rate, Delayed Delivery Rate, Estimated Time of Arrival (ETA) Accuracy, and Average Trip Duration.

The report highlights patterns in delivery delays by route, efficiency by time of day, and geographic distribution of deliveries across states. By evaluating these indicators, the analysis provides actionable insights into operational strengths and areas for improvement, ultimately supporting better decision-making for efficiency, reliability, and customer satisfaction within the logistics network.

# About the Dataset
The dataset had over 3000 records and One table - Fact Table,  which came in CSV format. Data transformation and analysis was done using Power Query and Power BI.

# Problem Question

* Customer & Supplier Performance Report
Create a report that analyzes customer shipment volumes and supplier performance, highlighting top customers, suppliers with the highest delays, and overall delivery distribution across states.

* Predictive Logistics Report
Build a predictive analysis report that forecasts delivery demand and evaluates whether delay rates are expected to decline over time, helping the business anticipate operational challenges.

# Tool
  Power BI

# Processes 
* Imported CSV files into Power BI
* Transformed the data using Power Query
* Loaded the data into Power BI for Analysis & Reporting
* Created a Forcast Table 
* Modeled the data
* Used DAX to perform indepth analysis
* Calculated the following using DAX: Abg Delivery Time, Total Delays, Total Suppliers, ETA Accuracy, On-time Delivery Rate
* Created the report wireframe using Figma
* Created interactive reports

  # Data Modeling

  <img width="1670" height="641" alt="Screenshot 2025-09-14 184658" src="https://github.com/user-attachments/assets/43ab1b94-2d83-4387-add1-63b4c81c8fea" />

  # Key Insights

  <img width="1043" height="113" alt="Screenshot 2025-09-14 185544" src="https://github.com/user-attachments/assets/d0bd27e4-1d1f-490d-89eb-f04ba6215f93" />

  * On-time Delivery Rate - 38.52%
  * Delay Delivery Rate - 61.48%
  * Total Delays - 2203
  * ETA Accuracy - 41.81%
  * Average Trip Duration - 5 days


<img width="1055" height="103" alt="Screenshot 2025-09-14 190611" src="https://github.com/user-attachments/assets/5a96d07e-e0b8-4f39-9683-c40a50f2c010" />


* Total Customers - 36
* Total Suppliers - 193
* Avg Delivery Time - 113 hrs


<img width="1045" height="273" alt="Screenshot 2025-09-14 191412" src="https://github.com/user-attachments/assets/96daa12c-69e6-4abe-90cf-af87841ee21f" />

* Khorajnanoda, Ahmedabad → Singaperumalkoil, Kanchipuram route had the highest number of delays (92) followed by Jamalpur, Gurgaon → Singaperumalkoil, Kanchipuram (87)
* September and October were the months with the most accurate Expected Time of Arrival. This might be because these months had the lowest number of bookings (O and 3 respectively)



<img width="1045" height="273" alt="Screenshot 2025-09-14 191412" src="https://github.com/user-attachments/assets/59fd843e-3e98-433e-989d-e0777ea95a68" />


* Delivery efficiency by time of day reveals that the highest number of deliveries occur between 12 AM – 2:59 AM (245 deliveries) and 3 AM – 5:59 AM (176 deliveries), yet these periods record relatively lower on-time delivery rates.  This implies that; High delivery volumes at night (12 AM – 6 AM) are linked with lower on-time rates, while smaller daytime volumes (6 AM – 2 PM) achieve better delivery reliability.
*  States like Tamil Nadu, Maharashtra, and Gujarat dominate the delivery network  -  a key signal for focused resource allocation and capacity planning.



<img width="1056" height="280" alt="Screenshot 2025-09-14 201242" src="https://github.com/user-attachments/assets/31f906be-c1bc-4f6a-b161-ab4b74614d86" />

* Larsen and Toubro Limited had 975 shipments dellivered followed by Ford India Private Limited- 631 shipments.
* Ekta Transport had 238 shipments and 186 delays followd by Unknown which had 217 shipments and 192 delays and Cargo India which had 198 shipments and 172 delays.


<img width="1067" height="297" alt="Screenshot 2025-09-14 202647" src="https://github.com/user-attachments/assets/d86205ca-a87f-4e97-bc7e-8696885f870d" />

* On a positive note, forecast models suggest improved delivery timelines and increase in  booking volumes in the coming months.


# Reports

<img width="1264" height="783" alt="Screenshot 2025-09-14 202901" src="https://github.com/user-attachments/assets/d7240296-b72f-4eb3-8397-c252607f7eac" />


<img width="1259" height="783" alt="Screenshot 2025-09-14 203005" src="https://github.com/user-attachments/assets/a4ed8a90-0979-4e69-8c69-bb444ce9fdcc" />


# Recommendations

* Optimize High-Delay Routes: Investigate and address bottlenecks on routes such as Ahmedabad → Kanchipuram and Gurgaon → Kanchipuram to reduce delays.
* Balance Delivery Scheduling: Redistribute nighttime deliveries (12 AM – 6 AM) into daytime slots to improve punctuality and reliability.
* Strengthen Capacity in Key States: Focus resources and logistics investments in Tamil Nadu, Maharashtra, and Gujarat where delivery volumes are highest.
* Improve Supplier Performance: Review underperforming suppliers like Ekta Transport and enforce KPIs or consider switching to more reliable partners.
* Leverage Predictive Insights: Prepare for rising bookings and improved timelines by scaling fleet capacity, optimizing staffing, and enhancing tracking systems.

View the interactive report here: https://tinyurl.com/TransportationAnalysis
