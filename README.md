# Titanic-Survival-Prediction
Titanic Survival Prediction 
Objective
The goal of this project is to build a machine learning model to predict whether a passenger survived the Titanic disaster based on features such as age, gender, ticket class, fare, and cabin information.
________________________________________
Project Structure
├── README.md                          # Main notebook with full implementation
├── titanic-survival-prediction.ipynb  # Project documentation
├── requirements.txt                   # Python dependencies
└── titanic.xlsx                       # Dataset file
________________________________________
Steps to Run the Project
1.	Clone the repository:
git clone https://github.com/Abhi2122/Titanic-Survival-Prediction.git
cd titanic-survival-prediction
2.	Install dependencies:
pip install -r requirements.txt
3.	Download dataset:
Dataset can be downloaded from Kaggle - Titanic Dataset.
4.	Run the notebook:
Open titanic-survival-prediction.ipynb in Jupyter Notebook / VSCode / Google Colab and run all cells.
________________________________________
Project Highlights:
•	Handled missing values in Age, Embarked, and Cabin columns.
•	Encoded categorical variables: Sex, Embarked, Pclass.
•	Applied normalization to numerical features.
•	Tried various models: XGBoost, Logistic Regression, Decision Tree, Random Forest.
•	Evaluated using accuracy, precision, recall, F1-score.
•	Achieved 82% accuracy with XGBoost model.
________________________________________
 Model Selection
In this project, multiple classification algorithms were tested to determine the most effective model for predicting Titanic survival:
1.	Logistic Regression 
o	A baseline linear model suitable for binary classification.
2.	Naive Bayes 
o	Simple probabilistic classifier based on Bayes theorem.
3.	Decision Tree Classifier 
o	Tree-based model capable of capturing non-linear relationships.
4.	Random Forest Classifier 
o	Ensemble model using multiple decision trees to reduce overfitting.
5.	Support Vector Machine (SVM) 
o	Effective in high-dimensional spaces.
6.	Linear Discriminant Analysis (LDA) 
o	Linear classifier with dimensionality reduction.
7.	XGBoost Classifier 
o	Advanced boosting algorithm that improves accuracy and reduces bias.
________________________________________
Model Selection Process:
•	Data Preprocessing: 
o	Handled missing values, encoded categorical variables, normalized numerical data.
•	Evaluation Metrics: 
o	Accuracy, Precision, Recall, and F1-score were used to compare model performance.
•	Final Model Choice: 
o	After evaluating all models, XGBoost Classifier was selected due to its superior balance of accuracy and F1-score.
________________________________________

________________________________________
Performance Summary:
Model	                Accuracy  Precision	Recall	F1-score
XGBoost	              0.8212	  0.8000	  0.7568	0.7778
Random Forest	        0.8156	  0.8361	  0.6892	0.7556
Spport Vector Machine	0.8156	  0.8060	  0.7297	0.7660
Logistic Regression	  0.8101	  0.7857	  0.7432	0.7639
Decision Tree	        0.7989	  0.8276	  0.6486	0.7273
LDA	                  0.7933	  0.7681	  0.7162	0.7413
Naive Bayes	          0.7710	  0.7200	  0.7297	0.7248
