<h1 align="center"> Titanic Survival Prediction⛴</h1>

- Load the Titanic dataset, and preprocess it by handling missing values, encoding categorical features, and extracting relevant features.
- Conduct EDA to understand data distributions, correlations, and insights that can guide feature selection and preprocessing.
- Standardize features using Min-Max scaling or StandardScaler to ensure consistent scales for classifiers like **KNN** and **SVC**.
- Apply Synthetic Minority Over-sampling Technique **(SMOTE)** to balance the dataset, improving the predictive performance, especially for the minority class (survived).
- Use PCA to reduce the dimensionality of the dataset while retaining important information, especially useful for high-dimensional datasets.
- Train **K-Nearest Neighbors (KNN)**, **Support Vector Classifier (SVC)**, **Decision Tree Classifier**, and **Random Forest Classifier** using the preprocessed data.
- Tune hyperparameters for each classifier using techniques like Grid Search or Random Search to find the optimal settings for better model performance.
- Evaluate each model using appropriate evaluation metrics such as accuracy, precision, recall, F1-score, and confusion matrix.
- Compare the performance of KNN, SVC, Decision Tree, and Random Forest classifiers to determine the most effective model for Titanic survival prediction.
