# 🛒 Demand Forecasting Analysis  

## 📌 Project Overview  
This project focuses on **demand forecasting** using a historical sales dataset (2013–2017) collected from Kaggle.  
The goal is to build a reliable forecasting model and provide insights to help businesses optimize **inventory, resource allocation, and profitability**.  



---<img width="1327" height="746" alt="demand_forecasting_dashboard" src="https://github.com/user-attachments/assets/a31c8a8d-a922-488d-b7ab-091495063f60" />



## 📂 Repository Structure  
├── notebooks/ # Jupyter notebooks (EDA, Model building,report)
│ └── EDA.ipynb
├── dashboard/ #demand_forecasting_dashboard
│ └── Prediction.pbix
├── presentations/ # Sales pitch / dashboard presentations
│ └── Sales Pitch Presentation.pptx
└── README.md # Project description


---
## 🔎 Data Details  
- **Source:** Kaggle Sales Dataset (2013–2017)  
- **Rows:** 913,000 entries  
- **Columns:**  
  - `date` → daily sales timeline  
  - `store` → store identifier (1–10)  
  - `item` → product/item identifier (1–50)  
  - `sales` → daily sales values  

Forecast generated for **2018**.

---
## 📊 Exploratory Data Analysis (EDA)  
- 📈 **Seasonality:** Clear peaks in festive/high-demand months, dips in off-season  
- 🏪 **Top Stores:** Store 2 and Store 8 are best performers  
- 📦 **Top Items:** Item 15 and Item 28 dominate sales  
- 📅 **Day-of-Week Effect:** Weekends drive higher sales than weekdays  

---

## 🤖 Model Building  
- **Algorithm:** Random Forest Regressor  
- **Baseline:** Yesterday’s sales = today’s sales  
- **Performance:**  
  - R² = **0.93**  
  - MAE = **6.25**  
  - RMSE = **8.14**  
  - MAPE = **12.87%**  

✅ Random Forest reduced error by ~45–50% compared to the baseline.  

---

## 📈 Business Value  
- 📦 **Optimize Inventory** → minimize stockouts & reduce excess stock  
- 👥 **Resource Allocation** → direct manpower & marketing to high-demand periods  
- 😀 **Customer Satisfaction** → ensure availability during peak demand  
- 💰 **Increase Profitability** → focus on top stores & products  
- 📊 **Data-Driven Decisions** → reliable forecasts for short-term & long-term planning  

---

## 🚀 How to Use  
1. Clone this repo or download ZIP  
2. Open `notebooks/EDA.ipynb` in Jupyter Notebook  
3. Install dependencies (pandas, numpy, matplotlib, seaborn, scikit-learn)  
4. Run all cells to reproduce EDA, modeling, and forecasts  

---

## 📫 Connect with Me  
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-blue?style=for-the-badge&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/harsh-chauhan-sh)  [![Gmail](https://img.shields.io/badge/-Gmail-red?style=for-the-badge&logo=Gmail&logoColor=white)](mailto:har05sh03@gmail.com)  [![GitHub](https://img.shields.io/badge/-GitHub-black?style=for-the-badge&logo=github&logoColor=white)](https://github.com/harshchauhan-analytics05)  

---

✨ *Turning raw data into foresight — enabling smarter, faster, and profitable business decisions.*  
