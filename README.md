🍷 Red Wine Quality Prediction Using Machine Learning
Predicting wine quality using physicochemical properties — through both regression and classification approaches. 

📌 Problem Statement
In the competitive beverage industry, wine quality significantly impacts customer satisfaction and business growth. However, assessing wine quality based on chemical properties is often subjective and requires expert knowledge. This project leverages machine learning to objectively predict red wine quality using measurable physicochemical attributes — approached both as a regression (predicting numeric quality score) and classification (labeling wine as “Good” or “Bad”) problem.

🎯 Objective
Build and compare two machine learning models to:

Regression Task: Predict wine quality on a continuous scale (0–10).
Classification Task: Classify wine as “Good” (quality ≥ 7) or “Bad” (quality < 7).
This dual approach helps understand how different modeling techniques extract insights from the same dataset and supports real-world decision-making in production and marketing.

🏷 Domain
Data Mining
Food & Beverage Analytics
Machine Learning
💡 Motivation
Practice foundational ML skills in a real-world context.
Gain hands-on experience with both regression and classification workflows.
Explore how predictive models can optimize wine production, quality control, and targeted marketing strategies.
📊 Dataset
Source: UCI Machine Learning Repository — Wine Quality Dataset

Features (11 physicochemical properties):

Fixed acidity
Volatile acidity
Citric acid
Residual sugar
Chlorides
Free sulfur dioxide
Total sulfur dioxide
Density
pH
Sulphates
Alcohol
Target Variable:

quality — Score between 0 and 10 (integer)
🛠 Tools & Technologies
Language: Python
Libraries:
Pandas, NumPy — Data manipulation
Scikit-learn — Machine Learning models & evaluation
Matplotlib, Seaborn — Data visualization
Models Used:
Regression: Linear Regression, Random Forest Regressor
Classification: Logistic Regression, Decision Tree, Random Forest Classifier
Environment: Jupyter Notebook / Google Colab
🔄 Project Workflow
1. 🧹 Data Preprocessing & EDA
Load dataset into Pandas DataFrame
Check and handle missing values (if any)
Perform statistical summaries and visualizations (histograms, boxplots, pairplots)
Analyze feature correlations using heatmaps
Identify key drivers of wine quality
2. 📈 Regression Approach
Treat quality as continuous variable
Train models: e.g., Random Forest Regressor
Evaluate using:
MAE (Mean Absolute Error)
RMSE (Root Mean Squared Error)
R² Score
Extract feature importance to understand key quality influencers
3. 🏷 Classification Approach
Convert quality into binary labels:
“Good” → quality ≥ 7
“Bad” → quality < 7
Train models: Logistic Regression, Decision Tree, Random Forest
Evaluate using:
Accuracy, Precision, Recall, F1-Score
Confusion Matrix
Compare performance across models
4. 💼 Insights & Business Impact
Identify top features influencing quality (e.g., alcohol, sulphates, volatile acidity)
Suggest production adjustments for improving quality (e.g., reduce volatile acidity, increase alcohol content)
Use classification to segment wines for premium vs. standard lines
Enable data-driven QC and marketing decisions
🧠 Key Learnings
✅ Hands-on experience with end-to-end ML workflow
✅ Comparison of regression vs. classification on the same dataset
✅ Importance of EDA, feature correlation, and selection
✅ Practical application of multiple ML algorithms
✅ Real-world relevance in Food & Beverage industry analytics

📝 Conclusion
This project showcases the power of machine learning in transforming raw chemical data into actionable business insights. By approaching wine quality prediction from both regression and classification angles, we gain deeper, more flexible understanding of quality drivers — making it an ideal foundational project for aspiring data scientists.
