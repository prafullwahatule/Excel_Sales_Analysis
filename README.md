 # 📊 Excel Sales Analysis

An interactive Excel Sales Dashboard project built to analyze 10,000+ sales transactions.
This project demonstrates data cleaning, transformation, KPI calculation, pivot tables, and dashboard visualization using Microsoft Excel.

## 📂 Project Structure
```
Sales_Analysis/
 ├─ 1_Raw_Data/        # Original dataset
 ├─ 2_Cleaned_Data/    # Processed & cleaned dataset
 ├─ 3_Analysis/        # KPI calculations & Pivot Tables
 ├─ 4_Visuals/         # Dashboard charts & visuals
 └─ 5_Reports/         # Final report & export files
```

## 🛠️ Steps Performed
🔹 Data Preparation (Power Query)
- Loaded raw dataset into Excel

- Applied transformations:

- Promoted headers

- Changed data types

- Removed errors, blanks & duplicates

- Added Sales_ID column (SLS-1, SLS-2, ...)

- Created calculated columns:

- Total Sales = Quantity × Price
  Earned Commission = Total Sales × Commission
  

## 🔹 KPI Calculations

| Sr.No | KPI                       | Formula / Logic                                | Use                    |
|-------|---------------------------|-----------------------------------------------|-----------------------|
| 1     | Total Sales               | SUM(Total Sales)                              | Overall revenue        |
| 2     | Total Quantity Sold       | SUM(Quantity)                                 | Volume of sales        |
| 3     | Total Commission Earned   | SUM(Earned Commission)                        | Total payout           |
| 4     | Average Sales per Transaction | AVERAGE(Total Sales)                        | Transaction efficiency |
| 5     | Average Commission %      | (SUM(Earned Commission) ÷ SUM(Total Sales)) × 100 | Profitability insight |
| 6     | Top Sales Rep (by Sales)  | Pivot (Sales Rep, Total Sales, Sort Desc)    | Best performer         |
| 7     | Top State (by Sales)      | Pivot (State, Total Sales, Sort Desc)        | Best market            |
| 8     | Most Selling Item         | Pivot (Item, Quantity, Sort Desc)            | Demand analysis        |
| 9     | Top vs Bottom Performers  | Pivot + Conditional Formatting               | Highlights extremes    |
| 10    | Commission Efficiency     | (Earned Commission ÷ Total Sales)            | Efficiency comparison  |


## 🔹 Pivot Table Analysis

| Analysis Type                  | Description                                |
|--------------------------------|--------------------------------------------|
| Sales by Item                  | Compare sales & quantity per item          |
| Sales by Sales Rep             | Performance by representative             |
| Sales by State                 | Regional sales distribution                |
| Sales Trend by Date            | Monthly/Yearly trend analysis              |
| Commission Analysis            | Who earns the most commission              |
| Quantity by Item & State       | Cross-analysis for demand                  |
| Top vs Bottom Performers       | Highlights best & worst                     |
| Commission Efficiency          | Efficiency % across sales reps             |


## 📈 Dashboard Features

- Clean & professional UI design with slicers and charts
- KPIs at a glance (cards for Total Sales, Avg Sales, etc.)
- Time-series trend chart for daily/monthly analysis
- Geographical map chart for state-wise performance
- Bar & Pie charts for Sales Rep, Item, and Commission
- Top vs Bottom analysis with conditional formatting
- Insights box with key findings


## 🖼️ Dashboard Preview
<img width="1920" height="1080" alt="Screenshot 2025-10-09 234124" src="https://github.com/user-attachments/assets/39e6565f-19d0-4417-9d1b-31286bcab138" />
<img width="1690" height="872" alt="Screenshot 2025-10-09 234155" src="https://github.com/user-attachments/assets/78afd8cc-bbae-4273-bce6-6f9927dbb2bb" />

## 🚀 How to Use
Clone this repo:
```bash
git clone https://github.com/prafullwahatule/Excel_Sales_Analysis.git
```
1. Open the Excel file in the 4_Visuals/ folder

2. Interact with slicers and charts to explore insights

## 🎯 Key Insights (Sample)

- Total Sales: ₹15,84,466

- Top Sales Rep: Stacey

- Top State: Gujarat

- Most Selling Item: White Board

- Highest Commission Efficiency: Bob (7.69%)


## 🛠️ Tools Used

- Microsoft Excel → Power Query, Pivot Tables, Charts

- Conditional Formatting → Top/Bottom highlighting

- Map Chart → State-wise sales visualization
---

## 📌 Future Improvements

1. Automate dashboard refresh with macros

2. Connect to a live database (SQL/Power BI)

3. Add forecasting models


## 👤 Author

- **Name:** Prafull Wahatule
- **Email:** prafullwahatule@gmail.com
- **GitHub:** [Profile](https://github.com/prafullwahatule)

