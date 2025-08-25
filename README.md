# coffee-sales-analysis
Data analysis of coffee sales across countries. includes yearly sales trends, top 10 customers, KPI's and insights using excel

This project provides an overview of coffee sales performance between **2019 and 2022**, highlighting key trends, growth patterns, and areas for strategic improvement. The analysis focuses on variations in **sales, unit price, quantity, customer demographics, and monthly sales trends**.

---

## Objectives
1. Identify trends of total sales for each coffee type.  
2. Highlight the **top 10 customers** based on their contribution to total sales.  
3. Analyze total sales by each country.  
4. Analyze the total quantity ordered for each coffee type.  

---

## Data Description
The dataset was provided as part of an internship project. It contains **sales records across multiple countries**, including information on:

- Quantities  
- Customers  
- Yearly performance  
- Coffee type  
- Unit price  
- Quantity  
- Roast type  
- Customer name  
- Order date  
- Phone numbers  
- Email  
- Address, city, country, postal code  
- Loyalty card  
- Size  
- Profit  
- Product ID  
- Customer ID  

---

## Dataset Size
- **Rows:** 1,001  
- **Columns:** 20  

---

## Tools
- **Excel**

---

## Data Cleaning and Transformation
To ensure data quality and consistency, the following steps were applied:

1. Blank cells were filled using `Ctrl + H`, replacing missing values with `"Unknown"`.  
2. Three separate files (**Orders, Customers, Products**) were merged into a single dataset using `VLOOKUP` to create a unified view for analysis.  

---

## Key Performance Indicators
| Metric       | Value     |
|--------------|----------|
| Sales        | $45.1k   |
| Profit       | $1.3k    |
| Quantity     | 3.6k     |
| Unit Price   | $12.9k   |

---

## Yearly Sales Trend
**Trends and Insights by Coffee Type:**

- **Ara:** Peaked in 2021 ($4,045.63), strong in 2019 ($2,926.63) and 2020 ($3,356.42). Significant drop in 2022 ($1,439.82).  
- **Exc:** Consistent performance: 2019 ($3,481.46), 2020 ($3,663.41), 2021 ($3,468.84), decline in 2022 ($1,691.93).  
- **Lib:** Slightly higher sales in 2019 ($3,378.01) vs 2020 ($2,604.46). Moderate peak in 2021; 2022 remained low ($2,234.92).  
- **Rob:** Lowest sales across all years: 2019 ($2,401.07), 2020 ($2,493.27), 2021 ($2,414.15), 2022 ($1,439.82).  

### 2022 Sales Decline
- Low sales across **Q1–Q3**.  
- **No recorded sales in Q4**, significantly contributing to overall decline.  

---

## Top 10 Customers by Sales Contribution
1. Allis Willmore – $317.07  
2. Brenn Dundredge – $307.07  
3. Terri Farra – $289.11  
4. Nelson Cuttler – $281.68  
5. Don Flintiff – $278.01  
6. Derick Snow – $251.13  
7. Brice Romera – $246.21  
8. Alexa Sizey – $218.73  
9. Ailey Brash – $206.06  
10. **Shared:** Nanny Lush, Shelli Keyna, Teddi Crowthe, Elysee Sketch, Daniel Heinonen, Lacee Tanti ($204.93 each)  

---

## Sales Distribution by Country
- **United States:** ~79% of total sales (primary growth driver)  
- **Ireland:** 15%  
- **United Kingdom:** 6% (needs investigation for lagging performance)  

---

## Quantity Breakdown by Country
- **Ara**: Highest orders – indicates strong customer preference.  
- **Lib**: Lowest orders – indicates lower demand.  

---

*This analysis was performed using Excel and represents insights from the internship dataset.*
