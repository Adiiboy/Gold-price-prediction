🥇 Gold Price Prediction — Machine Learning
A machine learning project that predicts gold prices using historical financial data. Built using Python, Scikit-Learn, and data analysis libraries.

🎯 Objective
Gold prices are influenced by multiple financial indicators like stock indices, oil prices, and currency exchange rates. This project builds a predictive ML model to forecast gold prices based on these features.

📁 Files in this Repository
FileDescriptionUntitled3.ipynbJupyter Notebook with full ML pipeline — EDA, model training & evaluationgld_price_data.csvHistorical gold price dataset with financial indicators

📊 Dataset Features
The dataset includes key financial indicators such as:
FeatureDescriptionSPXS&P 500 IndexGLDGold ETF Price (Target Variable)USOOil ETF PriceSLVSilver ETF PriceEUR/USDEuro to USD Exchange Rate

🤖 ML Workflow

Data Loading & Exploration — shape, info, missing values, statistics
Correlation Analysis — heatmap to find feature relationships
Feature Selection — selecting relevant predictors
Model Training — Random Forest Regressor
Model Evaluation — R² Score, actual vs predicted comparison


🛠️ Tools & Libraries
python
pandas
numpy
Scikit Learn
Matplotlib
seaborn
Jupyte


📈 Model Performance
MetricScoreAlgorithmRandom Forest RegressorEvaluationR² ScoreTrain/Test Split80% / 20%

🚀 How to Run
bashgit clone https://github.com/Adiiboy/Gold-price-prediction
cd Gold-price-prediction
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
jupyter notebook Untitled3.ipynb

💡 Key Learnings

How financial indicators correlate with gold prices
Building and evaluating a Random Forest regression model
Feature importance analysis
Data visualization for financial datasets
