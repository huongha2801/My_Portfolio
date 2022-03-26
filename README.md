# Welcome to my page where I posted mini projects!

## Projects:
### Project 1: [Exploratory Data Analysis](https://github.com/huongha2801/EDA_2)
In this project:
* I made use of a publicly available data from Kaggle, which you can find here: [Marketing Campaign](https://www.kaggle.com/datasets/rodsaldanha/arketing-campaign)
* Prepared the data: 
  *  As most datasets shared on Kaggle, the structure of this was clear (the information being presented in a row-and-column format) and did not need much wrangling.
  *  There were few missing values so it was acceptable to drop those from the dataset. 
* Feature-engineered:
  * The dataset had information about the Year of birth of the customers so it was a no-brainer to calculate their age.
  * I also calculated how long the customers had been with the site for further analysis.
  * I summed up the total amount each customer had spent on all categories.
  * I calculated the number of children in each household (by summing up the number of 'kids' and 'teens' provided).
  * I re-categorized the Marital status and Education level for simplicity.
* Conducted univariate and multivariate exploratory analysis of the variables

![](/blob/main/images/Age_distribution.png)
![](/images/Age_distribution.png)
![](/images/Income_distribution.png)
![](/images/Total_spending.png)
![](/images/Sales_value.png)
![](/images/Spending_an_0Education.png)
![](/images/Spending_and_No._of_children.png)
![](/images/Total_spending.png)
![](/images/Spending_and_Offers.png)

### Project 2: [Cohort Analysis](https://github.com/huongha2801/CohortAnalysis_OnlineRetail_ii)
The link to the data can be found here: [Online Retail II UCI](https://www.kaggle.com/datasets/mashlyn/online-retail-ii-uci)
In this project, I:
* Prepared the data:
  * I didnot resolve missing values: As all missing values come from customer IDs, which cannot and shouldn't be estimated or imputed based on other variable, I decided to leave it as it was.
  * I dropped cancelled orders, orders on debt, as well as orders that have quantity less than 0, keeping only meaningful orders.
  * Created new columns for later use: Order month (in which month that order was made); Sales value (by multiplying Quantity with Price) 
* Conducted a light EDA on: 
  * Sales and Month - Which month recorded the best sales?
![](/images/cohort_monthsales.png)
  * Peak hour for people to make orders
![](/images/cohort_hoursales.png)
  * Top 10 countries by sales value:
![](/images/cohort_top10.JPG)
* Cohort analysis:
  * Cohort 1: Retention rate
![](/images/cohort_retentionrate.png)
  * Cohort 2: Average quantity sold
![](/images/cohort_average_quantity_sold.png)
  * Cohort 3: Average sales value
</br>![](/images/cohort_average_sales_by_month.png)

### Project 3: [Brazilian Ecommerce Dashboard with Power BI](https://github.com/huongha2801/powerbi_brazilian_ecommerce)
The dataset was collected from [Kaggle](https://www.kaggle.com/olistbr/brazilian-ecommerce).
* Brief introduction
  * I only downloaded relevant tables, which are the *customer*, *order*, *order items*, *product* and *category name* tables
  * The customer table contains customers' id and information about the customer's state and city
  * The order table contains order ids and various timestamps regarding order's processing (purchased, approved, delivered). This table is linked to the customer table with customer_id.
  * The order_item contain item ids, price, product information and name of the seller
  * The remaining 2 tables give more details about the items' specification.
* Data transformation
  * After joining the above tables, I created new measures and used Power Query to add new columns according to ad hoc needs during the process <br/>
  * New measures include: No. of orders, No. of late orders (and percentage), average shipping time, ... <br/>
  * To calculate the number of late orders, I used actual deliver date and estimated time of delivery to determine which order is late <br/>
  * For average shipping time, the difference between actual deliver date and purchased date was calculated using DATEDIFF function <br/>
  * Further more, throughout the process, there was much need for the date and time columns to be transformed into formats suitable for PowerBI presentation, hence I did make much use of the Editor.  
* How to use it?
  * The slicers allow the end-user to choose their state and city of interest, as well as the period to focus on. <br/>
  * For the <strong>Orders and Late orders</strong> timeseries, the reader can also drill down to such levels as days and weeks.
* What insights can be drawn?
  * Top 5 states with the highest number of orders: Sao Paulo, Rio de Janeiro, Minas Gerais, Rio Grande do Sul & Paraná
  * The capacity to deliver orders quickly improved since Janulary 2017 the period after which saw the total number of orders soaring while that of late orders remain low.
  * During the two-year period, there were as many as 7000 orders delivered late Brazil-wide, this calls for better operation from the Supply side.
  * Most orders (note, to be differentiated with app use, where shoppers browse for products) took place between 10 a.m and 23 p.m.
Making use of the slicers, the reader can gain more insights into the pattern of e-commerce inside each state/city in particular. <br/>
![](/images/Dashboard.JPG)

## Certificates
Several courses and tests I have completed as of present:
* SQL
  * HackerRank (where I solved basic and intermediate problems)
![](/images/Hackerrank_Intermediate_Cert.png)
