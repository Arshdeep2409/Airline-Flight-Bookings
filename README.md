✈️ Airline Bookings Dashboard
This Power BI dashboard presents an analytical overview of international airline booking patterns, based on actual booking data. The dashboard was created to derive business insights that can support airline strategy, marketing, and customer experience optimization.

<br>

📌 Objective
To analyze flight booking trends across countries and routes, identify customer behavior such as booking confirmation rate, preferred travel days, time slots, trip types, and extra baggage demand — using Power BI and PostgreSQL.

🧰 Tools & Technologies
Microsoft Power BI: For data visualization and dashboard development

PostgreSQL: For data querying, filtering, and generating insights

MS Excel: For data cleaning and initial formatting

DAX (Data Analysis Expressions): For calculated measures in Power BI

📊 Key Visuals on Dashboard
KPIs:

Total Passengers

Average Advance Booking Days

Average Length of Stay

Charts & Visuals:

Pie Chart: Confirmed vs Not Confirmed Booking Percentage

Bar Chart: Length of Stay by Route

Bar Chart: Countries Wanting Extra Baggage

Filters: Route, Booking Country, Mode of Booking

🔍 Data Insights (Power BI + SQL Findings)
✅ Insights Derived During SQL Querying and Dashboard Development:
Malaysia is the country with the highest number of bookings (2434) and also has the highest number of confirmed tickets.

A maximum of 9 passengers were booked under a single PNR.

Top 5 routes where 9 passengers were booked under one PNR:

CTU – PER

AKL – KUL

KCH – PEK

Top 3 countries by number of bookings:

🇲🇾 Malaysia – 2434

🇦🇺 Australia – 895

🇨🇳 China – 684

Top 5 most popular routes:

AKL – KUL: 2620 bookings

PEN – TPE: 912 bookings

MEL – SGN: 833 bookings

ICN – SIN: 793 bookings

DMK – KIX: 729 bookings

Out of 49,281 total bookings, only 14% were confirmed, meaning 6,899 bookings were completed. The rest were either abandoned or failed due to factors like plan changes or internet issues.

Monday is the most preferred day for flight bookings, especially around 1 PM in the afternoon.

Trip Type Distribution:

Roundtrip: 99.66%

One-way: 0.27%

Circle Trip: 0.06%

📈 Business Use Cases
Identify routes and countries with high passenger volumes to target for marketing campaigns.

Analyze low booking confirmation rates and reduce abandonment by optimizing checkout flows.

Plan promotions around top booking days/times.

Understand which countries tend to request more extra baggage.

📂 Project Structure
bash
Copy
Edit
📁 AirlineBookingsDashboard
├── Airline Bookings Dashboard.pbix         # Power BI project file
├── Airline Bookings Dashboard(1).png       # Final Dashboard Screenshot
├── README.md                               # Project documentation (this file)
└── SQL Queries                             # PostgreSQL scripts used for analysis (optional folder)
🔗 Connect With Me
Name: Arshdeep Singh

LinkedIn: https://www.linkedin.com/in/arshdeep-singh-900540b0-data-analyst/

Tools: Power BI | PostgreSQL | MS Excel

📌 Note
This dashboard was created using a sample dataset and is intended for educational and portfolio purposes.

