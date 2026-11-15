# Sales_Effectiveness_Prediction
Developed a Sales Effectiveness Prediction System using Python and machine learning to classify sales leads into High Potential and Low Potential categories, helping businesses prioritize leads and improve sales follow-up strategies.

## Project Objectives
- Analyze historical sales lead data.
- Perform data cleaning and preprocessing.
- Handle missing values using imputation.
- Perform Exploratory Data Analysis (EDA).
- Identify important patterns in sales leads.
- Build and compare multiple machine learning models.
- Predict High Potential and Low Potential leads.
  
## Dataset Information

The dataset contains historical sales lead information.
**Key features include:**
- Created – Date and time when the lead was created.
- Product_ID – Product associated with the lead.
- Source – Source through which the lead was generated.
- Sales_Agent – Agent responsible for the lead.
- Location – Location associated with the lead.
- Delivery_Mode – Mode of communication or delivery.
- Status – Historical status of the lead.

**Target Variable:**
- High Potential
- Low Potential


## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## Project Workflow
1. Data Collection
2. Data Loading and Inspection
3. Data Cleaning
4. Handling Missing Values (Imputation)
5. Duplicate Removal
6. Exploratory Data Analysis (EDA)
7. Feature Engineering
8. Encoding Categorical Variables
9. Feature Scaling
10. Train-Test Split
11. Model Building
12. Model Evaluation and Comparison
13. Feature Importance Analysis
14. Final Lead Prediction

## Machine Learning Algorithms
Five machine learning algorithms were implemented and compared:
1. Logistic Regression
2. Decision Tree
3. Random Forest
4. K-Nearest Neighbors (KNN)
5. Support Vector Machine (SVM)

The models were evaluated using:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
The best-performing model was selected based on its evaluation results, with particular attention to the F1-score for High Potential leads.

## Key Features
- Sales lead classification.
- High Potential and Low Potential prediction.
- Comparison of five machine learning algorithms.
- Feature importance analysis.
- Model performance evaluation.
- Prediction of new sales leads.

## Results and Evaluation

Five machine learning algorithms were trained and evaluated to identify the most suitable model for classifying sales leads.
The final model was selected based on its performance, especially its ability to identify High Potential leads.
**Evaluation metrics:**
- Accuracy
- Precision
- Recall
- F1-Score
  
## Business Benefits
- Helps sales teams prioritize promising leads.
- Supports more effective follow-up planning.
- Helps analyze lead sources and sales patterns.
- Reduces manual effort in lead classification.
- Supports data-driven sales decisions.

## Limitations
- Predictions depend on the quality of historical data.
- The target categories are based on an assumed mapping of historical statuses.
- The model may not capture every factor influencing lead conversion.
- Predictions should support, not replace, sales-team decisions.

## Future Improvements
- Integrate real-time lead prediction.
- Develop an interactive Streamlit dashboard.
- Include additional customer and sales-related features.
- Retrain the model with updated sales data.
  
## Conclusion
The Sales Effectiveness Prediction project demonstrates how machine learning can support sales lead classification and prioritization. By analyzing historical sales data and comparing five machine learning algorithms, the project identifies a suitable model for predicting High Potential and Low Potential leads. The system can help sales teams improve follow-up strategies and make more informed, data-driven decisions.

## Author
**Ayushman Barik**

GitHub: https://github.com/your-username

---

⭐ If you find this project useful, consider giving the repository a star!
