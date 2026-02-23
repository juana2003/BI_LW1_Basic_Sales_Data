 Verify Data in Data View

![Dashboard Screenshot](https://github.com/juana2003/BI_LW1_Basic_Sales_Data/blob/9ec851231bbd17638c11e7d49040ac9057eb3fd8/Verify%20Data%20in%20Data%20View.png)


 
● Are all columns visible?  yes all columns are visible

● Is “Date” formatted as Date?  yes it's already formatted 

● Is “Sales” formatted as Decimal Number?  No it was not formatted as Decimal

If Data Type is Incorrect:

1. Click the column
2. Go to Column Tools
3. Change Data Type accordingly:
○ Date → Date
○ Sales → Decimal Number
○ Product/Category/Region → Text

CORRECTED DATA

![if data is Incorrect Screenshot](https://github.com/juana2003/BI_LW1_Basic_Sales_Data/blob/9baf3977861b07a07c91a4fa1e2f776dcb5b3b87/If%20Data%20Type%20is%20Incorrect.png)

CREATING AUTO-GENERATE VISUALS

![Quick Visualization Screenshot](https://github.com/juana2003/BI_LW1_Basic_Sales_Data/blob/e12885315ecf20bbb99b3d3667ef513e8b8f2ced/Quick%20Visualization.png)

● What type of chart was created? Clustered column chart

● What does it show? it shows the sum of sales in form of chart

CREATING SALES BY REGION CHART

![SALES BY REGION Screenshot]( https://github.com/juana2003/BI_LW1_Basic_Sales_Data/blob/9baf3977861b07a07c91a4fa1e2f776dcb5b3b87/Create%20a%20Sales%20by%20Region%20%20Chart(Clustered%20column%20chart).png)

● Which region has highest sales? West

SALES BY CATEGORY

![SALES BY CATEGORY Screenshot](https://github.com/juana2003/BI_LW1_Basic_Sales_Data/blob/9baf3977861b07a07c91a4fa1e2f776dcb5b3b87/Sales%20by%20Category%20(Pie%20Chart).png)

● Which category dominates? Electronics

● Is the distribution balanced? No, they're not balance because the electronics was the highest category and followed by the furniture while the office supplies was the lowest. 

SALES OVER TIME

![SALES OVER TIME Screenshot](https://github.com/juana2003/BI_LW1_Basic_Sales_Data/blob/9baf3977861b07a07c91a4fa1e2f776dcb5b3b87/Sales%20Over%20Time%20(line%20chart).png)

● Is there growth? There's no grownth, Instead of increasing, the sales decreased from 2024 (about 0.2M) to 2025 (about 0.02M).

● Any noticeable trend? Yes. There is a clear downward trend, because the line consistently declines from 2024 to 2025.


BASIC DATA INSIGHT INTERPRETATION


● Which region contributes most revenue? The West region contributes the most revenue, as it has the tallest bar among all regions.

● Which product category performs best? Electronics performs best, having the largest share in the pie chart (about 40.82%), which is higher than Furniture and Office Supplies.

● Are sales consistent across dates? No. Sales are not consistent because they drop significantly from 2024 to 2025, showing a sharp decline.

● What business recommendation can you suggest?

Since sales are decreasing:

1. Investigate why sales dropped in 2025.
   
2. Focus marketing and promotions on strong regions like West and East.
   
3. Invest more in Electronics, since it is the top-performing category.
   
4. Improve strategies in lower-performing regions like North.
   

TECHNICAL QUESTIONS


1. What are the five columns in the dataset? Date, Product, Catgory, Region and Sales
   
2. What data type is assigned to the “Sales” column? Decimal Number
   
3. Which Power BI view allows you to see raw data? Table View
   
4. What chart type is best for showing trends over time? A Line Chart is best for showing trends over time because it clearly displays changes and patterns along a timeline.
   
5. What aggregation is automatically applied to Sales? The aggregation automatically applied to the Sales column is Sum.


 ANALYTICAL QUESTIONS
 

6. Which region has the highest total sales? West

7. Which category has the lowest performance? Office supplies
   
8. Are sales increasing, decreasing, or stable? Decreasing
    
9. If you were a manager, which region would you prioritize?
    
      If I were a manager, I would prioritize the West and North regions. I would focus on West to maintain its consistently high performance and
      ensure it continues to excel. For the North, I would prioritize it because I want to help it grow and improve its performance so it doesn’t fall behind compared to other regions.
    
10. Provide one actionable recommendation based on the data.
    
     Based on the data, one actionable recommendation is to invest in marketing and training for the North region and the Office Supplies category.
     This could help boost sales in underperforming areas while maintaining strong performance in the West region.





ENHANCEMENT SECTION


Task 1: Add a Card Visualization

![SALES OVER TIME Screenshot](https://github.com/juana2003/BI_LW1_Basic_Sales_Data/blob/0740ee0866238e3ce855dca21a0c5763488920a8/Card%20Visualization.jpg)

Question:

● What is the total sales amount? ₱220,229

Task 2: Add Slicer

![SALES OVER TIME Screenshot](https://github.com/juana2003/BI_LW1_Basic_Sales_Data/blob/0740ee0866238e3ce855dca21a0c5763488920a8/Add%20slicer.jpg)

Question:

● What happens to other visuals when you click a region? It displays a total sales of each region

● Why is filtering important in BI? Filtering is important because it lets you see only the data you need, making analysis clearer, faster, and more useful.

Task 3: Sort Sales

![SALES OVER TIME Screenshot](https://github.com/juana2003/BI_LW1_Basic_Sales_Data/blob/0740ee0866238e3ce855dca21a0c5763488920a8/Sort%20Decending.jpg)

Question:

● Does sorting improve readability? yes sorting improves readability.

● Why?  Because sorting organizes the data in a clear.


Task 4: Identify Outliers

● Which region is significantly higher or lower? 

Significantly lower: North – its total sales (45K) are noticeably lower than the other regions (55–58K).

Significantly higher: No region is a major outlier on the high end; West, East, and South are fairly close (55–58K), so there isn’t a strong high outlier.

● What might explain that difference? 

North region lower sales could be due to:

   - Fewer stores or branches compared to other regions.

   - Lower population or market demand in that region.

   - Seasonal or operational issues affecting sales.

   - Less effective marketing or product availability compared to other regions.
     
