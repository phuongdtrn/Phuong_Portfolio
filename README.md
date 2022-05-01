# Portfolio

## [Allrecipes Webscraper Data Pipeline](https://github.com/phuongdtrn/Python-Web-Scraping-Allrecipes)
Food recipe websites is a highly competitive space, where any data that could improve customer satisfaction could give an edge against competitors. In this project, we webscraped 13,000+ recipes to analyze factors that could contribute to a higher customer satisfaction measured by star ratings from 1 to 5. We pulled various attributes and performed exploratory analysis. 
#### Tools & techniques: Python (BeautifulSoup), PySpark, Databricks, AWS

#### Interesting findings:
- The top rated and most-reviewed recipes tend to belong to the desert category, such as chocolate chip cookies, pancakes, banana bread, muffins
- It's possible that readers tend to gravitate towards recipes with an average cooking time of around 2-2.5 hours.
- Customers were agnostic of nutrition information and are more favorable to websites with high reviews. 

![image](https://user-images.githubusercontent.com/77939423/160414750-143e899d-f307-4a64-ae54-90b713e995be.png)

Improvement: Build a better data pipeline, including creating a table within RedShift, cleaning the table in a staging area, and then feeding the table to Spark for analysis. This would lead to higher scalability than our adhoc analysis.


## [Dynamic A/B Testing for Banner Optimization](https://github.com/phuongdtrn/Dynamic-AB-Testing-for-Banner-Optimization)
A/B testing is largely implemented in the market today to analyze whether or not a business decision needs to be made. Most businesses fail to review and update their "bes strategy" on a regular basis due to a multitude of factors. In this project, we use a banner showing case to demonstrate how business operations can potentially benefit from continous A/B testing and dynamic strategy choosing.
#### Tools & techniques: Big Data (Spark Streaming, SparkSQL, Hive, Statistical Analysis, Python)

#### Dynamic A/B Testing Framework
<img width="923" alt="Screen Shot 2022-05-01 at 11 48 13 AM" src="https://user-images.githubusercontent.com/77939423/166155873-4d396ba0-d17d-4a74-aa13-60b8cde9713b.png">

Compared to the traditional A/B testing method, our solution archtecture can:
- Create streaming dashboards to visualize the results
- Constantly review the experiment & adjust setting automatically
- Maximize the profits
- Potential to scale up

#### Big Data Architecture
<img width="899" alt="Screen Shot 2022-05-01 at 11 48 32 AM" src="https://user-images.githubusercontent.com/77939423/166155894-f303b43d-7a8a-48fa-9612-599f00215666.png">

#### Results
Our method achieves 92% of the perfect scenario, comparing to 83% and 84% of the traditional A/B and show half and half.

![demo_dashboard.gif](https://github.com/xinbo-w/Dynamic-AB-Testing-for-Banner-Optimization/blob/main/demo_dashboard.gif)


## [Home Credit Default Risk Prediction](https://github.com/phuongdtrn/Home-Credit-Default-Risk-Prediction)
Home Credit is an international consumer finance provider, whose goal is to provide a safe experience for people who have little or no credit history. In order to create a positive borrowing experience for the customers, Home Credit utilizes a variety of data attributes to predict a customer’ ability to repay loan. However, there are still many untapped data sources that could be employed to help Home Credit better serve its customers. By having a full understanding of its data, Home Credit could guarantee that the clients’ ability to repay is not rejected and that loans are granted with principal and maturity.
#### Tools & techniques: Predictive Modeling, Python

### Methodology Overview
<img width="624" alt="Screen Shot 2022-04-22 at 6 02 27 PM" src="https://user-images.githubusercontent.com/77939423/164815453-0af69366-53c0-4307-988f-d19e2bbd0aa9.png">

### Model Building
We implemented stacking, in which we stacked up Logistic Regression, XGboost, Adaboost, LightGBM and RandomForest as the base estimators using the best parameters from GridSearch and RandomizedSearch. The final estimator is taking the predictions of the previously tuned models as input, flowing through another XGBoost model in order to conduct predictions.
<img width="557" alt="Screen Shot 2022-04-22 at 6 07 35 PM" src="https://user-images.githubusercontent.com/77939423/164815837-309ae1f4-5276-41ab-8c39-3f055752d191.png">

### Results
There is a 76.4% likelihood that our predictive model will better distinguish between the customers who are loan defaulters vs customers who are not.
Deploying this model gives Home Credit better decisive power when it comes to loan application acceptances or rejections. In line with their goal to support their clients through responsible loan grants, being able to better distinguish clients with the ability to pay will allow Home Credit to
maximize successful loan applications that will further empower underserved clients financially. Reducing unnecessary rejections will also help foster the relationship between Home Credit and their retailers by improving the overall client experience.


## [Dashboards](https://public.tableau.com/app/profile/phuong.tran5157)
#### Tools & techniques: Tableau, Visualization
![Screen Shot 2022-05-01 at 2 20 56 PM](https://user-images.githubusercontent.com/77939423/166161304-48063321-654a-4578-9eba-9633845f240a.png)


