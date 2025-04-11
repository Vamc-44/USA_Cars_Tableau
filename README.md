# 🚗 Vehicle Auction Data Cleaning, Analysis & Visualization

This repository contains a Jupyter Notebook that performs **data cleaning, preprocessing, and transformation** on a vehicle auction dataset. The dataset includes details such as brand, model, price, condition, mileage, and more — aimed at preparing it for further analysis, visualization, or machine learning tasks.

## 📁 Files

- `Preprocessing.ipynb` – Jupyter notebook with all data cleaning steps
- `USA_cars_datasets.csv` – Raw dataset used for cleaning
- `cleaned_cars_dataset.csv` - Cleaned dataset
- Tableau dashboard (link or screenshots) – Interactive visualization of key insights

## 🔧 Features

✔️ Column renaming and formatting  
✔️ Title casing for string columns  
✔️ Capitalizing short brand names (≤3 letters)  
✔️ Converting 'condition' (e.g., `10 Days Left`, `22 Hours Left`) to standardized `Days`  
✔️ Dropping rows with `mileage < 10`  
✔️ Filtering out entries with `price = 0`  
✔️ Handling potential data entry issues in `model` names  
✔️ Visualizing data using **Tableau dashboards**

## 📊 Visualizations with Tableau

- Price distribution by brand and model  
- Mileage trends over time  
- Auction time-left breakdown  
- Geo-distribution of vehicles by state  
- Interactive filters for brand, price range, and time left

> Tableau dashboards offer dynamic insights and allow for real-time interaction with the dataset.

## 🛠️ Tools Used

- Python 🐍  
- pandas 🧼  
- Jupyter Notebook 📓  
- Tableau 📊

## 🧠 Next Steps

- Add machine learning models (e.g., price prediction, time-to-sell estimation)  
- Build automated ETL pipeline  
- Host the dashboard online for public access
