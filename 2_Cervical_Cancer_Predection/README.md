# Cervical Cancer Prediction

This project involves building and training an **XGBoost classifier** to predict the risk of cervical cancer. The dataset used for this project consists of records from **858 patients** collected at the *Hospital Universitario de Caracas* in Caracas, Venezuela. The dataset includes various features such as:

- Number of pregnancies  
- Smoking habits  
- History of sexually transmitted diseases (STDs)  
- Demographics  
- Medical history  

## Key Highlights  
- Conducted **Exploratory Data Analysis (EDA)** and **Data Visualization** on the training dataset.  
- Prepared and split the data into **training** and **test datasets** before model training.  
- Used the **XGBoost algorithm** for training and evaluation, utilizing the `scikit-learn` library in Python.  

### Model Accuracy  
- **Training Dataset Accuracy:** 99.562%  
- **Test Dataset Accuracy:** 97.674%  

<p align="center">  
  <img src="https://i.imgur.com/mvDS5UV.png" width="700"/>  
</p>  

---

## Installation Guide  

To set up the required environment, open your [![Anaconda](https://img.shields.io/badge/Anaconda-342B029.svg?&style=flat&logo=anaconda&logoColor=white)](https://www.anaconda.com/products/individual) prompt and run the following commands:  

```bash
pip install pandas
pip install numpy  
pip install seaborn
pip install plotly
pip install jupyterthemes
pip install --upgrade pip
pip install xgboost
