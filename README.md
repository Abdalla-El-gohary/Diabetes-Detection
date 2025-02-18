# Diabetes Detection

This repository focuses on building a machine learning model to detect diabetes using a range of health and lifestyle indicators. The aim is to accurately predict the presence of diabetes based on several features, helping in early diagnosis and preventive healthcare.

## Dataset
We use the following features for diabetes prediction:
- **Gender**: Biological sex of the individual  
- **Age**: Age of the individual  
- **Hypertension**: Presence of high blood pressure (0 = No, 1 = Yes)  
- **Heart Disease**: History of cardiovascular issues (0 = No, 1 = Yes)  
- **Smoking History**: Past or current smoking habits  
- **BMI**: Body Mass Index  
- **HbA1c Level**: Average blood glucose levels over the past 3 months  
- **Blood Glucose Level**: Current blood glucose measurement  
- **Diabetes**: Target variable indicating the presence (1) or absence (0) of diabetes  

## Exploratory Data Analysis (EDA)
Before training the models, we perform a comprehensive Exploratory Data Analysis to:
- Understand the distribution and relationship of features  
- Check for missing values and data imbalances  
- Visualize patterns and correlations among the features  

## Models
We experiment with the following machine learning models:
- **Logistic Regression**: Simple and interpretable linear model  
- **Support Vector Machine (SVM)**: Classifier with the option of using different kernels  
- **Random Forest**: Ensemble model for better generalization and reduced overfitting  
- **Gradient Boosting**: Boosting technique for improving accuracy  
- **k-Nearest Neighbors (k-NN)**: Instance-based learning algorithm  

## Model Evaluation
Each model is evaluated using accuracy as the primary metric. After training and testing, we compare the performances to select the best model.

## Results
The model with the highest accuracy will be selected for the final deployment. The results and insights from EDA and model evaluation will be documented in detail.

## How to Use
1. Clone the repository:  
    ```bash
    git clone https://github.com/Abdalla-El-gohary/Diabetes-Detection.git
    ```
2. Install the required dependencies:  
    ```bash
    pip install -r requirements.txt
    ```
3. Run the notebook or script to explore the data and train the models.

## Contributors
- **Abdalla Elgohary**  
- **Mahmoud Elgendy**


## Contributions
Contributions are welcome! Feel free to open issues or submit pull requests for improvements or new features.


