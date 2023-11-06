# Bank_Churn
The objective of this project is to create a model to detect customers who may churn.

The data for this project was sourced from Kaggle. In this analysis, we will leverage popular Python libraries such as NumPy, Pandas, and Scikit-Learn for data preprocessing and model creation. For visualization, we will utilize Seaborn and Matplotlib.

The dataset consists of a total of 20 columns and 10,127 samples. The primary target variable for prediction is 'Attrition_Flag.'

Our project workflow begins with an initial data exploration phase. We will create various graphical representations to gain insights into the distributions of each column and their relationships with the target variable.

Next, we will delve into understanding the relationships between different variables through a correlation matrix.

To prepare the data for modeling, we will apply custom data preprocessing techniques using a function called `pre_processing()`.

Subsequently, we will partition the data into training, validation, and testing subsets.

We will proceed to build a function named `model_eval()` for the evaluation of models. This function will enable us to optimize models using grid search and cross-validation based on the F1 score. The models under consideration for optimization include Logistic Regression, Random Forest, XGBoost, and Support Vector Machine (SVM).

Once the best combination of hyperparameters is determined, we will assess the selected models using a function named `results_eval()`. This function will generate a graphical representation with a ROC curve, AUC (Area Under the Curve), and F1 score for the testing set.

To conclude, we will delve into the identification of the most influential columns for predicting churn and explore how these features impact the 'Attrition_Flag.'

In the final phase, we will discuss the potential limitations and areas where the model may exhibit shortcomings during the prediction process.

This project represents a comprehensive data analysis and predictive modeling endeavor, aimed at understanding and addressing customer churn within a financial services context.
