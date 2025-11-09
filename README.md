# Pangyo Road Traffic Analysis 🚗📊

This project analyzes road traffic behavior in the **Pangyo Autonomous Driving Zone (South Korea)**  
based on the **IEEE DataPort dataset** simulated using **VISSIM** software.

---

## 📘 Overview
As autonomous vehicles (AVs) transition from concept to reality, they will inevitably share the road with millions of human-driven (conventional) vehicles. This project delves into the complex dynamics of this "mixed-traffic" environment. Using a realistic, high-fidelity traffic simulation dataset from the Pangyo region, this analysis aims to model, analyze, and visualize how these different vehicle types interact and influence overall traffic network performance.

The core goal is to move beyond simple vehicle counts and understand the second-order effects on traffic quality, such as changes in flow, congestion bottlenecks, and network efficiency.

### 🎯 Objectives
The primary objectives of this analysis are:

Analyze Macro-Traffic Patterns

Quantify and analyze key network performance indicators such as traffic density (VEHS(ALL)), arithmetic mean speed (SPEEDAVGARITH(ALL)), and congestion (measured by QUEUEDELAY(ALL)).

Identify and statistically summarize traffic patterns during peak vs. off-peak hours.

Compare Autonomous vs. Conventional Vehicle Performance

Note: This objective depends on the dataset containing a breakdown of AV vs. conventional vehicle data.

Isolate and compare the performance metrics (like average speed and stop-and-go frequency) of autonomous-designated lanes versus conventional lanes, if applicable.

Analyze how different penetration rates of AVs (if varied in the simulation) impact overall network stability.

Visualize Spatiotemporal Traffic Flow Trends

Develop rich time-series visualizations to illustrate how traffic flow changes throughout the day.

Create comparative plots and heatmaps to analyze traffic distribution across different lanes (e.g., _1 vs _2, _3, etc.).

Use feature-engineered data (like hour_of_day, day_of_week) to uncover cyclical or weekly patterns in congestion.  

---

## 🧠 Dataset
- **Source:** [IEEE DataPort – Road Traffic Data](https://ieee-dataport.org/open-access/road-traffic-data)  
- **Authors:** Donghyun Park, Yong-Shin Kang  
- **Size:** ~70 MB (`.csv`)  
- **Software:** VISSIM (Microscopic traffic simulation)  
- **Attributes:** timestamp, vehicle type, position, lane ID, signal phase, speed, etc.

---

## 🧰 Tools & Libraries
| Category | Tools |
|-----------|--------|
| Language | Python 3.10+ |
| Data Analysis | pandas, numpy |
| Visualization | matplotlib, seaborn, folium *(optional)* |
| ML (optional) | scikit-learn, xgboost |
| Environment | Jupyter / VS Code |

---

## ⚙️ Workflow
1. **Data Cleaning:** handle nulls, normalize units, remove outliers  
2. **Exploratory Analysis:** study density, average speed, signal impact  
3. **Visualization:** plot trends and heatmaps of traffic flow  
4. **(Optional)** Build a predictive model for congestion detection  


---

## 📊 Example Insights
- Autonomous vehicles show ~12% higher speed consistency  
- Peak congestion occurs at 8–9 AM and 6–7 PM  
- Signal timing directly influences queue length  

---

## 🧾 License
MIT License © 2025 **Muhammad Azahrul Ramadhan**

---

### ✨ Author
Developed by **Muhammad Azahrul Ramadhan**  
📧 [azahrulsmavo@gmail.com](mailto:azahrulsmavo@gmail.com)  
📍 Yogyakarta, Indonesia  

