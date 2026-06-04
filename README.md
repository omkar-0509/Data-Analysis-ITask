# 🚆 Train Enquiry System using Python and Pandas

## 📌 Project Overview

The **Train Enquiry System** is a Python-based data analysis and interactive application developed using **Pandas, NumPy, Matplotlib, and Seaborn**. The project performs data cleaning, preprocessing, exploratory data analysis (EDA), advanced analytics, and finally builds an interactive route-based train enquiry system.

The application allows users to:
- Explore train datasets.
- Analyze routes and station traffic.
- Validate and clean railway schedule data.
- Find direct trains between source and destination stations.
- Estimate journey durations.

---

## 🎯 Objectives

- Understand and explore railway datasets.
- Perform data preprocessing and quality checks.
- Analyze train routes and station traffic.
- Visualize trends using charts and graphs.
- Build an interactive train enquiry application.

---

## 🛠️ Technologies Used

- Python 3.x
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 📊 Dataset Information

The dataset contains railway schedule information including:

| Column Name | Description |
|------------|-------------|
| SN | Stop Number |
| Train_No | Train Number |
| Station_Code | Station Code |
| Station_Name | Station Name |
| Arrival_time | Arrival Time |
| Departure_Time | Departure Time |
| Distance | Distance Covered |
| Route_Number | Route Identifier |
| 1A | First AC Availability |
| 2A | Second AC Availability |
| 3A | Third AC Availability |
| SL | Sleeper Class Availability |

---

# 📖 Project Levels

## 🔹 Level 1: Basic Data Review

### Tasks
- Dataset overview
- Count records and attributes
- List all trains with start/end stations
- Calculate stops per train
- Find trains with maximum and minimum stops

### Skills
- Data Exploration
- Pandas Basics
- Data Summarization

---

## 🔹 Level 2: Simple Data Processing

### Tasks
- Standardize arrival and departure times
- Compute journey durations
- Classify routes (Short, Medium, Long)
- Generate station-wise train frequency

### Skills
- Data Cleaning
- Datetime Operations
- Classification
- GroupBy Analysis

---

## 🔹 Level 3: Data Quality Checks

### Tasks
- Handle missing values
- Remove duplicate records
- Validate station order
- Save cleaned dataset

### Skills
- Data Validation
- Missing Value Handling
- Duplicate Removal

---

## 🔹 Level 4: Basic Analysis and Visualization

### Tasks
- Compare average journey durations
- Identify high-traffic stations
- Create visualizations
- Generate insights

### Visualizations
- Bar Charts
- Histograms
- Pie Charts
- Station Traffic Analysis

---

## 🔹 Level 5: Advanced Analysis and Visualization

### Tasks
- Pivot Tables
- Cross Tabulations
- Heatmaps
- Comparative Analysis

### Skills
- Pivot Tables
- Crosstab Analysis
- Advanced Visualization
- Data Storytelling

---

## 🔹 Level 6: Final Capstone System

### Features

✔ Find all direct trains between source and destination.

✔ Display route information.

✔ Calculate estimated journey duration.

✔ Interactive user input system.

### Sample Output

```
===== TRAIN ENQUIRY SYSTEM =====

Enter Source Station : HOWRAH JN.
Enter Destination Station : JAYNAGAR

---------------------------------
Train Number : 53041
Route        : HOWRAH JN. -> JAYNAGAR
Journey      : HOWRAH JN. -> JAYNAGAR
Duration     : 15.25 Hours

Thank You!
```

---

## 📈 Key Features

- Data Cleaning and Validation
- Journey Duration Calculation
- Route Classification
- Station Traffic Analysis
- Interactive Console Application
- Multiple Data Visualizations
- Advanced Pivot Table Analysis

---

## 📋 Requirements

Create a file named `requirements.txt` with:

```
pandas
numpy
matplotlib
seaborn
jupyter
```

---

## 🎓 Learning Outcomes

Through this project, the following concepts are demonstrated:

- Python Programming
- Pandas Data Analysis
- Data Cleaning
- Data Visualization
- Exploratory Data Analysis (EDA)
- Pivot Tables and Crosstabs
- User Input Handling
- Mini Application Development

