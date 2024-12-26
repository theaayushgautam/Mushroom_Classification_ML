# Mushroom_Classification_ML 🍄

### Project Objective 
The goal is to classify mushrooms as edible or poisonous based on their features such as cap shape, cap color, and gill color.
A real-world dataset from Kaggle is used for this purpose.

### 1. Data Loading and Exploration 
Dataset is loaded using Pandas and explored using methods like head(), tail(), shape, and info().
Target variable (class) has two values: e (edible) and p (poisonous).
Checked for null values (none found) and examined column statistics using describe().

### 2. Data Preprocessing 
Categorical data is converted to numerical format using Label Encoding.
Features are stored in X (independent variables) and the target variable in y (dependent variable).

### 3. Dimensionality Reduction with PCA 
PCA (Principal Component Analysis) is applied to reduce the dataset's dimensionality while retaining 85% of the original information.
This helps optimize model training by reducing computational costs.

### 4. Train-Test Split 
The dataset is split into training (80%) and testing (20%) sets using train_test_split from sklearn.

### 5. Model Training 
Multiple machine learning models are trained, including Logistic Regression, K-Nearest Neighbors, SVM, Decision Tree, Random Forest, and Gradient Boosting.

### 6. Model Evaluation 
Models are evaluated using the accuracy_score metric.
Performance comparison helps identify the best model for the task.

### 7. Model Saving and Prediction 
The best-performing model (Random Forest) is retrained on the entire dataset and saved using joblib.
Demonstrated in my Pythob code how to use the saved model to predict whether a mushroom is edible or poisonous.

### 8. GUI Implementation 
A GUI is created using (tkinter library) to allow users to input mushroom features and get classification results in real-time.
