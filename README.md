# 📊 Website Traffic Analysis  
**Internship Project – Data Analyst | Alfido Tech**

---

## 🎯 Objective  
The goal of this project was to analyze real-world website traffic data to identify user behavior patterns, content performance trends, and time-based engagement insights. The project was completed as part of my Data Analyst Internship at Alfido Tech using Python and visualization tools in Google Colab.

---

## 🛠️ Tools & Technologies  
- **Language:** Python  
- **Libraries:** Pandas, Matplotlib, Seaborn  
- **Platform:** Google Colab / Jupyter Notebook

---

## 📁 Dataset Overview  
The dataset contains interaction logs from website traffic. Key columns include:

| Column        | Description                                 |
|---------------|---------------------------------------------|
| `event`       | User interaction (e.g., play, skip, pause)  |
| `date`        | Date of the event                           |
| `country`     | User’s country                              |
| `city`        | User’s city                                 |
| `artist`      | Artist associated with the track            |
| `album`       | Album name                                  |
| `track`       | Track name                                  |
| `isrc`        | International standard recording code       |
| `linkid`      | Unique content identifier                   |
| `Hour`        | Extracted hour from the event timestamp     |
| `Weekday`     | Day of the week                             |
| `Month_Name`  | Name of the month                           |

---

## 🧹 Data Preparation  
The `date` column was converted to datetime format and additional time-based features such as `Hour`, `Weekday`, and `Month_Name` were extracted. Null values were checked and handled, and columns were standardized to ensure consistency throughout the analysis.

---

## 🔍 Analysis & Insights  

**Event Distribution**:  
The most common user interaction recorded was `play`, indicating high user engagement with the content.

**Top Artists & Tracks**:  
The dataset revealed the most popular artists and tracks based on interaction frequency, providing a strong foundation for identifying trending content.

**Geographic Trends**:  
Traffic originated from a diverse set of countries and cities, highlighting potential areas for market focus and regional promotion.

**Weekly Traffic Trends**:

| Weekday   | Visits    |
|-----------|-----------|
| Thursday  | 35,361    |
| Friday    | 34,112    |
| Saturday  | 34,083    |
| Sunday    | 32,633    |
| Wednesday | 30,447    |
| Tuesday   | 29,834    |
| Monday    | 29,808    |

Peak engagement was observed between **Thursday and Sunday**, suggesting optimal timing for content promotion and campaign launches.

**Hourly Activity**:  
All data was timestamped at midnight (Hour = 0), indicating that precise hourly information was not captured. This limited deeper behavioral segmentation based on time of day.

**Monthly Overview**:  
All recorded interactions occurred in **August**, suggesting that this data reflects a short-term campaign or limited analysis window.

---

## 📊 Visualizations  
The analysis was supported by visualizations including:
- Bar chart of top 10 artists  
- Bar chart of top 10 tracks  
- Pie chart of event distribution  
- Countplot of weekday-wise traffic  
- Bar chart of hourly traffic  
- Optional heatmaps (if timestamp precision is improved)

---

## 📌 Key Takeaways  
- Content engagement is strongest toward the end of the week  
- Top artists and tracks account for a significant share of user interest  
- Traffic is geographically concentrated in a few countries and cities  
- The dataset reflects a specific period (August), useful for campaign analysis  
- Timestamp precision should be improved for better behavioral insights

---

## ✅ Recommendations  
- Schedule major content releases between **Thursday and Sunday**  
- Collect full timestamp data (including hour and minute) for advanced time-based analysis  
- Promote top-performing content based on interaction data  
- Track data over a longer period for trend analysis and strategy refinement

---


## 👩‍💻 Intern: Tanishka Jain  
**Company:** Alfido Tech  
**Role:** Data Analyst Intern  
**Project:** Website Traffic Analysis  
**Timeline:** June–July 2025




