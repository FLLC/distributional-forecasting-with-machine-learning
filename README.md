# Quantile Regression Forest – Distributional Modeling in Econometrics

This repository contains the code and report for our **Machine Learning in Econometrics** course assignment.  
The goal of the project is to build a *distributional predictive model* — estimating the full conditional distribution of real income (`p(y|x)`) rather than just its expected value.

---

## 📊 Project Overview

We implemented a **Quantile Regression Forest (QRF)** model to predict the distribution of real income using data from the **General Social Survey (GSS)**.  
The QRF approach provides a non-parametric, flexible way to estimate conditional quantiles, making it well-suited for skewed and heteroskedastic data.

Our final model achieved a strong calibration and low CRPS (Continuous Ranked Probability Score), indicating accurate distributional predictions.

Key features modeled include:
- Year of survey  
- Age  
- Occupation code  
- Occupational prestige score  
- Education level  
- Marital status  
- Work status  
- Gender  

---

## 🧠 Repository Contents

---

## ⚙️ Data Availability

The dataset used in this project **cannot be shared publicly** due to **University restrictions**.  
However, it can be retrieved directly from the official **General Social Survey (GSS)** website:  
🔗 [https://gss.norc.org/](https://gss.norc.org/)  
or obtained through the **Canvas assignment page** associated with this course.  

The data files required to reproduce the results are:
- `X_trn.csv`  
- `y_trn.csv`  
- `X_test.csv`  

These should be placed locally in a `data/` folder when running the notebook.

---

## 🧑‍🎓 Authors

**Group 27 – Erasmus University Rotterdam**  
**Course:** FEM21045 – Machine Learning in Econometrics  

- Ferran Llorca Mataix  
- Yan van Snippenburg  
- Emre Cekin  
- Danyl Sol  

---
