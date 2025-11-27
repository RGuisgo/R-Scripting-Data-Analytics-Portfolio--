# African Climate Trend Analysis & Forecasting – Bayesian Models (R)

## 📌 Overview
This project examines trends and forecasts of yearly **temperature and rainfall** in ten African countries across West, South, East, and North Africa (Ghana, Nigeria, Senegal, South Africa, Namibia, Rwanda, Ethiopia, Madagascar, Egypt, Tunisia) using **Bayesian Autoregressive (AR(1))** and **Random Walk (RW(1))** models.  

- **Objective:** Compare model performance and generate projections for temperature and rainfall.  
- **Models Used:** Bayesian Autoregressive (AR(1)) and Random Walk (RW(1))  
- **Evaluation Metrics:** Deviance Information Criterion (DIC) and Watanabe-Akaike Information Criterion (WAIC)  

---

## 🔍 Key Findings
- **Temperature Data:** Random Walk model provided better fit across all countries.  
- **Rainfall Data:** Autoregressive model outperformed Random Walk model.  
- **Forecasting Patterns:**  
  - AR model forecasts indicate a **downward trend** in temperature for most countries.  
  - RW model forecasts align with recent trends but have **wider credible intervals**, reflecting higher uncertainty.  
- **Implications:** Temperature is expected to decrease, while rainfall trends largely follow historical observations.  

---

## 📁 Repository Contents
- **Thesis Document:** Main PDF with full methodology, results, and discussion.  
- **Supplementary Materials:**  
  - Datasets used in the analysis  
  - R scripts for data processing and model implementation  
  - Visualizations and charts  

---

## 🛠️ Tools
- **Language:** R  
- **Packages:** tidyverse, coda, rstan, ggplot2  

---

## ▶️ How to Run
1. Open the relevant R scripts in RStudio.  
2. Execute scripts sequentially to reproduce data cleaning, model estimation, and visualization.  
3. Output includes forecast plots, credible intervals, and model comparison metrics.  

---

## 📌 Citation
If you reference or use this work, please cite as:  
**Rebecca Efua Guisgo**, *"Trend analysis and forecasting of yearly temperature and rainfall in some African countries using Bayesian Autoregressive and Random Walk models."*  

---

## 📫 Contact
For questions or collaborations, reach out:  
- **Email:** rguisgo@gmail.com
