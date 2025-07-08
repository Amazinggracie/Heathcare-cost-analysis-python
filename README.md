# 🩺 Heathcare-cost-analysis-python
Python project analyzing what drives healthcare costs using real-world data

This project explores the drivers behind medical insurance charges using real-world healthcare data (2,700+ patient records). The goal is to deliver actionable business insights that health insurance companies can use to optimize pricing, manage risk, and improve profitability.

This project analyzes medical insurance charges using real-world data to explore:
- What drives healthcare costs?
- How do factors like smoking, age, and BMI influence charges?
- What can health insurers learn from this data?

🔍 **Key Objectives**
- Clean, explore, and analyze the dataset
- Uncover cost-driving patterns in healthcare
- Build and evaluate a regression model
- Translate insights into business-relevant findings

📊 **Dataset**
- Source: [Kaggle - Medical Insurance Price Prediction](https://www.kaggle.com/datasets/harishkumardatalab/medical-insurance-price-prediction)

📁 **Project Structure**
📦 Heakthcare-cost-analysis
├── 📓 medical_insurance_analysis.ipynb
├── 📂 visuals/
│ ├── charges_by_smoking status.png
│ ├── charges_by_region.png
├── 📄 requirements.txt
└── 📜 README.md

📌 **Tools Used**
- Python (Pandas, NumPy, Seaborn, Matplotlib)
- Scikit-learn (for regression model)
- Jupyter Notebook

📈 **Model Evaluation (Linear Regression)**
- MAE: `4177.05`
- MSE: `35,478,021.51`
- RMSE: `5956.34`
- R² Score: `80.69%`

💡 **Business Insight Summary**
- **Smokers pay significantly higher insurance charges** than non-smokers.
- **Southeast region** has the highest average costs, which may impact regional pricing strategies.
- **BMI alone doesn't drive cost**, but combined with smoking, the effect is significant.
- These insights can help insurers improve **pricing models, risk segmentation**, and health promotion efforts.

---

🧠 This project focuses on applying **data analysis skills to solve real-world healthcare problems** — not just to model, but to uncover insights that drive better business decisions.



