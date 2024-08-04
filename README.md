# Satvik's Walmart-Sales-Dashboard.

## Problem Statement

The objective is to develop a comprehensive and interactive sales dashboard using Power BI to empower Walmart's management and operational teams with real-time insights into sales performance, trends, and key metrics across various dimensions. The dashboard should facilitate data-driven decision-making, enhance visibility into sales operations, and identify areas for improvement.


### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : It was observed that in none of the columns errors & empty values were present except column named "Delivery Delay".
- Step 5 : For calculating average delay time, null values were not taken into account as only less than 1% values are null in this column(i.e column named "Deivery Delay") 
- Step 6 : In the report view, under the view tab, theme was selected.
- Step 7 : Since the data contains various regions, thus in order to represent regions, a new visual was added using the three ellipses in the visualizations pane in report view. 
- Step 8 : Visual filters (Slicers) were added for four fields named Central", "East", "West" & "South".
- Step 9 : Two card visuals were added to the canvas, one representing average sales  & other representing average profit.
           Using visual level filter from the filters pane, basic filtering was used & null values were unselected for consideration into average calculation.
           
           Although, by default, while calculating average, blank values are ignored.
- 

  
In our dataset, Some parameters were assigned value 0, representing those parameters are not applicable for some customers.

All these values have been ignored while calculating average rating for each of the parameters mentioned above.

- Step 13 : In the report view, under the insert tab, using shapes option from elements group a rectangle was inserted & similarly using image option company's logo was added to the report design area. 

- Step 14 : Calculated column was created in which, customers were grouped into various age groups.


        
