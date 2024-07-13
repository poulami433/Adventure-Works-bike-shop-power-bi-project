 ;::![1_T-P1WsT8iDNMz6Io4mVxLg](https://github.com/poulami433/Adventure-Works-bike-shop-power-bi-project/assets/171598364/8cb0f4de-077a-4109-bdbe-cfdc2d844a44)
# OVERVIEW OF THE ADVENTURE WORKS BIKE SHOP POWER BI PROJECT :

The Power Bi Project is comprehensive analysis and visualization of the adventure works bike shop data . It's desighned as a practical application of the skills taught in the "Power Bi Desktop 2024" , course by @Maven Analytics  . Key features of this project include :

1. Interactive Dashboards : Customized dashboards providing insightful metrics and KPIs relevant metrics to the bike shop's operations
2. Data Models : Well-structured data models that integrate various data sources for a holistic view of the business.
3. Analytical Report : Detailed reports focusing on sales performance , customer demographics ,inventory management and more.
4. Visualizations : A range of visualization including bar charts , line graphs , pic charts ,and maps offering intuitive data interpretations .

  In this project I used Power Bi to visualize the sales and returns data of a hypothetical bike shop . Adventure Works . Using techniques learned throughout the course . I visualized global data across time periods ,products and customers . 

  I decided to use this project purely as a method to learn the visualization and amalysis techniques , choosing not to actually analyse the results in any real depth as the data is made up and didn’t seem to display any meaningful trends. I’m currently working on a much more interesting project which will have some much more exciting analysis! 

 # The Data

 This data comes from Maven Analytics and is hypothetical, as mentioned above. The data was stored in 3 separate tables, with 56,046 rows of sales data, 1,809 rows of returns data and 293 rows of product data. The raw data is provided as part of this course and so is only accessible as part of this course. 

 # Key Insights Techniques Learned 

 I started off by connecting and shaping the data, carrying out some data quality assurance and getting the tables in order. This was my first time working in the Power BI query editor so there was a lot of new content! Moving on, I created my first data model, learning about relational models, cardinality, and filter flow. This was one of the most interesting sections as these are concepts which I could’ve definitely overlooked had I self-studied Power BI! 
 Then came the section I was most looking forward to – learning DAX. This is the part I’ve heard people talk about, the power of BI’s DAX functionality is really impressive. 

 # Some of favourite tools and functions 

 1. Measures – the way that you can utilise measures in visualisations gives Power BI a big step up on Excel for me. 
 2. Switch – although I’ve since found out this is available in Excel too, this was the first time I’d seen this function and I love the simplicity of it. 
 3. Related – I’ve been using VLOOKUPs for a long time and, to be fair, their syntax is pretty logical, but this takes logical syntax to a whole new level. 
 After learning DAX came the exciting part of actually building some dashboards. I built 4 dashboards and a decomposition tree, which are pretty in depth and will naturally be better viewed in Power BI Service where the functionality all works, but I thought I’d include some screenshots to show my favourite features below.

 # 1) Executive Dashboard: 
   A high level summary of this data set 
     ![Screenshot (1)](https://github.com/poulami433/Adventure-Works-bike-shop-power-bi-project/assets/171598364/e8a6d0ca-d8c1-4c15-a433-664dd79decd3)
   Highlights on this dashboard: 
  After inserting the table showing the top 10 products and the associated orders, revenue and return rate, I was able to incorporate some drill through functionality. This means that if you click on a specific product you can go to a separate dashboard (The Product Detail Dashboard) and view more details on just this specific product. I think this is a great little trick which adds a lot of value to dashboards. 
While the cards at the bottom left showing monthly revenue, orders and returns are useful on their own, the addition of conditional formatting based off of whether or not they have reached their monthly targets is a huge value add. Further, these targets are dynamic as they are based on the previous months’ revenue/orders/returns total.
The filter button at the top left brings up a Slicer Panel which allow users to filter the entire page by continent and year, which allows for a whole new angle of analysis.
![Screenshot (8)](https://github.com/user-attachments/assets/fa6f1ed6-47b0-49d9-8b2e-51597cf36b84)

# 2) Map – A nice simple visualisation to learn about using geospatial data & tooltips.
   ![Screenshot (2)](https://github.com/user-attachments/assets/ca326e58-7d26-4e65-a86b-8350cd187bcf)


# 3) Product Details – All the product specific KPIs.
![Screenshot (3)](https://github.com/user-attachments/assets/36481819-a14a-420f-982d-b92114b037b2)


Highlights on this dashboard:

3.1) As mentioned above, this page is a drill through from the executive dashboard, so whichever product you look at on that dashboard will be shown in more detail here. 

3.2) One of my favourite features learned throughout this process – parameters! Using numerical field parameters to enable users to run their own scenario analysis in real time is an unbelievable feature for analysis. Couldn’t believe how easy it was to build in and use.

3.3) A very useful technique shown here is the gauges along the top of the dashboard which are a great way to show KPI performance against targets.

 # 4)   Customer Details – All the customer specific KPIs.

![Screenshot (4)](https://github.com/user-attachments/assets/489978fe-90e4-43c8-b151-d635628fd251)

This dashboard is pretty similar to the Product Details dashboard above, but it contains details of specific customers rather than products. 

4.1) The line chart here has chart-specific filters on it, which means that the chart currently shows the total number of customers over time but can be changed to rather show the revenue per customer over time. This is a great way to enable users to view more information without overcomplicating the dashboard. 

4.2) I also went a bit further here, adding in a little tip I learned from watching Guy in a Cube’s videos, an information panel to make user experience a bit more intuitive.


# 5) Decomposition Tree

   ![Screenshot (6)](https://github.com/user-attachments/assets/da545dfe-2f64-4de9-8a1b-35504fd29951)


This was a last minute add on to the project and I could definitely do with some further exploration of these visualisations but essentially, they allow users to analyse data themselves, across categories and subcategories. 

As can be seen above from the above example, this can be very helpful when analysing things like a breakdown of total revenue, to see which products drive revenue and which category or subcategory they come from. 

# A Final Word

Thank you so much for making it this far and reading my data analysis project! Any feedback you may have would be greatly appreciated - you can reach me on LinkedIn or by email at sarkarpoulami941@gmail.com




         

         
 
