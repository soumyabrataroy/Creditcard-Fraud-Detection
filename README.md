# Creditcard-Fraud-Detection

We need to find the creditcard frauds using machine learning and deep learning. It is a imbalance dataset and we need to find the proper solution for the same.
You can find the different steps included in the notebook below.

1. **Importing Libraries:**

The script begins by importing several libraries commonly used in data analysis and machine learning tasks:

- `numpy`: This library is used for performing numerical computations on arrays.
- `pandas`: This library is used for data manipulation and analysis.
- `tensorflow`: This library is used for building and training machine learning models.
- `matplotlib.pyplot`: This library is used for creating visualizations and plots.
- `seaborn`: This library is used for creating statistically-informed visualizations.

2. **Data Preprocessing and Feature Engineering:**

The code then performs various data preprocessing and feature engineering steps, including:

- **Data Scaling:** The script uses `StandardScaler` or `RobustScaler` to standardize or robustly scale the data.
- **Dimensionality Reduction:** Techniques like TSNE, PCA, and TruncatedSVD are used to reduce the dimensionality of the data for visualization purposes.
- **Visualization:** The script creates various visualizations to explore the data, including scatter plots, histograms, and boxplots.

3. **Model Training and Evaluation:**

The code then trains and evaluates several machine learning models, including:

- Logistic Regression
- KNears Neighbors
- Support Vector Classifier
- Decision Tree Classifier
- Random Forest Classifier

The script uses various metrics to evaluate the performance of the models, including accuracy, precision, recall, and F1 score.

4. **Imbalanced Data Handling:**

The script acknowledges the potential issue of imbalanced data and explores techniques to address it. It applies both undersampling (NearMiss) and oversampling (SMOTE) techniques to balance the data and improve the performance of the models.

5. **Confusion Matrix and Classification Report:**

The script creates confusion matrices and classification reports for the various models to analyze their performance in more detail.

6. **Neural Network Model:**

The script builds a simple neural network model using Keras and trains it on the data. It then evaluates the performance of the neural network model using metrics such as accuracy and confusion matrix.

7. **Visualization of Confusion Matrices:**

The script creates and displays confusion matrices for both the undersampled and actual data, allowing for a visual comparison of their performance.

Overall, the code snippet demonstrates a comprehensive approach to analyzing and modeling data, including data preprocessing, feature engineering, model training, evaluation, and handling imbalanced data. It provides a good example of how to apply various techniques and tools to gain insights from data and build predictive models.
