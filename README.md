# Telco Customer Churn Prediction

End-to-end machine learning project predicting customer churn for a telecommunications company.

## Project Overview

This project analyzes customer data and builds predictive models to identify customers likely to churn (leave the service). The goal is to help businesses take proactive retention measures.

## Objective

Predict which customers will churn based on their demographics, services, and account information.

## Dataset

- **Source:** Kaggle - Telco Customer Churn
- **Size:** ~7,000 customers
- **Features:** 21 variables including demographics, services, and billing info

## Technologies Used

- Python 3.13.5
- Pandas & NumPy (data manipulation)
- Matplotlib & Seaborn (visualization)
- Scikit-learn (machine learning)
- Jupyter Notebook

## Models Used

- Logistic Regression
- Random Forest Classifier

## Results

- **Best Model:** Random Forest
- **ROC-AUC Score:** 0.82
- **Key Insights:**
  - Month-to-month contracts have highest churn rate
  - ChargesPerServices is the strongest predictor
  - Fiber optic customers churn more than DSL

## How to Run

1. Clone this repository
2. Download dataset from [Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
3. Install requirements: `pip install pandas numpy matplotlib seaborn scikit-learn`
4. Open and run the Jupyter notebook

## Key Findings

1. **Contract Type:** Month-to-month contracts show  higher churn
2. **Customer Tenure:** New customers are highest risk  
3. **Payment Method:** Electronic check users churn at higher rates

## 💡 Business Recommendations

- Incentivize long-term contracts with discounts
- Focus retention efforts on customers in first year
- Bundle tech support with all plans
- Encourage automatic payment methods

## 👨‍💻 Author

Azada Imranzada

---

⭐ If you found this helpful, please star the repository!
```

20. **Save the file** in VS Code

---

## **Step 9: Upload the README**

21. Go back to **GitHub Desktop**
22. You should automatically see `README.md` appear in the "Changes" list on the left
23. In the **Summary** box, type:
```
    Add README documentation
```
24. Click **"Commit to main"**
25. Click **"Push origin"** button (top right area)

**Wait a moment for it to upload...**

26. Go back to your GitHub page and **refresh**
27. You should now see your beautiful README displayed!

---

## **Step 10: Handle Large Files (If Needed)**

**If you get an error about the CSV file being too large:**

28. In your project folder, create a file called `.gitignore`
29. Add this content:
```
    # Data files
    *.csv
    *.xlsx
    
    # Python
    __pycache__/
    *.py[cod]
    .ipynb_checkpoints/
    
    # VS Code
    .vscode/
