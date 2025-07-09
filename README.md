# SUMMER ANALYTICS CAPSTONE PROJECT - Dynamic pricing for Urban Parking Lots
Urban parking is often mispriced — static pricing leads to overcrowding in some lots and underuse in others. This project simulates a **real-time intelligent pricing engine** for 14 parking spaces using data-driven models and real-time stream processing.
In this project I have created an intelligent, data-driven pricing engine for 14 parking spaces using real-time data streams, basic economic theory, and ML models built from scratch, using only numpy, pandas libraries.
I have used data collected from 14 urban parking spaces over 73 days, sampled at 18 time points per day with 30 minutes of time difference (from 8:00 AM to 4:30 PM the same day).
The price is realistically updated in real-time based on: Historical occupancy patterns, queue length, nearby traffic, special events, vehicle type.
All models are implemented from scratch using only:
- Python
- NumPy
- Pandas
- Pathway (for real-time stream processing)

Technologies used are-

 **Language** : Python 

 **Data Manipulation** : Pandas, NumPy 
 
 **Stream Processing** : [Pathway](https://pathway.com/) 
 
 **Visualization** : Bokeh 
 
 **Environment** : Google Colab 

 The dataset used (dataset.csv) contains:
 
SystemCodeNumber, Capacity, Occupancy, VehicleType, TrafficConditionNearby, QueueLength, IsSpecialDay, etc

**Setup instructions**

git clone <https://github.com/seher19/SA_capstoneproject>

cd your-repo

pip install pathway bokeh panel pandas matplotlib

**Key features**

- Aggregates and analyzes traffic data by day and vehicle type.

- Applies windowed computations with Pathway.

- Produces real-time dashboard visualizations.

- Supports dynamic pricing or allocation simulations.


