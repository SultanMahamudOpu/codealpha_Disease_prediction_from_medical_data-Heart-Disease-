# Heart Disease Prediction - Machine Learning Project

## 🎯 Objective
Predict the possibility of heart disease based on patient medical data using multiple classification algorithms and cross-validation techniques.

## 📊 Dataset
The `heart.csv` dataset contains 1025 patient records with 13 medical features:
- **age**: Age of the patient
- **sex**: Gender (1 = male, 0 = female)
- **cp**: Chest pain type (0-3)
- **trestbps**: Resting blood pressure
- **chol**: Serum cholesterol level
- **fbs**: Fasting blood sugar > 120 mg/dl
- **restecg**: Resting electrocardiographic results
- **thalach**: Maximum heart rate achieved
- **exang**: Exercise induced angina
- **oldpeak**: ST depression induced by exercise
- **slope**: Slope of the peak exercise ST segment
- **ca**: Number of major vessels colored by fluoroscopy
- **thal**: Thalassemia type
- **target**: Heart disease presence (0 = no disease, 1 = disease)

## 🤖 Machine Learning Algorithms
This project implements and compares four different classification algorithms:

1. **Logistic Regression** - Linear probabilistic classifier
2. **Support Vector Machine (SVM)** - RBF kernel for non-linear classification
3. **Random Forest** - Ensemble method with decision trees
4. **XGBoost** - Gradient boosting framework

## 📈 Key Features
- **Comprehensive EDA**: Data exploration and visualization
- **Data Preprocessing**: Outlier detection, scaling, and feature engineering
- **Cross Validation**: 10-fold stratified cross-validation for robust evaluation
- **Hyperparameter Tuning**: Grid search optimization for best models
- **Model Comparison**: Detailed performance metrics and visualizations
- **Feature Importance**: Analysis of most predictive medical parameters

## 🚀 Getting Started

### Prerequisites
Install required packages:
```bash
pip install -r requirements.txt
```

### Running the Project
1. Open `heart_disease_prediction.ipynb` in Jupyter Notebook or VS Code
2. Run all cells sequentially
3. The notebook will automatically:
   - Load and explore the dataset
   - Preprocess the data
   - Train all four ML models
   - Perform cross-validation
   - Tune hyperparameters
   - Compare model performances
   - Select the best model

## 📊 Expected Results
- **Model Accuracies**: 80-90% on test data
- **Cross Validation**: Robust performance across folds
- **Feature Insights**: Key predictors of heart disease
- **Model Rankings**: Performance comparison across algorithms

## 🔍 Analysis Sections
1. **Data Loading & Exploration** - Dataset overview and statistics
2. **Data Preprocessing** - Cleaning and preparation
3. **Exploratory Data Analysis** - Visualizations and correlations
4. **Feature Engineering** - Feature selection and scaling
5. **Model Training** - Individual algorithm implementation
6. **Cross Validation** - Model stability assessment
7. **Hyperparameter Tuning** - Performance optimization
8. **Final Evaluation** - Comprehensive model comparison

## 🏆 Model Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC
- Confusion Matrix
- Cross-validation scores

## 📁 Project Structure
```
Heart_Disease/
├── heart.csv                          # Dataset
├── heart_disease_prediction.ipynb     # Main notebook
├── requirements.txt                    # Python dependencies
└── README.md                          # Project documentation
```

## 🎯 Key Insights
The project provides insights into:
- Which medical parameters are most predictive of heart disease
- How different ML algorithms perform on medical data
- The importance of cross-validation in medical predictions
- Model interpretability for healthcare applications

## 🔧 Technical Notes
- Uses stratified train-test split to maintain class balance
- Implements proper feature scaling for algorithms that require it
- Includes both tree-based and linear models for comparison
- Provides comprehensive visualization of results

---
**Note**: This project is for educational purposes. Medical predictions should always be validated by healthcare professionals."# codealpha_Disease_prediction_from_medical_data-Heart-Disease-" 
