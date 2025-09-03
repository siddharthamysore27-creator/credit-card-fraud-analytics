# Credit Card Fraud Detection (ML)

## Project Overview  
This project applies **machine learning** to detect fraudulent credit card transactions.  
Using a dataset of **98,000+ transactions** with fewer than 3% labeled as fraud, we developed an end-to-end pipeline for **data preparation, feature engineering, model training, and evaluation**.  
The final outcome is a **comprehensive fraud detection report** that presents the methodology, model comparisons, and business impact.

---

## Goals  
- Develop a fraud detection pipeline for imbalanced classification  
- Engineer behavioral, temporal, and geographic features to capture fraud patterns  
- Compare multiple machine learning models and select a production-ready solution  
- Quantify the business value of fraud detection through financial evaluation  

---

## Approach  
1. **Data Preparation** → Outlier removal, invalid transaction filtering, targeted imputations  
2. **Feature Engineering** → Transaction velocity, burst detection, entity diversity, geographic distance  
3. **Feature Selection** → Reduced 3,500+ engineered features to the **top 20 predictors**  
4. **Modeling** → Compared Decision Trees, Random Forest, LightGBM, and Neural Networks  
5. **Business Evaluation** → Estimated financial savings from fraud prevention vs. false positives  

---

## Key Results    
- **Neural Network** achieved the highest predictive performance (AUC = 0.637 on out-of-time validation)  
- **Random Forest** selected as the final production model due to consistent performance, stability, and interpretability  
- At a **3% transaction review rate**, the model detected **46.3% of fraudulent activity**  
- Business evaluation showed potential **savings of ~$47.9M annually** by reducing fraud losses and minimizing false positives   

---

## Tech Stack  
- Language: Python
- Libraries: Scikit-Learn, LightGBM, Catboost, Numpy, Pandas, Matplotlib 

---

## Repository Contents
- [Credit_Card_Fraud_Detection.pdf](Credit_Card_Fraud_Detection.pdf): Final project report

---


