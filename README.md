# Victoria Road Accidents - Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project explores road accidents in Victoria, analyzing the impact of **speed zones, road geometry, accident types, and time of day** on accident frequency and severity. 

## 📊 Dataset
- **Source**: [Victoria Road Crash Data](https://discover.data.vic.gov.au/dataset/victoria-road-crash-data/resource/11b93427-60b7-46c8-be2e-6419f1b5c978)
- **Key Variables Analyzed**:
  - `ACCIDENT_DATE`: Timestamp of the accident.
  - `SPEED_ZONE`: Speed limit where the accident occurred.
  - `ROAD_GEOMETRY_DESC`: Road type (e.g., intersection, roundabout).
  - `ACCIDENT_TYPE_DESC`: Type of accident (e.g., collision, pedestrian struck).
  - `SEVERITY`: Level of severity.
  - `NO_OF_VEHICLES`: Number of vehicles involved.
  - `POLICE_ATTEND`: Indicates whether police attended the scene.

---

## 🔍 Key Findings from Analysis

### **1️⃣ Accidents by Time of Day**
- **Afternoon (12 PM - 6 PM) has the highest number of accidents**, likely due to peak-hour traffic.
- **Nighttime accidents are fewer but tend to be more severe**, possibly due to reduced visibility.

### **2️⃣ Speed Zone and Accident Frequency**
- **50 km/h and 60 km/h zones have the highest accident rates**, mainly on local and arterial roads.
- **100-110 km/h highway accidents are less frequent but more severe**, due to higher speeds.

### **3️⃣ Road Type and Accident Severity**
- **Local roads have the highest accident counts**, particularly in 50 km/h zones.
- **Highways and non-arterial roads** have **fewer but more severe accidents**.

### **4️⃣ Police Attendance Trends**
- **Pedestrian-related accidents and fixed-object collisions** have the highest police attendance rates.
- **Minor vehicle collisions are less likely to have police on site**.

---

## 📈 Exploratory Data Analysis (EDA) Steps

### **1️⃣ Data Cleaning**
- Checked for missing values and handled `RMA` (Road Management Authority) missing values.
- Converted `ACCIDENT_DATE` into separate **date, time, and time-of-day categories**.

### **2️⃣ Univariate Analysis**
- **Plotted bar charts, histograms, and boxplots** to analyze individual variables.
- Identified **outliers in speed zones** where values exceeded 1000 km/h (incorrect data points).

### **3️⃣ Bivariate Analysis**
- Examined **the impact of speed zones and road types on accident frequency and severity**.
- **Heatmaps and correlation matrices** showed that speed and road geometry are key factors in accident severity.

### **4️⃣ Multivariate Analysis**
- Built a **linear regression model** to predict accident severity based on **speed zone, road type, and accident type**.
- Used a **decision tree model** to classify accident severity levels.

---

## 📊 Visualizations in the Notebook
The Jupyter Notebook contains:
- **Heatmaps** to analyze accident distribution.
- **Boxplots** for severity comparisons.
- **Bar charts** for accident types and frequency.
- **Decision Tree Model Visualizations** for predicting accident severity.

---

   ## 📌 Next Steps
- 🔍 **Develop a Machine Learning model** to predict accident severity.
- 🌦 **Investigate the role of weather conditions** in accident severity.
- 📊 **Identify trends over multiple years** to assess the effectiveness of road safety measures.

## 🏆 Author
- **Your Name**: Avirukth Gurulingegowda Thadaklur  
- 🔗 **LinkedIn**: [Avirukth Gurulingegowda Thadaklur](https://www.linkedin.com/in/avirukth-thadaklur-6323722b7/)
- 💻 **GitHub**: [Randxmforest](https://github.com/Randxmforest)  


