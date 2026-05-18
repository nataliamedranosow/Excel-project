# Excel-project
Excel project sales
In this project built entirely in Microsoft Excel, I explored the demographic and behavioral factors that influence bike purchasing decisions across thousands of customers. The project covers the full data workflow: raw data ingestion, cleaning and transformation, aggregation via pivot tables, and final visualization via an interactive dashboard.



 Project Structure
 I've organized the work across four different sheets, in order to show the diffent stages of the analytical process used to achieved the results
 
1) The raw data: Here is the raw dataset, unprocessed with no structure or changes

2 ) Worksheet: In this sheet is where I make all the changes, clean, prepare all the data and standarised it to later analysed it.
 Categorised labels Abbreviated values in the raw data (e.g. M/F, M/S) were expanded to full, readable labels (Male/Female, Married/Single) for clarity in pivot tables and charts.

Created an Age Bracket column: Rather than working with raw ages, I grouped customers into meaningful segments using a nested an 'IF' formula:
  "Adult" — ages 25–34
  "Middle Age" — ages 35–59
   "Old" — ages 60+

    
3) Pivot table: In this part of the work sheet I analyze all the project and make any aggragation or calculation needed in the dataset
   1)  Average Income by Gender and Bike Purchase
   Rows: Gender  Columns: Purchased Bike (Yes / No)
   Values: Average of Income
   Insights show on average, customers who purchased a bike earned more than those who did not, across both genders. Male buyers averaged $60,124             vs.$56,208 for non-buyers; female buyers averaged $55,774 vs. $53,440

    2)  Purchase Count by Commute Distance
    Rows: Commute Distance Columns: Purchased Bike (Yes / No)
    Values: Count of Purchased Bike
    Insight on Customers with very short commutes (0–1 miles) represented the largest group     of bike buyers (200 purchases), while those commuting 10+      miles were the least likely to purchase. This suggests bikes are primarily purchased for short, everyday commuting

    3) Purchase Count by Age Bracket
    Rows: Age Bracket  Columns: Purchased Bike (Yes / No)
    Values: Count of Purchased Bike
    Insights present Middle-aged customers (35–59) made up the largest segment of bike buyers (351 purchases), while younger adults (25–34) and older          customers (60+) purchased far less. 

   
4) Dashboard: The last part of the work I make visual summary from the pivot tables I created earlier. To show patterns or trends in a way that it's easy to understan for those not too technical with the data
    Charts I used:

  Bar chart — Average Income by Gender & Purchase: Compares income levels across four customer segments (Male/Female × Buyer/Non-Buyer), making the income   gap between buyers and non-buyers easy to read

  Line chart — Purchase Count by Commute Distance: Tracks how bike purchase rates change across commute distance bands. I chose the line format              because commute distance has a natural order, and the downward trend as distance increases is clearly visible

  Bar chart — Purchase Count by Age Bracket: Compares purchase volumes across the three age groups, immediately surfacing the dominance of the middle-age    segment.
     
   
