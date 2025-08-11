# 🏨 Hotel Data Analysis

## 📌 Objective

The goal of this project is to analyze hotel booking data to uncover patterns, trends, and insights related to bookings, capacity, revenue, and customer behavior. The analysis leverages multiple related datasets to perform exploratory data analysis, data cleaning, and statistical summarization.

---

## 📊 Dataset

This project uses **5 CSV files**:

1. `dim_date.csv` – Date reference table.
2. `dim_hotels.csv` – Hotel details including property IDs and locations.
3. `dim_rooms.csv` – Room types and related attributes.
4. `fact_aggregated_bookings.csv` – Aggregated booking information.
5. `fact_bookings.csv` – Detailed booking records.

---

## 🛠 Methods Used

- **Data Exploration**
  - Identifying unique property IDs
  - Calculating total bookings per property
  - Finding days where bookings exceeded capacity
  - Determining highest capacity properties
- **Data Cleaning**
  - Removing invalid guest counts (negative values)
  - Checking for revenue outliers
  - Handling missing ratings (decision not to drop or impute due to volume)
  - Filling null values in aggregated bookings appropriately
- **Trend Analysis**
  - Revenue trends by property and room type
  - Booking trends over time
  - Capacity utilization patterns

---

## 📈 Key Insights

- Certain properties experience booking days exceeding their capacity.
- Presidential suite (RT4) bookings have distinct revenue characteristics due to their luxury status.
- A significant portion of ratings data is missing, influencing decision-making in cleaning.
- Seasonal and property-specific booking patterns can guide capacity planning.

---

## 📂 Project Structure

```
hotel_analysis/
├── data/                  # CSV datasets
├── hotel_analysis.ipynb   # Jupyter Notebook with full analysis
└── README.md              # Project documentation
```


