Car_Type_Prediction

Author : Prasad Patharvat

IDE: Jupyter Notebook

Language: Python 3

Libraries used : Pandas , Numpy , Sk-learn , Tensorflow , Keras , Seaborn, Matplotlib

Problem Statement:

Problem:

We gave a diffrent cars dataset which having multiple variables . Goal is to predict using other features predict car type

Data:

Overview of the data

Checklist:

• Do we find something wrong in the data?

• Are there ambiguous variables in the dataset?

• Are there variables that should be fixed or removed? Project Summary :

• Performed “Classification Analysis” on Dataset Cars93.

• Type feature is our predicted column and we applied various mathematical test like ANOVA, ChiSquare contingency test, Correlation etc.

• Created EDA function for visualizing data - Univariate & Bivariate Analysis.

• Found we cannot use those columns which contains dot as a column name.

• Applied cross tabulation to find the relationship between the categorical to categorical columns, Also used ChiSquare test for finding all best value. Generally found 2 nd value shows the relationship.

• Some of the values were not in the Standard form. So, preprocessed the data using Standard Scaler for continous and One Hot Encoding for categorical columns.

• Performed all before training the model that is data profiling, data preprocessing, and exploratory data analysis

• Used Logistic Regression was model that was best accuracy model.
