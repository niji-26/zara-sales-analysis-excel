# Zara Sales Analysis (Excel)

An Excel-based sales analysis of Zara retail transactions (2023–2024), using a cleaned dataset, PivotTables, charts and a KPI summary to understand sales and profit by category, month, product, channel, store and country.

## Dataset

- **Records:** ~10,000 sales transactions
- **Period:** 1 Jan 2023 – 31 Dec 2024
- **Coverage:** 26 store locations across 12 countries (Brazil, China, France, Germany, India, Italy, Japan, Mexico, Spain, UAE, UK, USA)
- **Categories:** Men, Women, Kids, Home (17 sub-categories)
- **Channels:** In-Store, Online, Mobile App

### Columns (20)

| Group | Columns |
|---|---|
| Order & product | `Order_ID`, `Product_ID`, `Product_Name`, `Category`, `Sub_Category`, `Color`, `Size` |
| Location & time | `Store_Location`, `Country`, `Sale_Date` |
| Sales figures | `Quantity`, `Unit_Price`, `Discount_Percent`, `Sales`, `Cost`, `Profit` |
| Customer & channel | `Payment_Method`, `Customer_Type`, `Channel`, `Rating` |

## Workbook structure

| Sheet | Contents |
|---|---|
| `Cleaned_Data` | Cleaned transaction data (source for all analysis) |
| `Sheet1` | 7 PivotTables with 6 charts |
| `Sheet2` | KPI summary |
| `Sheet3` | Dashboard with 6 charts |

## Analysis included

- Sales and profit by **category**
- Sales and profit by **month**
- **Top 10 products** by sales
- Sales by **channel**
- **Store performance** (sales and profit by store)
- Sales and profit by **country**

## KPIs

| KPI | Value |
| Total Sales | ~5.57M |
| Total Profit | ~2.38M |
| Total Quantity Sold | ~53,959 |
| Total Orders | ~9,988 |
| Average Order Value | ~558 |
| Average Rating | ~3.62 |

## Key findings

- **Women** is the top category by sales, followed by Kids, Men and Home.
- **In-Store** drives about half of total sales, ahead of Online and Mobile App.
- **USA** is the highest-selling country; **Madrid**, **Dubai** and **Houston** are among the top stores.
- Sales peak in **August** and **October** and dip in **May**.

## Data notes

- `Size` is stored as a number (34–44), so it applies to clothing and shoes only.
- Some fields contain blanks, mainly `Rating`, `Color`, `Customer_Type`, `Payment_Method`, `Size` and `Product_ID`.

## Tools

- Microsoft Excel
- PivotTables and PivotCharts
- Data cleaning

## Author
Niji Maria John