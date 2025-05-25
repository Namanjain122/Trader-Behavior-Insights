# Trader-Behavior-Insights

💹 Sentiment Classification of Financial Data Using Random Forest
📚 Project Overview
This project focuses on classifying financial data based on sentiment using supervised machine learning models. The aim is to predict whether a financial position (trade) is profitable or not profitable using a variety of engineered features, with a particular emphasis on sentiment classification.

The primary models tested include:

Logistic Regression

✅ Random Forest Classifier (Best Performing Model)

📊 Exploratory Data Analysis (EDA)
Boxplots were used to visualize Closed PnL distribution across sentiment classes.

A Kruskal-Wallis H test was conducted to assess statistical differences in PnL across sentiment groups.

The dataset showed imbalanced classes, which was addressed using class_weight='balanced'.

🧠 Model Training
Logistic Regression
Baseline performance

Struggled with non-linearity and class imbalance

✅ Random Forest Classifier
Handled imbalance effectively

Captured complex relationships in data

Provided feature importance scores

📈 Evaluation Metrics
✅ Random Forest Classifier – Performance Report
✅ Accuracy: 100%

🚀 Conclusion: The model performs perfectly on the current dataset — suggesting either an extremely well-separated dataset or a need to validate against unseen or external data to avoid overfitting.

Key Insights
Random Forest outperformed Logistic Regression due to:

Robust handling of non-linear patterns

Class-weight balancing to address skewed data

Ability to evaluate feature importance
