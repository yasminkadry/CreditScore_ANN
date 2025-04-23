# 🧠 ANN-Based Credit Score Classification

This project applies an **Artificial Neural Network (ANN)** to predict **credit score categories** based on customer demographic and financial data. The model classifies individuals into segments such as **Good**, **Standard**, or **Poor** credit scores.

## 🎯 Project Objective

Build a simple yet effective neural network model using **tabular data** to predict the credit score category of a user based on various input features.

## 💡 Highlights

- Preprocessing and feature scaling
- ANN architecture design and training
- Model evaluation with accuracy, loss plots, and confusion matrix
- Clean and reproducible Jupyter Notebook format

## 🛠 Technologies & Libraries

- Python
- TensorFlow / Keras
- NumPy / Pandas
- Scikit-learn
- Matplotlib / Seaborn

## 📁 Repository Structure

```
ann-credit-score/
│
├── CreditScore_ANN.ipynb     # Main Jupyter Notebook
├── README.md                  # Project overview and instructions
└── dataset/                   # Folder for input dataset (optional)
```

## 🔍 Workflow Overview

1. **Data Exploration & Cleaning**  
   Handle missing values, encode categorical features, scale numeric features.

2. **Model Building**  
   - Input layer based on number of features  
   - Hidden layers with ReLU activation  
   - Output layer with Softmax (for multiclass classification)

3. **Training**  
   Model trained using Adam optimizer and categorical crossentropy loss.

4. **Evaluation**  
   Includes performance metrics and visualizations:
   - Accuracy & loss curves
   - Confusion matrix

## 📈 Sample Results

> Achieved approximately **[Insert Accuracy]%** accuracy on the test set.  
> The ANN model successfully learned meaningful patterns from the dataset and generalized well.

## 🚀 Getting Started

1. **Clone the repo:**
   ```bash
   git clone https://https://github.com/yasminkadry/CreditScore_ANN.git
   ```

2. **Run the notebook:**
   Open `CreditScore_ANN.ipynb` in Jupyter Notebook or JupyterLab.

## 📬 Contact 
Feel free to reach out via  GitHub issues for any questions or improvements.

