# Bank Loan Prediction

## Overview
This project aims to predict whether a loan applicant will be approved for a loan based on various financial and demographic features. It utilizes machine learning techniques to analyze past loan application data and make accurate predictions.

## Dataset
The dataset is sourced from Kaggle: [Loan Approval Prediction Dataset](https://www.kaggle.com/datasets/architsharma01/loan-approval-prediction-dataset/data).

It consists of historical loan application records with features such as:
- **Number of Dependents of the Applicant**
- **Education of the Applicant**
- **Employment Status of the Applicant**
- **Annual Income of the Applicant**
- **Loan Amount**
- **Loan Term in Years**
- **Credit Score**
- **Residential Assets Value**
- **Commercial Assets Value**
- **Luxury Assets Value**
- **Bank Asset Value**
- **Loan Approval Status (Target Variable)**

## Project Workflow
1. **Installing and Importing Dependencies**:
   - `pandas`
   - `scikit-learn`
   - `kagglehub`
   - `warnings`
2. **Data Preprocessing**: Handling missing values, encoding categorical variables, and data normalization.
3. **Model Training**:
   - Decision Tree Classifier
   - Random Forest Classifier

4. **Model Evaluation**: Using accuracy, confusion matrix, and classification report to assess performance.
5. **Hyperparameter Tuning**
   - Hyperparameter tuning using GridSearchCV
6. **Comparative Analysis**: Before and after Hyperparameter Tuning

## Dependencies
To run this project, install the following Python libraries:
```bash
!pip install kagglehub pandas scikit-learn
```

## How to Run
1. Clone the repository:
```bash
git clone https://github.com/harshhmaniya/Bank-Loan-Prediction-98-accuracy.git
```
2. Navigate to the project directory:
```bash
cd Bank-Loan-Prediction-98-accuracy
```
3. Run the Jupyter Notebook:
```bash
jupyter notebook bank_loan_prediction_98_accuracy.ipynb
```

## Results
The model achieves an accuracy of **98.31%** and provides insights into the key factors influencing loan approval.

## Future Improvements
- Deploy the model as an interactive web application.
- Integrate real-time data for better predictions.

## Author
- **Harsh Maniya**  
- [LinkedIn](https://linkedin.com/in/harsh-maniya)
- [GitHub](https://github.com/harshhmaniya)

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
