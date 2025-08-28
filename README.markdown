# Saudi-Company-Sales-Analysis

## 1. Data Description
This project uses a dataset containing daily revenue data for January 2025. The data includes sales records for 5 products (A, B, C, D, E) across 5 regions in Saudi Arabia (Riyadh, Jeddah, Al Khobar, Mecca, Dammam). Each entry specifies the date, product, region, and revenue amount. There are 150 records in total (5 products per day over 30 days), with revenues ranging from 529 to 4916 per entry.

## 2. Work Done
### 2.1 Apply DAX to Extract KPIs
DAX measures were created in Power BI to calculate key performance indicators:
- **Total Revenue**: Sum of all revenues = 406,873
- **Number of Regions**: Distinct count of regions = 5
- **Number of Products**: Distinct count of products = 5
- **Average Revenue**: Average revenue per entry = 2,712.49

### 2.2 Build Dashboard
A interactive dashboard was built in Power BI to visualize the data. It includes:
- A line chart showing daily revenue trends over the 30 days.
- Bar charts for revenue by product, by day of the week, and by other breakdowns.
- Cards displaying total revenue, number of products, and other KPIs.
- A gauge chart for average revenue.

![Dashboard Screenshot](https://github.com/HazemMedhat/Saudi-Company-Sales-Analysis-/blob/02acae0e35ce0ffa54bdd24b547c3b5b9c6fec45/%D9%84%D9%88%D8%AD%D8%A9%20%D8%AA%D8%AD%D9%84%D9%8A%D9%84%20%D9%85%D8%A8%D9%8A%D8%B9%D8%A7%D8%AA.png)

## 3. Extracted Insights
### 3.1 Measures
- **Total Revenue**: 406,873
- **Number of Regions**: 5 (Riyadh, Jeddah, Al Khobar, Mecca, Dammam)
- **Number of Products**: 5 (A, B, C, D, E)

### 3.2 Top 3 Products
Based on total revenue:
- Product D: 87,987
- Product B: 87,466
- Product A: 83,670

### 3.3 Top 2 Regions
Based on total revenue:
- Jeddah: 96,524
- Al Khobar: 84,022

### 3.4 Top 3 Days
Based on total revenue by day of the week:
- Wednesday: 78,690
- Thursday: 62,387
- Sunday: 58,289

## 4. Recommendations
### 4.1 
Focusing resources on the most profitable products (D and B) while improving the position of C and E.

### 4.2 
Considering Jeddah as a major growth center, with a strategy to increase sales in Riyadh.

### 4.3 
Allocating targeted marketing campaigns on Wednesday and Saturday to take advantage of the strongest and weakest days.

### 4.4 
Using these analyses as an input to build a dynamic pricing and promotion strategy based on product, region, and day.
