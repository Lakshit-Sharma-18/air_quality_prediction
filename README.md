# 🌫 Air Quality Prediction using Machine Learning

## 📌 Overview
This project focuses on **predicting air quality levels using machine learning techniques**. The dataset contains information about different pollutants such as **SO2, NO2, RSPM, SPM, and PM2.5** collected from monitoring stations across different locations.

The objective of this project is to analyze pollution data, handle missing values, visualize pollution trends, and build a model that helps understand and predict air quality conditions.

---

## 📊 Dataset Description
The dataset contains multiple attributes related to air pollution monitoring.

Main features include:

- **stn_code** – Monitoring station code  
- **sampling_date** – Date of sample collection  
- **state** – Indian state where monitoring was conducted  
- **location** – Location of monitoring station  
- **agency** – Monitoring agency  
- **type** – Type of area (industrial, residential, etc.)  
- **so2** – Sulphur dioxide concentration  
- **no2** – Nitrogen dioxide concentration  
- **rspm** – Respirable suspended particulate matter  
- **spm** – Suspended particulate matter  
- **pm2_5** – Fine particulate matter (PM2.5)

These pollutants are used to analyze and estimate the **Air Quality Index (AQI)**.

---

## ⚙️ Project Workflow

### 1. Data Understanding
- Examined dataset features and structure
- Identified pollutant variables affecting air quality
- Studied monitoring locations and sampling information

### 2. Data Preprocessing
- Checked for **missing values**
- Handled null values in pollution parameters
- Cleaned and prepared data for analysis

### 3. Data Visualization
- Visualized pollutant distributions
- Analyzed pollution trends across locations
- Observed relationships between different pollutants

### 4. AQI Calculation
The **Air Quality Index (AQI)** is calculated using pollutant concentration values.  
AQI is computed using a **piecewise linear function** based on pollutant concentration ranges.

This helps categorize air quality into levels such as:

- Good
- Satisfactory
- Moderate
- Poor
- Very Poor
- Severe

---

## 🛠 Technologies Used

- **Python**
- **Jupyter Notebook**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Machine Learning techniques**

---

## ▶️ How to Run the Project

```bash
# Clone the repository
git clone https://github.com/your-username/air-quality-prediction.git

# Move into the project directory
cd air-quality-prediction

# Open the Jupyter Notebook
jupyter notebook air-quality-prediction.ipynb
