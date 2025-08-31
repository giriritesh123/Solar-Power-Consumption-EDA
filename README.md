# Tetuan City Power Consumption Analysis

This project focuses on **Exploratory Data Analysis (EDA)** of the *Tetuan City Power Consumption Dataset*.  
The aim is to analyze electricity usage in different city zones and understand how environmental factors like temperature, humidity, and wind speed affect power consumption.

--
## How to Run
1. Clone the repository  
2. Open `Solar_AI_Project.ipynb` in Jupyter Notebook  
3. Run all cells to see the analysis



## 📊 Dataset Information
The dataset contains **52,416 rows** with the following features:

- **Temperature** (°C)  
- **Humidity** (%)  
- **Wind Speed** (m/s)  
- **General Diffuse Flows** (Solar Radiation 1)  
- **Diffuse Flows** (Solar Radiation 2)  
- **Zone 1 Power Consumption** (kW)  
- **Zone 2 Power Consumption** (kW)  
- **Zone 3 Power Consumption** (kW)

---

## 🛠 Project Workflow
1. **Data Cleaning**  
   - Checked for missing values  
   - Removed duplicates  
   - Verified datatypes  

2. **Descriptive Statistics**  
   - Mean, Median, Min, Max, Standard Deviation  

3. **Data Visualization**  
   - Correlation Heatmap between all variables  
   - Zone-wise power consumption patterns  
   - Relation of temperature & humidity with consumption  

4. **Insights**  
   - Consumption increases with higher temperature.  
   - Zone 1 consumes the most electricity on average.  
   - Humidity also shows correlation with power demand.  



