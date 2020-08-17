# Financial-Fraud-Detection

For my work at OnPoint Insights, I along with my teammate worked on a **Financial Fraud Detection** problem using Python programming language. The data is confidential so we have received the PCA converted variables instead of the regular data.

**Pre-Processing Data:** The financial data consists of 300k rows and 31 variables. Around 98% of the data is fraud records and only 2% is not fraud. The data is highly imbalanced. 

**Data Visualization:** We developed bar plots, distribution plots, box plots, and heat maps to understand the distribution of each variable. We used seaborn and matplotlib to build the plots.

**Data Modeling:** To handle the data imbalance issue, we used the **SMOTE** analysis on the data. We first build an **OLS Regression Model** with an R-square value of 0.66. We analyzed each variable and their importance and performed variable selection for the model. 
We also developed a **Neural Network** and optimized it by changing multiple parameters. Evaluation of the models were done by using AUC-ROC curve and Confusion matrix. 
Later, we implemented a **Random Forest** model and **LightGBM** and evaluated both the models using multiple evaluation metrics. We used various techniques like Feature Importance to develop the best model.

**Results:** We were able to successfully predict the frauds from the data set using our developed predictive models. 

**Python Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scipy, Sklearn, Lightgbm
