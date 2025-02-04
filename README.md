# ⛽ Fuel Consumption Analysis with Machine Learning 🚗✨

This project analyzes **fuel consumption data** using six different machine learning models: **Linear Regression**, **Random Forest**, **Decision Trees**, **Artificial Neural Networks (ANNs)**, **K-Nearest Neighbors (KNN)**, and **AdaBoost**. It aims to predict fuel efficiency and uncover key factors affecting fuel consumption through data preprocessing, feature engineering, and model evaluation.

---

## 📋 Features

- 📊 **Dataset Exploration**:
  - Loads and explores the dataset, including descriptive statistics and data structure.
  - Handles missing values and performs necessary transformations.

- 🧹 **Data Preprocessing**:
  - Encodes categorical features using **OneHotEncoder** and **OrdinalEncoder**.
  - Scales numerical features with **StandardScaler**.

- 🤖 **Machine Learning Models**:
  - Implements six models for predicting fuel consumption:
    1. **Linear Regression**: A simple and interpretable model for linear relationships.
    2. **Random Forest**: An ensemble learning technique that reduces overfitting and handles nonlinearity well.
    3. **Decision Trees**: A simple yet powerful model for handling categorical and numerical features.
    4. **Artificial Neural Networks (ANNs)**: Advanced models capable of capturing complex nonlinear relationships.
    5. **K-Nearest Neighbors (KNN)**: A distance-based algorithm that makes predictions based on similar instances.
    6. **AdaBoost**: A boosting algorithm that focuses on difficult-to-predict data points.
  - Uses **Grid Search** and **RandomizedSearchCV** for hyperparameter tuning.

- 📈 **Model Evaluation**:
  - Evaluates models using metrics like **Mean Squared Error (MSE)** and **R-squared**.
  - Visualizes feature importance and compares model performance.

---

## 🛠️ Technologies Used

- **Pandas** and **NumPy**: For data manipulation and preprocessing.
- **Matplotlib** and **Seaborn**: For data visualization.
- **Scikit-Learn**: For implementing machine learning models.
- **Artificial Neural Networks (ANNs)**: For advanced prediction models.

---

## 📂 Project Structure

- **`Fuel_Consumption_Ai1Group4.ipynb`**: Jupyter Notebook containing the complete implementation.
- **`dataset.csv`**: The dataset used for fuel consumption analysis.

---

## 🌟 Contributors

- **Sana Araj**
- **Deem Alrashidi**
- **Sahad Adel**
- **Sara Thear**
- **Lama Alhujaili**

---

## 📝 Example Results

### Model Comparison
| Model               | R² Score | MSE       |
|---------------------|----------|-----------|
| Linear Regression   | 0.78     | 10.5      |
| Random Forest       | 0.88     | 7.4       |
| Decision Tree       | 0.80     | 9.6       |
| ANN                 | 0.85     | 8.2       |
| KNN                 | 0.76     | 11.0      |
| AdaBoost            | 0.84     | 8.8       |




