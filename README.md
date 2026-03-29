# Modeling Diabetes Progression with Neural Networks

##  Project Overview
This project models the progression of diabetes using the **Diabetes dataset** available in the `sklearn` library.  
The goal is to help healthcare professionals understand how different factors influence diabetes progression and potentially aid in designing better treatment plans and preventive measures.

We use a **simple Artificial Neural Network (ANN)** to predict the target variable (disease progression) based on patient features.

---

##  Objectives
1. **Loading and Preprocessing**
   - Load the dataset from sklearn.
   - Handle missing values (if any).
   - Normalize features for better ANN performance.

2. **Exploratory Data Analysis (EDA)**
   - Understand the distribution of features and target variable.
   - Visualize relationships between features and target.

3. **Building the ANN Model**
   - Design a simple ANN with at least one hidden layer.
   - Use appropriate activation functions.

4. **Training the ANN Model**
   - Split dataset into training and testing sets.
   - Train the model using suitable loss function and optimizer.

5. **Evaluating the Model**
   - Evaluate performance on test data.
   - Report metrics such as Mean Squared Error (MSE) and R² Score.

6. **Improving the Model**
   - Experiment with different architectures, activation functions, and hyperparameters.
   - Report improvements in performance.

---

##  Dataset
- **Source:** `sklearn.datasets.load_diabetes`
- **Features:** 10 independent variables (age, sex, BMI, blood pressure, etc.)
- **Target:** Quantitative measure of disease progression one year after baseline.

---

##  Model Architecture
- Input Layer: 10 features  
- Hidden Layers: Dense layers with ReLU activation  
- Output Layer: Single neuron (regression output)  

---

##  Tools & Libraries
- Python 3.x  
- NumPy, Pandas  
- Matplotlib, Seaborn (for visualization)  
- Scikit-learn (dataset, preprocessing, metrics)  
- TensorFlow / Keras (ANN model building)

---

## 📈 Results
- **Baseline Model:** Achieved MSE and R² score on test data.  
- **Improved Model:** Deeper architecture and tuned hyperparameters improved performance.  

---
