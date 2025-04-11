# 🚗 Vehicle Auction Data Cleaning, Analysis & Visualization

This repository contains a Jupyter Notebook that performs **data cleaning, preprocessing, and transformation** on a vehicle auction dataset. The dataset includes details such as brand, model, price, condition, mileage, and more — aimed at preparing it for further analysis, visualization, or machine learning tasks.

## 📁 Files

- `vehicle_data_cleaning.ipynb` – Jupyter notebook with all data cleaning steps
- `vehicle_dataset.csv` – Raw dataset used for cleaning
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

## 📊 Sample Preview

| Price($) | Brand     | Model   | Mileage | Time_Left       | Time_Left_Days |
|----------|-----------|---------|---------|------------------|----------------|
| 6300     | TOYOTA    | Cruiser | 274117  | 10 Days Left     | 10.0           |
| 2899     | FORD      | SE      | 190552  | 6 Days Left      | 6.0            |
| 25000    | FORD      | Doors   | 64146   | 22 Hours Left    | 0.92           |

## 🧠 Next Steps

- Add machine learning models (e.g., price prediction, time-to-sell estimation)  
- Build automated ETL pipeline  
- Host the dashboard online for public access

## 📫 Contact

Made with 💻 by **Vamshidhar Reddy**  
Feel free to connect on [LinkedIn](https://www.linkedin.com) or check out my [GitHub](https://github.com/vamshidharkommineni)
