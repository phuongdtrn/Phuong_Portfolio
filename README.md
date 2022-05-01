## Portfolio
---
### [WebScrape and Detect Food Trends](https://github.com/phuongdtrn/Python-Web-Scraping-Allrecipes)

[![View on GitHub](https://img.shields.io/badge/View_on_GitHub-PURPLE?logo=GitHub)](https://github.com/phuongdtrn/Python-Web-Scraping-Allrecipes)

Food recipe websites is a highly competitive space, where any data that could improve customer satisfaction could give an edge against competitors. In this project, we **webscraped 13,000+ recipes to analyze factors that could contribute to a higher customer satisfaction measured by star ratings from 1 to 5** We pulled various attributes and performed exploratory analysis. 

Tools & techniques: Python (BeautifulSoup), PySpark, Databricks, AWS
![image](https://user-images.githubusercontent.com/77939423/160414750-143e899d-f307-4a64-ae54-90b713e995be.png)

Interesting findings: <br>
• The top rated and most-reviewed recipes tend to belong to the desert category, such as chocolate chip cookies, pancakes, banana bread, muffins
• It's possible that readers tend to gravitate towards recipes with an average cooking time of around 2-2.5 hours.
• Customers were agnostic of nutrition information and are more favorable to websites with high reviews. 
<br>
Improvement: Build a better data pipeline, including creating a table within RedShift, cleaning the table in a staging area, and then feeding the table to Spark for analysis. This would lead to higher scalability than our adhoc analysis.

---
### [Dynamic A/B Testing for Banner Optimization](https://github.com/phuongdtrn/Dynamic-AB-Testing-for-Banner-Optimization)

[![Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=Jupyter)](https://github.com/phuongdtrn/Dynamic-AB-Testing-for-Banner-Optimization/blob/main/Dynamic%20AB%20Testing%20Demo.ipynb)
[![Presentation](https://img.shields.io/badge/Presentation-salmon?)](https://github.com/phuongdtrn/Dynamic-AB-Testing-for-Banner-Optimization/blob/main/Presentation%20Slides.pdf)

A/B testing is largely implemented in the market today to analyze whether or not a business decision needs to be made. Most businesses fail to review and update their "best strategy" on a regular basis** due to a multitude of factors. In this project, we use a banner showing case to demonstrate how business operations can potentially **benefit from continous A/B testing and dynamic strategy choosing**.

Tools & techniques: Big Data, Statistical Analysis, Python

Compared to the traditional A/B testing method, our solution archtecture can:
- Create streaming dashboards to visualize the results
- Constantly review the experiment & adjust setting automatically
- Maximize the profits
- Potential to scale up

**Big Data Architecture**
<img width="899" alt="Screen Shot 2022-05-01 at 11 48 32 AM" src="https://user-images.githubusercontent.com/77939423/166155894-f303b43d-7a8a-48fa-9612-599f00215666.png">

<br>

**Results**:
Our method **achieves 92% of the perfect scenario**, comparing to 83% and 84% of the traditional A/B and show half and half.
<br>
![demo_dashboard.gif](https://github.com/xinbo-w/Dynamic-AB-Testing-for-Banner-Optimization/blob/main/demo_dashboard.gif)

---
### [Predict Ability to Repay Loan](https://github.com/phuongdtrn/Home-Credit-Default-Risk-Prediction)

[![Report](https://img.shields.io/badge/PDF-Report-red?logo=PDF)](https://github.com/phuongdtrn/Home-Credit-Default-Risk-Prediction/blob/main/Project%20WriteUp.pdf)
[![Model](https://img.shields.io/badge/Model-lightskyblue?logo=Python)](https://github.com/phuongdtrn/Home-Credit-Default-Risk-Prediction/blob/main/Final_Code_Home_Credit.ipynb)

Home Credit is an international consumer finance provider, whose goal is to provide a safe experience for people who have little or no credit history. In order to create a positive borrowing experience for the customers, Home Credit utilizes a variety of data attributes to predict a customer’ ability to repay loan. Our goal is to **generate additional meaningful features and perform predictive modeling** to help Home Credit better distinguish between the customers who are loan defaulters vs customers who are not. This will allow Home Credit to maximize successful loan applications that will further empower underserved clients financially

Models: Logistic Regression, RandomForest, XGboost, Adaboost, LightGBM  

We implemented stacking, in which we stacked up Logistic Regression, XGboost, Adaboost, LightGBM and RandomForest as the base estimators using the best parameters from GridSearch and RandomizedSearch. The final estimator is taking the predictions of the previously tuned models as input, flowing through another XGBoost model in order to conduct predictions.
<img width="557" alt="Screen Shot 2022-04-22 at 6 07 35 PM" src="https://user-images.githubusercontent.com/77939423/164815837-309ae1f4-5276-41ab-8c39-3f055752d191.png">

---
### [Visualization](https://public.tableau.com/app/profile/phuong.tran5157)

[![View on Tableau](https://img.shields.io/badge/View_on_GitHub-PURPLE?logo=Tableau)](https://public.tableau.com/app/profile/phuong.tran5157)

Tools & techniques: Tableau, Visualization
![Screen Shot 2022-05-01 at 2 20 56 PM](https://user-images.githubusercontent.com/77939423/166161304-48063321-654a-4578-9eba-9633845f240a.png)


