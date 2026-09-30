# Retail-Sales-Analysis
# Bike Sales Analysis

An Excel-based analysis of bike buyer data, exploring which customer characteristics are linked to buying a bike. The workbook goes from raw data to a cleaned dataset, pivot tables, and an interactive dashboard.

## Files

| File | Description |
|------|-------------|
| `Bike_Sales_Analysis.xlsx` | The full workbook (raw data, cleaned data, pivot tables, dashboard) |

## Dataset

1,000 customer records after cleaning, with 13 attributes each:

| Column | Description |
|--------|-------------|
| ID | Unique customer ID |
| Marital Status | Married / Single |
| Gender | Male / Female |
| Income | Annual income |
| Children | Number of children |
| Education | Highest education level |
| Occupation | Type of occupation |
| Home Owner | Yes / No |
| Cars | Number of cars owned |
| Commute Distance | Distance bracket (0-1 to More than 10 miles) |
| Region | Europe / North America / Pacific |
| Age | Age in years |
| Purchased Bike | Yes / No (target variable) |

## Workbook Structure

1. **bike_buyers** – the original raw data, kept untouched for reference.
2. **Workbook** – the cleaned working sheet:
   - Abbreviated values standardised (e.g. `M` → `Married`, `S` → `Single`, `F` → `Female`, `M` → `Male`)
   - A new **Age-Brackets** column created with a formula:
     - Adolescent: under 31
     - Middle Age: 31 to 54
     - Old: over 54
3. **Pivot Table** – pivot tables and charts summarising the data.
4. **Dashboard** – the final dashboard, with slicers for filtering.

## Dashboard

The **Bike Sales Dashboard** contains three charts:

- **Average Income per Purchase** – average income by gender, split by purchase decision
- **Customer Commute** – bike purchases by commute distance
- **Customer Age Brackets** – bike purchases by age group

## Key Findings

About **48%** of customers (481 of 1,000) bought a bike.

- **Age:** Middle-aged customers (31 to 54) buy the most, with roughly a 55% purchase rate. Adolescents (about 35%) and older customers (about 31%) buy far less often.
- **Commute distance:** Shorter commutes are linked to more purchases. Customers with 0-1 mile commutes bought at about 55%, while those commuting more than 10 miles bought at only about 30%.
- **Income and gender:** Male buyers had a higher average income (about $46.3K) than male non-buyers (about $38.3K). For females, the averages were similar between buyers and non-buyers.
- **Region:** Pacific had the highest purchase rate (about 59%), followed by Europe (about 49%) and North America (about 43%).
- **Marital status and cars:** Single customers bought more often than married ones (about 54% vs 43%), and customers with fewer cars were more likely to buy.

## Tools and Skills Used

- Microsoft Excel
- Data cleaning and standardisation
- Formulas (`IF` for age bracketing)
- Pivot tables and pivot charts
- Slicers and dashboard design

## How to Use

1. Download `Bike_Sales_Analysis.xlsx`.
2. Open it in Microsoft Excel (slicers and pivot features work best in the desktop version).
3. Go to the **Dashboard** sheet and use the slicers to filter the charts.

## Author

*Your Name* – [GitHub](https://github.com/your-username) | [LinkedIn](https://www.linkedin.com/in/your-profile)
