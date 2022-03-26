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
<br/>![](/images/cohort_monthsales.png)
  * Peak hour for people to make orders
<br/>![](/images/cohort_hoursales.png)
  * Top 10 countries by sales value:
<br/>![](/images/cohort_top10.JPG)
* Cohort analysis:
  * Cohort 1: Retention rate
</br>![](/images/cohort_retentionrate.png)
  * Cohort 2: Average quantity sold
</br>![](/images/cohort_average_quantity_sold.png)
  * Cohort 3: Average sales value
</br>![](/images/cohort_average_sales_by_month.png)


## Certificates
Several courses and tests I have completed as of present:
* SQL
  * HackerRank (where I solved basic and intermediate problems)
</br>![](/images/Hackerrank_Intermediate_Cert.png)
