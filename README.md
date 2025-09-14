# NYC Taxi Fare Analytics 🚖

## Overview
This project explores New York City's iconic **yellow taxi dataset**, a rich collection of trip records capturing the dynamics of urban mobility.  
The dataset provides insights into pickup/drop-off times, trip distances, fares, passenger counts, and payment methods — offering a detailed lens into city life and transit behavior.

Using this data, we analyze **fare dynamics, passenger trends, and payment patterns**, uncovering meaningful insights about urban transportation.

---

## Dataset Context
The data comes from the **NYC Taxi & Limousine Commission (TLC)**, collected under the TPEP/LPEP initiatives.  
It includes:
- Temporal data (pickup & dropoff times)
- Spatial dimensions (pickup & dropoff locations)
- Quantitative metrics (fare, tips, tolls, distance, passenger counts)

This makes it a valuable resource for **data science, machine learning, and urban planning research**.

### Key Columns
- **VendorID**: Taxi provider ID (1 = CMT, 2 = VeriFone)  
- **tpep_pickup_datetime / tpep_dropoff_datetime**: Trip timestamps  
- **Passenger_count**: Number of passengers  
- **Trip_distance**: Distance traveled (miles)  
- **PULocationID / DOLocationID**: Pickup & dropoff zone IDs  
- **RateCodeID**: Rate applied (Standard, JFK, Newark, etc.)  
- **Payment_type**: Payment method (1 = Credit card, 2 = Cash, etc.)  
- **Fare_amount, Extra, MTA_tax, Tip_amount, Tolls_amount, Total_amount**

📌 [NYC TLC Trip Record Data](https://www.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf)

---

## Requirements
Install dependencies with:
```bash
pip install -r requirements.txt
```

---

## Usage
1. Clone the repo:
   ```bash
   git clone https://github.com/<your-username>/NYC-Taxi-Fare-Analytics.git
   ```
2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook NYC_Taxi_Fare_Analytics.ipynb
   ```
3. Run all cells to explore the analysis.

---

## Results & Insights
- **Trip Patterns**: Clear daily and hourly peaks in taxi demand, with rush hours showing the highest activity.  
- **Fare Dynamics**: Total fare strongly correlates with trip distance, but surcharges and tolls create variance.  
- **Payment Trends**: Majority of trips are paid by **credit card**, followed by cash.  
- **Tips**: Higher tip amounts are often associated with longer trips or credit card payments.  
- **Passenger Count**: Most trips carry **1–2 passengers**, highlighting the individual nature of taxi use.  
- **Modeling**: Machine learning models (e.g., regression) can reasonably predict fare amounts using trip distance, passenger count, and temporal data.

These insights can help in **urban planning, optimizing taxi services, and understanding commuter behavior**.

---

## Acknowledgements
- Dataset provided by **NYC Taxi & Limousine Commission (TLC)**.  
- Data source: [TLC Trip Record Data](https://www.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf).  
