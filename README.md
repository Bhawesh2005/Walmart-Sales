# Satvik's Walmart-Sales-Dashboard.

## Problem Statement

The objective is to develop a comprehensive and interactive sales dashboard using Power BI to empower Walmart's management and operational teams with real-time insights into sales performance, trends, and key metrics across various dimensions. The dashboard should facilitate data-driven decision-making, enhance visibility into sales operations, and identify areas for improvement.



![Screenshot 2024-08-04 151403](https://github.com/user-attachments/assets/67e880a6-06a5-4605-a46f-ac601430782f)

### PowerBI Link-
https://app.powerbi.com/groups/me/reports/0fb0a0bd-86be-42a1-adbf-afb1ef698061/ReportSection?experience=power-bi

### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : It was observed that in none of the columns errors & empty values were present except column named "Delivery Delay".
- Step 5 : For calculating average delay time, null values were not taken into account as only less than 1% values are null in this column(i.e column named "Deivery Delay") 
- Step 6 : In the report view, under the view tab, theme was selected.
- Step 7 : Since the data contains various regions, thus in order to represent regions, a new visual was added using the three ellipses in the visualizations pane in report view. 
- Step 8 : Visual filters (Slicers) were added for four fields named Central", "East", "West" & "South".
- ![Screenshot 2024-08-04 151423](https://github.com/user-attachments/assets/ad68a88e-1cef-410c-b8fa-6492e12ec479)
- ![Screenshot 2024-08-04 151440](https://github.com/user-attachments/assets/0cd1a6e7-0f7e-453e-8a32-959231cb5caf)
- ![Screenshot 2024-08-04 151505](https://github.com/user-attachments/assets/b3a0ca91-05ee-404d-a271-3c940e1fa8d8)
- ![Screenshot 2024-08-04 151519](https://github.com/user-attachments/assets/11d5563e-8519-40d3-af9e-4deed7022400)
- Step 9 : Two card visuals were added to the canvas, one representing average sales  & other representing average profit.
           Using visual level filter from the filters pane, basic filtering was used & null values were unselected for consideration into average calculation.
           
           Although, by default, while calculating average, blank values are ignored.
- 

  
In our dataset, Some parameters were assigned value 0, representing those parameters are not applicable for some customers.

All these values have been ignored while calculating average rating for each of the parameters mentioned above.

- Step 13 : In the report view, under the insert tab, using shapes option from elements group a rectangle was inserted & similarly using image option company's logo was added to the report design area. 

- Step 14 : Calculated column was created in which, customers were grouped into various age groups.

# Walmart Sales Dashboard Insights

## 📊 Key Insights

### 1. **Annual Sales and Profit**
   - The total sales for the year amounted to **$154.9K**, while the total profit was **$21.95K**, indicating a profit margin of approximately **14.2%**.

### 2. **Seasonal Trends**
   - Sales peaked during **December**, driven by holiday shopping, but profit saw significant increases in **April, May, June**, and **December**, highlighting effective cost management and high-margin product sales during these months.

### 3. **Regional Performance**
   - **California** emerged as the top-performing state, boasting the highest sales and profit figures.

### 4. **Payment Methods**
   - The most preferred mode of payment was **online**, followed by **Cash on Delivery (COD)** and **credit cards**.

### 5. **Delivery Efficiency**
   - The average delivery time for online orders was **4 days**, indicating efficient logistics and prompt service.

### 6. **Product Performance**
   - **Phones** were the highest selling product, while **furniture** was the leading category in sales.

### 7. **Regional Sales and Profit**
   - The **Central** region dominated both sales and profit figures, followed by the **West**, **East**, and **South** regions, respectively.

---

By analyzing these insights, Walmart can enhance strategic planning, optimize regional performance, and improve overall customer satisfaction.

        
