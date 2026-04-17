# Hospitality-PowerBI-Dashboard
Power BI project analyzing hotel revenue, occupancy, and booking trends
📊 Hospitality Analytics Dashboard (Power BI)
👩💻 Author
Priyanka Arumugam
🔗 LinkedIn: Connect with me on LinkedIn
________________________________________
🧾 Project Overview
This project focuses on analyzing hotel performance using a hospitality dataset. The dashboard provides insights into key business metrics such as occupancy, revenue, booking trends, and customer behavior.
The goal of this project is to help stakeholders make data-driven decisions to improve hotel performance and revenue.
________________________________________
📁 Dataset Description
The dataset consists of 5 CSV files:
🔹 Dimension Tables
•	dim_date → Date-related information (week, month, day type) 
•	dim_hotels → Hotel details (property, category, city) 
•	dim_rooms → Room types and classifications 
🔹 Fact Tables
•	fact_bookings → Detailed booking-level data 
•	fact_aggregated_bookings → Aggregated room-level booking and capacity data 
________________________________________
🧠 Data Model
A star schema model is used:
•	Fact tables connected to dimension tables via: 
o	property_id 
o	room_category 
o	date 
This enables efficient filtering and analysis across different dimensions like city, room class, and time.
________________________________________
📊 Key KPIs
The dashboard includes the following important hospitality metrics:
•	Occupancy % → Room utilization rate 
•	ADR (Average Daily Rate) → Revenue per booking 
•	RevPAR (Revenue Per Available Room) 
•	Total Revenue 
•	Cancellation Rate 
•	Average Customer Rating 
________________________________________
📅 Analysis Performed
•	📈 Weekly performance analysis (Week-over-Week trends) 
•	🏨 Hotel-wise revenue and occupancy comparison 
•	🛏 Room class performance analysis 
•	🌐 Booking platform insights 
•	❌ Cancellation and no-show behavior analysis 
•	⭐ Customer rating trends 
________________________________________
📌 Key Insights
•	Luxury hotels generate higher revenue but may have lower occupancy rates 
•	Weekends show higher pricing (ADR) compared to weekdays 
•	Online booking platforms contribute significantly to total bookings 
•	Cancellation rates impact actual revenue realization 
________________________________________
🛠 Tools & Technologies
•	Power BI → Data visualization 
•	DAX → Calculations & KPIs 
•	Excel / CSV → Data source 
•	Data Modeling → Star schema design 
________________________________________
📂 Project Structure
Hospitality-PowerBI-Dashboard
│── Hospitality_Analytics_Dashboard.pbix
│── dataset/
│   ├── dim_date.csv
│   ├── dim_hotels.csv
│   ├── dim_rooms.csv
│   ├── fact_bookings.csv
│   ├── fact_aggregated_bookings.csv
│── screenshots/
│── README.md 
________________________________________
💼 Business Use Case
This dashboard can be used by:
•	Hotel management teams 
•	Revenue managers 
•	Business analysts 
To:
•	Track performance 
•	Optimize pricing strategy 
•	Improve occupancy and revenue 
______________________________________
