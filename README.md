# 🛫 Flight Fare Prediction - Exploratory Data Analysis (EDA)

This repository contains Exploratory Data Analysis (EDA) on an Indian airline dataset, aimed at preparing the data for machine learning models to predict flight fares.

## 📄 Dataset

- **Source**: [Data_Train.xlsx] - Indian airline flight fare dataset.
- **Rows**: ~10,000+
- **Columns**: Airline name, source/destination cities, timings, duration, total stops, and price.
- **Objective**: Understand trends and perform feature extraction to support accurate price prediction.

## 🧪 EDA Tasks Performed

- 📥 **Data Loading** using `pandas.read_excel`
- 🔍 **Missing Values Analysis** and reporting
- 🧹 **Data Cleaning**:
  - Converted `Date_of_Journey` into `Day`, `Month`, `Year`
  - Extracted `Arrival_hour`, `Arrival_min` from `Arrival_Time`
  - Processed `Duration` to extract duration in hours and minutes
- 🔁 **Feature Engineering**:
  - Split complex time/date fields into numeric features
  - Removed redundant fields after processing
- 📊 **Statistical Summary**:
  - Used `.describe()` and `.info()` to understand data structure

## 🧰 Tools Used

- Python 3.x
- pandas
- numpy
- seaborn
- matplotlib
