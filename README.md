# 🚲 Ford GoBike System Data Visualization

## 📝 Description
This project explores and visualizes data from the Ford GoBike bike-sharing system in the San Francisco Bay Area. The dataset contains information about individual rides, including trip duration, user type, station locations, and rider demographics. The goal was to uncover usage patterns across time, gender, and rider types using Python and data visualization tools.

## 📁 Dataset
- **Source**: [Ford GoBike Trip Data – February 2019](https://www.fordgobike.com/system-data)
- **Size**: 183,412 rows × 16 columns
- **Key Features**:  
  - `start_time`, `end_time`, `duration_sec`  
  - `start_station_name`, `end_station_name`  
  - `user_type`, `member_gender`, `bike_share_for_all_trip`

## 🔧 Tools Used
- Python (Pandas, NumPy)
- Seaborn & Matplotlib for visualization
- Jupyter Notebook

## 📊 Key Steps
- Imported and cleaned the data (removed nulls and duplicates)
- Explored trip durations, gender breakdowns, and hourly usage
- Visualized rider behavior by time of day and user type
- Created histograms, line plots, and bar charts

## 📈 Insights
- Most rides were taken by **subscribers** (vs. customers)
- Peak riding hours were during **morning and evening commute times**
- Males accounted for the majority of rides
- Weekend usage patterns were different from weekdays

