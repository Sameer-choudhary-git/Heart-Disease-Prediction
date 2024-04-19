# Heart Disease Prediction
This repository contains code for predicting the risk of developing heart disease using machine learning techniques. The dataset used for training and testing the model is from the Framingham Heart Study.

# Overview
Heart disease is one of the leading causes of death worldwide. Early detection and prediction of heart disease risk can help in preventive healthcare and personalized treatment strategies. This project aims to build a predictive model that can assess the 10-year risk of developing coronary heart disease (CHD) based on various risk factors.

# Dataset
The dataset used in this project is sourced from the Framingham Heart Study and is available in the framingham.csv file. It contains demographic information and medical measurements of individuals, along with their 10-year risk of CHD.

# Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

# Usage
1) Clone the repository to your local machine:
```
git clone https://github.com/Sameer-choudhary-git/Heart-Disease-Prediction.git
```
2) Install the required dependencies:
```
pip install pandas numpy scikit-learn matplotlib seaborn
```
3) Run the Jupyter Notebook **heart_disease_predictor.ipynb** to train the model and evaluate its performance.

# Model Evaluation
The predictive model is evaluated based on its accuracy in classifying individuals into high and low risk categories for CHD. Additionally, a confusion matrix is generated to visualize the performance of the model.

# Conclusion
The developed model achieves an accuracy of **approximately 85%** in predicting the 10-year risk of CHD. Further optimization and refinement of the model could enhance its predictive performance.
