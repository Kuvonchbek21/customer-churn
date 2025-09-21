# customer-churn-
# Project Title: Customer Churn Prediction

This project focuses on analyzing customer data from an E-Commerce  company to predict the likelihood of a customer leaving (churn). The main goal is to identify key factors driving customer churn and to proactively identify at-risk customers, allowing the company to take retention measures.

---

The data used in this project is the [Dataset](https://github.com/anvarnarz/praktikum_datasets/blob/main/E-Commerce-Dataset.csv).

###  Exploratory Data Analysis (EDA)

From the analysis, I found that:

New customers and those who received less cashback are more likely to churn.

Customers who have stayed for a long time and received more cashback tend to remain loyal.

Customers who haven’t made an order for a long time have a higher risk of churn.

Therefore, to reduce churn, the company should:

Pay more attention to new customers,

Strengthen the cashback and bonus system,

Take actions that encourage customers to order more frequently.

---

###  Prediction Model

[Logistic Regression,Decision Tree,Random Forest,XGBoost,] model was trained to predict customer churn.
Using a Decision Tree, the Recall (for those leaving) on the test set is 90%, accuracy score is 95% ,and the F1-score is 87%, which is higher compared to other models and ROC curve is higher as well. Therefore, the Decision Tree was chosen as the primary model for the churn project.

In the project, 83% of customers will retain, indicating a high level of customer loyalty to the company or service. This, in turn, reflects a relatively low churn rate (17%)

---

### 4. How to Run the Project

1.  Clone the repository:
    git clone https://github.com/Kuvonchbek21/customer-churn.git

2.  Install dependencies:
    pip install -r requirements.txt

3.  Launch the notebook:
    jupyter notebook

---

### 5. Technologies Used

* Python: Programming Language
* Pandas & NumPy: For data manipulation
* Matplotlib & Seaborn: For data visualization
* Scikit-learn: For machine learning
* Jupyter Notebook: Project environment

---

* [Kuvonchbek](https://github.com/Kuvonchbek21)

---

### 7. License

This project is licensed under the [MIT License](https://choosealicense.com/licenses/mit/).

---

##  Let's Work Together
If you need help with data analysis, visualization, or building ML models, feel free to reach out.  

Contact me:  
- Email: begimqulovquvonchbek53@gmail.com  
- LinkedIn: [Kuvonchbek Begimkulov](https://linkedin.com/in/kuvonchbek-begimkulov)
