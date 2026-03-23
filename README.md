# Machine-Learning-and-Deep-Learning

## About
This repository contains coursework projects where we applied machine learning techniques to real-world datasets. The work includes both  data analysis and financial modelling, with a focus on understanding patterns in data rather than just building models.

---

## Assignment 1

### What’s included
- 📓 [Notebook](./Assignment%201.ipynb)

### What we did
In this assignment, we explored UK greenhouse gas emissions data using exploratory data analysis (EDA). Instead of relying on built-in functions, we implemented covariance and correlation from scratch to better understand the relationships between emissions, sources, and activities.

We found that emissions are highly unevenly distributed, with a small number of sources (such as power stations and fossil fuels like coal and natural gas) contributing the most. The data also showed a clear long-term decline in emissions, mainly driven by changes in the energy sector.

We then applied clustering techniques (K-means) to group emission sources based on how their emissions changed over time. This required several iterations of preprocessing (normalization, scaling, and filtering), which highlighted how sensitive clustering methods are to data preparation.

---

## Assignment 2

### What’s included
- 📓 [Notebook](./Assignment%202.ipynb)

### What we did
In this assignment, we worked with financial time series data to compare investment strategies between cryptocurrency (Ethereum) and equity (Novo Nordisk).

We started by cleaning and preparing the data, then analyzed returns and volatility over time. We also looked at different market conditions (high vs low volatility), detected unusual events using anomaly detection, and used logistic regression to try to predict next-day returns.

The results showed that both assets are difficult to predict in the short term, with model performance close to random. Ethereum offered higher potential returns but came with much higher volatility, while Novo Nordisk was more stable but had lower returns.

Based on our analysis, a mixed portfolio approach provided a better balance between risk and return than investing in a single asset.

---

## Tools we used
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib / Seaborn  

---

## Authors
Salma Charaf Megrini, Ilinca Sandu, Marcjanna Handke and Helena Valk
