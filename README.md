# Team Project - Group 23
## Project Team Member
- George Zuo
- Panpan Wang
- Pramod Sharma
- Jingyi Lu

## Team Project - 1 - Regression Analysis [README Link](\README_Team_Project_1.md)

## Team Project - 2 - Data Visualization 

## Project Overview

The objective of this data visualization is to analyze transaction patterns at a coffee shop across different locations, times of day, and product categories. The data set selected by the team is linked below.

The dataset selected by the team is from this [dataset link](https://www.kaggle.com/datasets/ahmedmohamedibrahim1/coffee-shop-sales-dataset).

For this project, we chose to analyze the Coffee Shop Sales dataset from Kaggle, which provides transaction data across various store locations. The unique aspect of this dataset is its potential for creating meaningful visualizations that can uncover trends in consumer behavior, revenue patterns, and location-specific performance. The diversity in store locations and transaction dates allows for a comprehensive analysis of sales trends, making it an excellent candidate for exploring various visualization techniques.

Attribute information:
- Transaction ID: Numerical (Unique identifier for each transaction)
- Transaction Date: Date (Date of the transaction)
- Transaction Time: Time (Time of the transaction)
- Store Number: Numerical (Identifier for the store location)
- Store Location: Text (Location of the store)
- Unit Number: Numerical (Unit number within the store)
- Product Category: Text (Category of the product)
- Product Type: Text (Type of product within the category)
- Product Name: Text (Specific name of the product)
- Price: Numerical (Price of the product)
- Month: Numerical (Month of the transaction)
- Day: Numerical (Day of the month)
- Weekday: Text (Day of the week)
- Hour: Numerical (Hour of the day)

The Coffee Shop Sales dataset provided valuable insights into consumer behavior and store performance across different locations. By employing a variety of visualization techniques, we were able to uncover patterns and trends that might have been missed with basic analysis. The project demonstrates the power of data visualization in making informed business decisions, such as optimizing store operations and targeting promotions to maximize revenue.

## Objectives
The team brainstormed on various parameters before enlisting target objectives which were divided amongst team members in an exclusive manner so that we all can test the whole skillset to clean and evaluate the dataset using a variety of data visualization techniques.

### PART A - George Zou
The visualization aims to uncover trends in customer behavior by visualizing transaction quantities by weekday and hour, as well as comparing performance across different product categories. This analysis will provide insights into peak transaction periods, the popularity of specific product categories, and differences in performance across store locations. 

### PART B – Panpan Wang
The objective of this visualization project is to analyze revenue trends across different months and product categories for a coffee shop. My focus is on identifying top-performing products, understanding their revenue growth patterns, and determining which months contribute the most to overall revenue

### PART C – Pramod Sharma
Analyze and compare day-wise sale trends across the three locations from a revenue and product mix perspective – Pramod Sharma

### PART D – Jingyi Lu
Analyzing sales performance data for a coffee shop, specifically examining transaction quantities of various products. The goal is to derive meaningful insights into customer preferences and product performance

## Analysis
### Part A – George Zou
To achieve the project objectives, I employed two key visualizations:
-	Dual-Axis Plot for Transactions by Weekday and Location
    -	X-Axis: Weekday (Sun to Sat)
    -	Y-Axis (Primary): Transaction count by store location
    -	Y-Axis (Secondary): Total transactions across all locations
    -	 Plot Type: Bar plot for transaction counts per location, and a line plot for the total transactions.
-	Line Plot with Multiple Lines for Transaction by Hour
    -	X-Axis: Hour of the day (6:00 to 20:00)
    -	Y-Axis: Transaction count for each product category
    -	Plot Type: Line plot with separate lines representing Coffee, Tea, Bakery, and Others.

Analysis
-	Transactions by Weekday and Location:
    -	Transaction volumes vary significantly across different weekdays, with certain days (like weekends) having noticeably higher transactions.
    -	The total transactions line shows overall trends and helps identify the busiest days for the coffee shop across all locations.
    -	Individual bar heights allow for a comparison of the performance of each store location, highlighting which store performs best on different days.
-	Transaction by Hour:
    -	Coffee generally sees the highest transaction counts, especially during morning hours, reflecting its popularity as a morning beverage.
    -	Tea and Bakery items show more varied patterns, with some peaks in the late morning and early afternoon.
    -	The "Others" category has lower transaction volumes and more erratic patterns, indicating that these items are less central to the coffee shop's business.

### PART B – Panpan Wang
Data Preparation:
-	The dataset was imported and cleaned, focusing on the product_category, product_detail, Month, and Revenue columns.
-	The data was then aggregated to calculate total revenue by month, product category, and individual products.

Visualization Techniques:
-	Bar Chart: Created to visualize total revenue by month, providing a clear comparison of monthly performance.
-	Heatmap: Used to display the intensity of revenue contributions from different products across each month, highlighting patterns and identifying peak months for specific products.
-	Line Chart: Developed to show how revenue from the top 5 products fluctuated over the months, helping to track trends for specific products over time.

Analysis
-	Monthly Revenue Trends: The analysis revealed that certain months, such as March and May, contributed significantly more to overall revenue, potentially due to seasonal demand.
-	Top Performing Products: The top 5 products by revenue were identified, and their performance was tracked over time. These products showed consistent growth, with some experiencing peak revenue during specific months.
-	Product Category Performance: The heatmap analysis highlighted that certain product categories consistently contributed more to revenue, with coffee and beverages standing out as top earners.

### Part C – Pramod Sharma
Data Cleaning:
-	Removed any missing or incomplete data to ensure accuracy.
-	Converted to a datetime format for accurate time-based analysis.
-	Cleaned the revenue column by removing dollar signs and commas, converting it to a numeric format.

Data Sorting:
-	Sorted the data by to analyze trends over time.
-	Organized the data by store location and day of the week to focus on day-of-week patterns.

Data Preparation:
-	Created a pivot table to aggregate revenue by store location and day of the week.
-	Categorized the weekday column to maintain the natural order of the days.

Feature Engineering:
-	Added features “revenue per transaction” and “average daily sales” to enhance the analysis.

Visualization Techniques Used
-	Heat Map: Visualized the concentration of sales activity across various days and store locations, with color intensity representing revenue levels
-	Stacked Bar Chart: Illustrated the contribution of each store location to the overall revenue on different days of the week.

### Part D – Jingyi Lu
-	The dataset had some limitations, such as single-product orders and ambiguity around "Barista Espresso" (whether it represented multiple shots in one drink or multiple drinks). Besides, it only contained single-product orders, meaning there were no mixed-product purchases within the same transaction.
-	I cleaned the data by treating drinks with multiple shots as a single transaction, which altered the top-selling product rankings. The data was further refined by removing duplicates and irrelevant items like 'flavors' and 'branded' products.

## Conclusions
### Part A – George Zou
-	The visualizations created in this project provide a comprehensive view of transaction patterns at the coffee shop. The key insights include Peak Days and Hours, Location. 
-	Performance, Product Popularity. These insights can inform decisions related to staffing, inventory management, and promotional strategies.

### Part B – Panpan Wang
-	The visualizations provided a clear view of revenue distribution across months and products, with March and May emerging as peak revenue months.
-	The top 5 products demonstrated strong revenue performance, though some showed more consistent growth than others.
-	Product categories like coffee consistently drove revenue, suggesting a strong customer preference for these items.

### Part C – Pramod Sharma
-	The analysis revealed that certain store locations consistently outperformed others, particularly on weekends. The use of a stacked bar chart clearly showed that Lower Manhattan was the top performer in terms of revenue, while Astoria had the lowest. 
-	Additionally, the heat map highlighted peak sales periods, with Friday and Saturday being the busiest days.

### Part D – Jingyi Lu
Three key data visualizations were created:
-	Top 5 Best-Selling Products by Store: The analysis revealed that the sales distribution across the three stores in this dataset was relatively uniform. The top three products were Brewed Chai Tea, Gourmet Brewed Coffee, and Barista Espresso.
-	Distribution of Quantity Sold by the Top 5 Best Sellers: The top three products 
accounted for approximately 12% of sales each, while the fourth and fifth best-sellers each contributed around 9%. The remaining products collectively made up 45% of sales.
-	Sales by Cup Size and Product Category: For the coffee category, small-sized cups were the most popular. In contrast, for tea and drinking chocolate, the popularity among different sizes was not as distinct.

## Video Links

[Part A -- George Zuo](https://youtu.be/GQl3NV-ySR4)

[Part B -- Panpan Wang](https://youtu.be/1X0N8Uuckus)

[Part C -- Pramod Sharma](https://youtu.be/4q4qOBLNybc)

[Part D -- Jingyi Lu](https://www.youtube.com/watch?v=PpMkGkWmwTg)

## Project Folder Structure
```markdown
|-- code (jupyter notebook files)
|-- data
|---- processed
|---- raw (dateset csv files)
|---- sql
|-- reports
|-- src
|-- README.md
|-- .gitignore
```

## Project Approach and Rules of Engagement
Our team approached the project with a structured and collaborative strategy, focusing on leveraging each member's unique skills and interests. Here's a breakdown of how we tackled the project and our team's Rules of Engagement:
Team Approach:
1.	Project Selection and Objectives Setting
    -	We chose the Coffee Shop Sales Dataset from Kaggle because it provides transaction data across various store locations. The unique aspect of this dataset is its potential for creating meaningful visualizations that can uncover trends in consumer behavior, revenue patterns, and location-specific performance.
    -	We set clear objectives for the project. These were divided into four parts (A, B, C, and D) to cover different aspects of the analysis and ensure that each team member had a specific focus area.
2.	Division of Tasks / Objectives
3.	Data Preprocessing
    -	Each member was responsible for cleaning and preprocessing their respective data segments. This included handling missing values, encoding categorical variables, and normalizing data where necessary.
4.	Data visualization techniques 
    -	Each member built and evaluated data visualization techniques specific to their part.
5.	Collaboration and Communication:
    -	We held regular team meetings to discuss progress, share insights, and address any challenges. This ensured that everyone was on the same page and could provide input and support where needed.

## Rules of Engagement
1.	Clear Communication
2.	Defined Roles and Responsibilities
3.	Respect and Support
4.	Regular Updates and Feedback
    -	We provided regular updates on our progress on Slack and gave constructive feedback to help each other.
5.	Time Management
    -	We set deadlines for each phase of the project to ensure timely submission.
6.	We reviewed each other's work to ensure high-quality results and consistency across the different parts of the project.

By dividing the project into manageable parts and working collaboratively with clear guidelines, we were able to effectively analyze the dataset and achieve our project objectives.
