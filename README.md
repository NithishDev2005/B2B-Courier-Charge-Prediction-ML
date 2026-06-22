# Preliminary Analysis of B2B Courier Charge Accuracy Using ML

A Machine Learning-based approach to analyze, predict, and validate B2B courier charges to improve billing transparency and reduce discrepancies in logistics operations.

---

## 📌 Project Overview

In B2B logistics, accurate estimation of courier charges is essential for cost control, operational efficiency, and maintaining trust between logistics providers and business clients. Traditional pricing approaches often fail to handle dynamic pricing factors and complex relationships between shipment characteristics.

This project uses Machine Learning techniques to predict courier charges based on historical shipment data and identify discrepancies between predicted and actual charges. The study demonstrates how data-driven approaches can support automated charge validation and cost optimization in logistics systems.

---

## 🎯 Objectives

- Analyze historical B2B courier shipment data.
- Identify factors influencing courier pricing.
- Develop machine learning models for courier charge prediction.
- Compare predicted charges with actual billed amounts.
- Detect discrepancies in courier billing.
- Improve cost optimization and pricing transparency.

---

## 📂 Repository Structure

```
B2B-Courier-Charge-Prediction-ML/
│
├── README.md
├── .gitignore
├── data/
│   └── courier_data.csv
├── notebooks/
│   └── courier_charge_analysis.ipynb
├── documentation/
│   └── Final_Report.pdf
├── progress_reports/
│   └── Review.pdf
├── deliverables/
│   ├── Final_Presentation.pdf
│   └── Final_Presentation.pptx
└── publications/
    ├── Acceptance_Letter.pdf
    ├── Research_Paper.pdf
    └── Publication_Details.md
```

---

## 📊 Dataset Information

The project utilizes historical B2B courier shipment data containing features such as:

- Shipment Weight
- Delivery Distance
- Service Type
- Carrier Information
- Actual Courier Charges

The dataset was divided into:

- **Training Set:** 80%
- **Testing Set:** 20%

---

## ⚙️ Technologies Used

### Programming Language
- Python

### Libraries
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

### Development Environment
- Jupyter Notebook
- Google Colab

---

## 🤖 Machine Learning Models Used

- Linear Regression
- Support Vector Regression (SVR)
- Decision Tree Regressor
- Random Forest Regressor

---

## 📈 Model Performance

| Model | MAE | RMSE | R² Score |
|---------|------|-------|-----------|
| Linear Regression | 24.36 | 31.12 | 0.78 |
| Support Vector Regression | 19.85 | 25.47 | 0.84 |
| Decision Tree Regressor | 16.92 | 21.34 | 0.88 |
| Random Forest Regressor | 12.47 | 17.56 | 0.92 |

### Best Performing Model

🏆 **Random Forest Regressor**

- Highest prediction accuracy
- Lowest prediction error
- Better handling of non-linear relationships
- Improved billing discrepancy detection

---

## 🔍 Key Outcomes

- Automated courier charge validation.
- Identification of billing discrepancies.
- Improved pricing transparency.
- Cost optimization insights.
- Data-driven decision-making support for logistics operations.

---

## 📚 Research Publication

This mini project resulted in an accepted research publication.

### Paper Title

**Preliminary Analysis of B2B Courier Charge Accuracy Using ML**

### Conference

**ICICCS-2026**

### Publication Status

✅ Accepted after peer review.

Publication-related documents are available in the `publications` folder.

---

## 👨‍💻 Team Details

**Batch ID:** 23MPCS-H20

| Roll Number | Name |
|-------------|-------|
| 23881A05FP | Jupelli Harika |
| 23881A05GK | Paluvai Nithish Kumar |
| 24885A0552 | Muddam Pranay |

---

## 👩‍🏫 Guide Details

**Ms. Mahankali Saritha**  
Assistant Professor  
Department of Computer Science and Engineering  
Vardhaman College of Engineering

---

## 🎓 Institution

**Vardhaman College of Engineering**  
Department of Computer Science and Engineering

---

## 📌 Conclusion

This project demonstrates that Machine Learning techniques can effectively improve the accuracy of B2B courier charge prediction and validation. The proposed approach reduces billing discrepancies, enhances transparency, and provides a foundation for intelligent logistics pricing systems.
