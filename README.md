# ANN
Artificial Neural Network (ANN) model built on Bank Churn dataset. Includes data cleaning, MinMax scaling, visualization, ANN training with TensorFlow/Keras, and evaluation using accuracy, classification report, and confusion matrix.
# 🏦 Bank Churn Prediction using ANN  

## 📌 Overview  
This project implements an **Artificial Neural Network (ANN)** to predict **bank customer churn** (whether a customer will leave the bank).  

The workflow covers:  
- Loading and cleaning the dataset  
- Feature scaling with MinMaxScaler  
- Data visualization with scatter plots  
- Splitting data into train and test sets  
- Building and training an ANN using TensorFlow/Keras  
- Evaluating model performance with accuracy, classification report, and confusion matrix  

---

## 🗂️ Project Workflow  

1. **Data Loading & Cleaning**  
   - Imported the Bank Churn dataset into Jupyter Notebook  
   - Handled missing values and encoded categorical variables  

2. **Data Preprocessing**  
   - Applied **MinMaxScaler** to normalize features between 0 and 1  

3. **Exploratory Data Analysis (EDA)**  
   - Visualized feature relationships using **scatter plots**  

4. **Train-Test Split**  
   - Split dataset into **training** and **testing** sets  

5. **Model Building (ANN)**  
   - Imported **TensorFlow** and **Keras**  
   - Defined ANN architecture with input, hidden, and output layers  
   - Used activation functions (ReLU & Softmax/Sigmoid depending on output)  
   - Compiled model with Adam optimizer and appropriate loss function  

6. **Model Evaluation**  
   - Checked accuracy on test data  
   - Generated predictions  
   - Evaluated results using:  
     - **Classification Report** (Precision, Recall, F1-Score)  
     - **Confusion Matrix** visualized with **Seaborn heatmap**  

---

## ⚙️ Tech Stack  

- **Python**  
- **Jupyter Notebook**  
- **TensorFlow / Keras**   
- **Seaborn / Matplotlib**  
- **NumPy, Pandas**  

---

## 📊 Results  

- Accuracy: 85%  
- Detailed classification metrics (precision, recall, F1-score)  
- Confusion matrix visualization  

---

## 🚀 How to Run  

```bash
# Clone the repository
git clone https://github.com/<DevikaYanamala>/<ANN>.git

# Go inside the project folder
cd <ANN>

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter Notebook
jupyter notebook
