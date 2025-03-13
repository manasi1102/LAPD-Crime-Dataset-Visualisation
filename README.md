# LAPD-Crime-Dataset-Visualisation


# 📌 Los Angeles Crime Dashboard  

### 📊 Analyzing and Visualizing Crime Patterns for Public Safety Insights  

## 🚀 Overview  
Los Angeles Crime Dashboard is an interactive data visualization project designed to analyze and explore crime patterns in Los Angeles using public crime data from the **Los Angeles Police Department (LAPD)**. The project provides insights into crime trends, geographic hotspots, and victim demographics through dynamic and interactive visualizations.  

## 🔍 Features  
✅ **Crime Trends & Analysis:** Visualizing crime rates over time using **line charts** and **bar graphs**  
✅ **Geospatial Crime Mapping:** Identifying crime hotspots using **heatmaps** and **cluster maps**  
✅ **Demographic Analysis:** Analyzing crime victims by **age, gender, and ethnicity** using pie charts  
✅ **Interactive Filters:** Explore crime types, time periods, and locations dynamically  
✅ **Data Processing Pipeline:** Cleaned and categorized over **900,000 crime records** for structured analysis  

## 📂 Data Source  
The dataset is sourced from the **Los Angeles Police Department (LAPD) Open Data Portal** and includes crime incidents reported between **2020 to the present**. Data preprocessing and analysis were performed using **Pandas, NumPy, and PostgreSQL**.  

## 🛠️ Technologies Used  
- **Python** (Pandas, NumPy, Matplotlib, Seaborn, Plotly, Folium)  
- **Data Processing & Storage:** PostgreSQL, Stratified Sampling, API Integration  
- **Visualization Tools:** Streamlit for dashboard deployment, Tableau for additional insights  
- **Geospatial Analysis:** Heatmaps & Cluster Maps using **Folium & Plotly**  

## 📊 Dashboard Preview  
![Dashboard Preview](annotated-LAPD_Dashboard.pdf)  

## 📥 How to Use  
1️⃣ Clone the repository:  
```bash
git clone https://github.com/manasi1102/LAPD-Crime-Dataset-Visualization.git
```  
2️⃣ Install dependencies:  
```bash
pip install -r requirements.txt
```  
3️⃣ Run the dashboard:  
```bash
streamlit run app.py
```  

## 📌 Insights & Findings  
🔹 **Downtown LA and adjacent areas are high-crime hotspots** 🏙️  
🔹 **Crime rates peak on Fridays due to nightlife & social activities** 🕺  
🔹 **Vehicle theft is the most frequent crime, followed by burglary** 🚗🔑  
🔹 **Hispanic & Black communities show higher victimization rates** 📊  

## 🔮 Future Enhancements  
🚀 **Predictive Analytics:** Integrate ML models to forecast crime trends  
☁️ **Cloud Deployment:** Optimize scalability using AWS/GCP  
🌎 **City Comparisons:** Expand the dashboard to analyze crime patterns across multiple cities  

## 📜 References  
- [LAPD Open Data Portal](https://data.lacity.org/Public-Safety/Crime-Data-from-2020-to-Present/2nrs-mtv8)  
- [Koreatown Crime Data Project](https://sodavi.org/portfolio-items/crime-data/)  
