# Breast-cancer-detection

# Objective:
- The primary objective of this project was to build classification models to predict whether a breast tumor is malignant or benign.
- Key steps included data preprocessing, feature scaling, model selection, and evaluation using various performance metrics.

# Data Understanding and Cleanup:
- The dataset contained information about various features related to breast tumors.
- Cleanup involved removing unnecessary columns and ensuring data consistency.

# Exploratory Data Analysis (EDA):
- Conducted EDA to understand the distribution of the target variable (diagnosis) and key features.
- Visualized feature distributions and identified potential insights.

# Preprocessing:
- Applied one-hot encoding to convert the target variable into numerical format.
- Split the data into training and testing sets.
- Applied feature scaling using Min-Max scaling.
- Applied Synthetic Minority Over-sampling Technique (SMOTE) to address class imbalance.

# Model Building and Evaluation:
- Evaluated multiple classification algorithms including Logistic Regression, Decision Trees, Random Forest, and Gradient Boosting.
- Used cross-validation to assess model performance.
- Selected Random Forest, Logistic Regression, and Gradient Boosting based on their median accuracy scores.

# Model Performance Evaluation:
- Evaluated selected models on training and testing datasets using accuracy, precision, recall, and confusion matrices.
- Calculated the Area Under the Receiver Operating Characteristic Curve (AUC-ROC) for each model to assess discrimination between classes.
- All models showed satisfactory performance with AUC scores around 0.97, indicating good discrimination between malignant and benign tumors.

# Conclusion:
- The project successfully developed classification models to predict breast cancer types.
- Random Forest, Logistic Regression, and Gradient Boosting exhibited good performance.
- The models can assist in early detection and decision-making processes related to breast cancer diagnosis.
