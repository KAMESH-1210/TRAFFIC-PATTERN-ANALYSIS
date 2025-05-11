# TRAFFIC-PATTERN-ANALYSIS-NM

🚦 Traffic Patterns Analysis


📌 Introduction

Traffic congestion remains a significant challenge in urban areas, affecting daily life and economic efficiency. This project simulates traffic data and performs analysis to identify vehicle flow patterns across different hours and weekdays. The insights aim to support smarter urban traffic management strategies through visual exploration.


🎯 Objective

Simulate hourly traffic volume over multiple days

Analyze temporal patterns in vehicle count

Visualize traffic trends using informative plots

Identify peak traffic periods to assist planning


📊 Data Source

Simulated Data:
The dataset is synthetically generated using Python libraries. It includes:

60 hours of simulated traffic data

Hourly vehicle counts based on sinusoidal patterns to reflect realistic flow variations

Features include datetime, vehicle_count, hour, and day (weekday)


🛠️ Technologies Used
Python 3.x

Pandas – for data manipulation

NumPy – for traffic data simulation

Matplotlib – for plotting time-series and bar charts

Seaborn – for heatmap visualization


📈 Visualizations

📉 Traffic Volume Over Time (Colored by Hour)

Line and scatter plot showing vehicle count changes

Points colored using a plasma gradient to indicate the hour of day

🗺️ Heatmap of Average Vehicle Count by Day and Hour

Reveals peak and off-peak hours across weekdays

Aggregated using a pivot table and visualized with Seaborn's heatmap

📊 Bar Chart of Average Daily Vehicle Count

Daily traffic trends shown using color-gradient bars

Helps identify which days experience higher/lower traffic volumes


▶️ How to Run

1. Clone the Repository

2. Install Dependencies

3. View the Output

