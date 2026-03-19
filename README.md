<p align="center">
<img src="images/banner.png" alt="Project Banner"/>
</p>

# 📊 Will the Customer Accept the Coupon?

## 📌 Overview
This project is part of **Module 5** of the **Berkeley's Professional Certificate in Machine Learning and Artificial Intelligence**.
The objective is to analyze customer behavior and identify the factors
that influence whether a driver accepts a coupon in different driving
scenarios.

The analysis focuses on:
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Hypothesis testing using segmentation
- Identifying key behavioral patterns

## 📂 Dataset
The dataset contains simulated driving situations with features such as:

-   **Demographics**: age, gender, income, occupation
-   **Behavioral patterns**: frequency of visiting bars, coffee houses,
    restaurants
-   **Contextual features**: weather, time of day, passenger type
-   **Target variable**:
    -   `Y` --- coupon accepted (1) or not (0)

## 🎯 Problem Statement
Identify which factors influence coupon acceptance and evaluate the
relative importance of behavioral, demographic, and contextual
variables.

## 📊 Key Results
Some notable insights from the analysis:
- Drivers who visit bars more than once a month are more likely to accept bar coupons
- Younger drivers (under 30) tend to have higher acceptance rates
- Drivers without kids as passengers are more likely to accept coupons
- Lifestyle factors (e.g., frequent restaurant visits) strongly correlate with acceptance

👉 Overall, behavioral patterns outperform demographic features in predicting coupon acceptance.

## 💡 Hypothesis
Customers who:
- frequently engage in social activities (bars, restaurants)
- are younger
- have fewer constraints (e.g., no kids)
are significantly more likely to accept coupons.

## ✅ Conclusion
The analysis demonstrates that contextual and behavioral variables play a crucial role in decision-making.
This insight can be used to:
-improve targeted marketing strategies
-increase coupon conversion rates
-personalize offers based on user behavior

## 🚀 How to Run

``` bash
git clone https://github.com/Rom4ik78/practical_app1.git
cd practical_app1
pip install -r requirements.txt
jupyter notebook
```
## 📎 Project Structure

``` text
├── data/
├── images/
├── prompt.ipynb
├── README.md
└── requirements.txt
```

## 📬 Author
**Roman Andreev**\
📧 roman.andreev@me.com
