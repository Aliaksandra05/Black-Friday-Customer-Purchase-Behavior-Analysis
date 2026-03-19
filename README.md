# <b>RevenueBoost-Demographic-Spending-Optimization</b>

### <b>Project Overview</b>
This project analyzes Walmart's Black Friday transactional data to understand customer spending habits. The primary goal is to determine if gender and other demographic factors significantly impact the purchase amount, helping Walmart make data-driven marketing decisions.

### <b>Key Questions</b>
* **Do women spend more on Black Friday than men?**
* **How do age and city category influence spending?**
* **Can we use Bootstrap Sampling and Confidence Intervals to make statistical inferences about the population?**

## <b>Key Insights</b>

* **Total Revenue:** **$5.1 Billion** total sales with **$865k** avg. spend per customer.
* **The "Power User":** **Males aged 26-35** are the dominant segment, contributing **76.72%** of total revenue.
* **Top Location:** **City B** is the primary revenue hub, accounting for **41.52%** of sales.
* **Statistical Significance:** T-Test results (**p-value < 0.05**) confirm the spending gap between genders is structurally significant.
* **Strategic Focus:** Marketing efforts should prioritize high-engagement age brackets in **City B** to maximize ROI.

<img width="1003" height="547" alt="power_bi" src="https://github.com/user-attachments/assets/0d20088e-5c17-4b8c-863e-37eb13b2420a" />

### <b>Data Description</b>
The company collected the transactional data of customers who purchased products from Walmart Stores during Black Friday. The dataset in walmart_data.csv has the following features:
* **User_ID**
* **Product_ID**
* **Gender - sex of a customer**
* **Age - age in bins**
* **Occupation (masked)**
* **City_Category - category of the city [A, B, C]**
* **Stay_In_Current_City_Years: number of years a customer stays in their current city**
* **Marital_Status**
* **Product_Category (masked)**
* **Purchase - purchase amount**

### <b>Tech Stack</b>
* **Language:** Python
* **Libraries:** NumPy, SciPy (Statistical Testing), Matplotlib/Seaborn (Visualization), Pandas (Data Manipulation)
* **Tools:** Power BI (for executive dashboards)
