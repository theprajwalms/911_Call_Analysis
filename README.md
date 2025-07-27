
# 911 Calls Analysis Project

This project analyzes 911 emergency call data to uncover insights into the types of emergencies, response trends, and geographical patterns in emergency calls. The analysis leverages Python, Pandas, Matplotlib, and Seaborn for data exploration and visualization.

## 📂 Dataset

- **Source:** 911 calls dataset (custom, provided during course/project work)
- **Format:** CSV file
- **Features Include:**
  - `lat`, `lng` - Geolocation of the call
  - `title` - Reason for the call (medical, fire, traffic, etc.)
  - `timeStamp` - Date and time of the call
  - `zip`, `twp` - Zip code and township
  - `addr` - Address of the incident
  - `e` - Dummy variable (not relevant for analysis)

## 🔍 Project Objectives

- Categorize and count different types of emergency calls
- Visualize call volumes over time (hours, days, months)
- Analyze trends by geographical location (zip code, township)
- Plot heatmaps and cluster maps to display call density

## 🛠️ Tools & Technologies

- Python  
- Pandas  
- NumPy  
- Matplotlib & Seaborn  
- Jupyter Notebook

## 📊 Key Visualizations

- Bar plots of emergency call categories
- Time series analysis of call volume
- Heatmaps of 911 call density by time and location
- Geospatial analysis of calls using latitude and longitude

## 🚀 How to Run

1. Clone this repository or download the notebook and CSV file.
2. Install dependencies:

```
pip install pandas, numpy, matplotlib, seaborn, 
```

3. Run the notebook `911 Calls Project.ipynb` in Jupyter.

## 💡 Project Highlights

- Explored over 50,000+ emergency call records
- Discovered time-based trends in call volumes
- Mapped emergency types to visualize community needs
- Used heatmaps to identify high-risk time periods and locations

## 📄 License

For educational purposes only.
