# 🏨 Enhancing Hotel Performance with Data-Driven Insights  
🔓 Unlocking Key Trends Using Power BI

---

## 📋 Project Description

In the highly competitive hospitality industry, data plays a pivotal role in optimizing performance, minimizing cancellations, and maximizing guest satisfaction. This project uses **Power BI** to uncover hidden trends from a comprehensive hotel booking dataset.

By analyzing over 119K records from both city and resort hotels, the project identifies key patterns in guest behavior, revenue generation, room preferences, and booking channels. The interactive dashboard empowers hotel managers and analysts to make smart, informed decisions through dynamic visuals and filters.

---

## 💾 Project Files Description

- `Hotel_Performance.pbix`: Power BI file containing the complete interactive dashboard  
- `dashboard_screenshot.png`: Preview image of the dashboard  
- `README.md`: Detailed project documentation outlining objective, steps, and insights  
- *(Optional: Pre-cleaned Excel file used for import into Power BI)*

---

## 🧾 Dataset Contents

The dataset contains real-world hotel booking data from two hotel types — **City Hotel** and **Resort Hotel** — covering a wide range of attributes including guest details, booking channels, duration of stay, cancellations, and average daily rates.

- **Records**: 119,390  
- **Columns**: 32  
- **Time Span**: 2015 to 2017

---

## 📊 Key Variables

### 🏨 hotel_bookings.csv

| Column | Description |
|--------|-------------|
| `hotel` | Type of hotel: City or Resort |
| `is_canceled` | 1 = Canceled, 0 = Not canceled |
| `lead_time` | Days between booking and arrival |
| `arrival_date_year/month/day` | Date of arrival |
| `stays_in_weekend_nights` | Nights stayed on weekends |
| `stays_in_week_nights` | Nights stayed on weekdays |
| `adults`, `children`, `babies` | Number of guests |
| `meal` | Meal type (BB, HB, FB, SC) |
| `country` | Country of origin |
| `market_segment`, `distribution_channel` | Booking source and channel |
| `is_repeated_guest` | 1 = Returning guest |
| `reserved_room_type`, `assigned_room_type` | Room codes booked vs. assigned |
| `deposit_type` | No Deposit, Refundable, Non Refund |
| `customer_type` | Transient, Contract, Group, etc. |
| `adr` | Average Daily Rate (revenue per occupied room) |
| `total_of_special_requests` | Number of special guest requests |
| `reservation_status` | Canceled, Check-Out, or No-Show |

---

## ❓ Problem Statement

With high booking volumes and varying guest behaviors, hotel chains face critical questions:

- What causes high cancellation rates and how can they be reduced?
- Which room types and customer segments generate the most revenue?
- What are the key seasonal trends in bookings?
- How effective are distribution channels in driving business?

This project aims to answer these questions and provide clear, visual guidance for optimizing hotel operations.

---

## 🛠 Technologies Used

- **Tool**: Microsoft Power BI  
- **Support Tools**: Excel (for initial data wrangling)

---

## 🔍 Data Cleaning Summary

| Action | Column(s) Affected | Reason |
|--------|--------------------|--------|
| Removed columns | `company`, `agent` | Excessive missing values |
| Imputed missing values | Numeric = median; Categorical = mode | Maintain data integrity |
| Handled duplicates | 31,994 duplicate rows retained | Consistent with real-world volume |
| Created new features | Total Revenue, Cancellation Rate | To support key KPIs in dashboard |

---

## 🔍 Steps Involved

### 1. Data Preparation
- Cleaned and imputed missing values
- Removed irrelevant or sparse columns
- Created derived columns like revenue and booking counts

### 2. Exploratory Data Analysis
- Analyzed booking behaviors by hotel type, season, and channel
- Assessed cancellation impact and ADR trends

### 3. Dashboard Design
- Built an interactive dashboard using slicers and visual KPIs
- Incorporated filters for hotel type, year, and cancellation status
- Added charts to reveal trends, outliers, and key contributors

---

## 📊 Power BI Dashboard Features

### 💡 Visual Elements:
- **KPI Cards**: Total Bookings, Total Revenue, Cancellation Rate  
- **Bar Charts**: Room Type Demand, Top Booking Countries  
- **Column Charts**: Monthly Trends, Distribution Channels  
- **Donut & Pie Charts**: Customer Type Share, Meal Plan Distribution  
- **Line Charts**: Revenue and Booking Trends Over Time  

### 🧭 Interactive Slicers:
- Hotel Type  
- Year  
- Cancellation Status  
- Distribution Channel  
- Customer Type  

---

## 📌 Key Insights from Dashboard

- **📅 Peak Month**: August had the highest number of bookings (~13.9K)  
- **🧳 Total Bookings**: 119,390  
- **💰 Total Revenue**: $42.72 Million  
- **⚠️ Cancellation Rate**: 37% — a significant loss driver  
- **🌍 Top Booking Countries**: Portugal, UK, France, Spain, Germany  
- **🏨 Most Popular Room**: Room Type A (booked ~74K times)  
- **📦 Top Booking Channel**: Travel Agents / Tour Operators (TA/TO) — ~97.87K bookings

---

## 🧭 Dashboard Interactivity

The dashboard allows stakeholders to:

- Compare revenue performance across hotel types  
- Examine cancellation patterns by country, channel, or season  
- Filter data to explore guest preferences by market segment  
- Track operational trends in real time using slicers and timelines

---

## 🎯 Conclusion

This Power BI dashboard transforms raw booking data into strategic insights, enabling hoteliers to:

- Optimize marketing and pricing strategies  
- Reduce cancellation impact through flexible policies  
- Personalize offerings based on guest behavior  
- Make confident, data-informed decisions

> 📈 A smart hotel business begins with smart data visibility.

---

## 🔮 Future Scope

- Integrate real-time booking and cancellation feeds  
- Add review sentiment and customer satisfaction scores  
- Deploy the dashboard using Power BI service for broader access  
- Incorporate forecasting for demand and revenue management

