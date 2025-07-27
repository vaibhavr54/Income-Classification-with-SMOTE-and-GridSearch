# Income Classification with SMOTE and GridSearchCV

## 📊 Project Overview
A comprehensive machine learning project that predicts whether an individual's annual income exceeds $50K based on demographic and work-related features using the UCI Adult dataset. This project implements advanced techniques including SMOTE for handling class imbalance and GridSearchCV for hyperparameter optimization.

## 🎯 Objective
Develop a robust binary classification model with complete preprocessing pipeline to predict income levels while addressing real-world data challenges like class imbalance and feature optimization.

## 📈 Dataset Information
- **Source**: [UCI Adult Dataset (Census Income)](https://archive.ics.uci.edu/ml/datasets/adult)
- **Records**: 32,561 samples
- **Features**: 14 input features + 1 target variable
- **Target Classes**: ≤50K (0) and >50K (1)
- **Data Files**: `adult.data`, `adult.test`, `adult.names`

## 🛠️ Technology Stack
- **Python 3.x**
- **pandas** - Data manipulation and analysis
- **numpy** - Numerical operations
- **matplotlib** - Data visualization
- **scikit-learn** - Machine learning pipeline
- **imbalanced-learn** - SMOTE implementation

## 🔧 Key Features
- ✅ **Complete Data Preprocessing Pipeline**
- ✅ **Class Imbalance Handling** using SMOTE
- ✅ **Hyperparameter Tuning** with GridSearchCV
- ✅ **Feature Engineering** for categorical and numerical data
- ✅ **Model Performance Evaluation**
- ✅ **Comprehensive Data Analysis**

## 📁 Project Structure
Income-Classification-with-SMOTE-and-GridSearch

├── Income Classification with SMOTE and GridSearch.ipynb # Main notebook

├── adult.data # Training dataset

├── adult.names # Feature descriptions

├── adult.test # Test dataset

├── old.adult.names # Legacy feature names

├── Index # Dataset index

├── README.md # Project documentation


## 🚀 Getting Started

### Prerequisites
Ensure you have Python 3.7+ installed on your system.

### Installation
1. **Clone the repository**
git clone https://github.com/vaibhavr54/Income-Classification-with-SMOTE-and-GridSearch.git

cd Income-Classification-with-SMOTE-and-GridSearch


3. **Install required packages**
pip install pandas numpy matplotlib scikit-learn imbalanced-learn jupyter


4. **Launch Jupyter Notebook**
jupyter notebook "Income Classification with SMOTE and GridSearch.ipynb"


## 📊 Data Features

### Numerical Features
- **age**: Age of the individual
- **fnlwgt**: Final weight (sampling weight)
- **education-num**: Years of education
- **capital-gain**: Capital gains
- **capital-loss**: Capital losses
- **hours-per-week**: Hours worked per week

### Categorical Features
- **workclass**: Type of employment
- **education**: Education level
- **marital-status**: Marital status
- **occupation**: Job occupation
- **relationship**: Family relationship
- **race**: Race/ethnicity
- **sex**: Gender
- **native-country**: Country of origin

## 🔍 Machine Learning Pipeline

### 1. Data Preprocessing
- **Missing Value Handling**: Detection and treatment of missing data
- **Feature Scaling**: StandardScaler for numerical features
- **Categorical Encoding**: OneHotEncoder for categorical variables
- **Feature Selection**: Analysis of feature importance

### 2. Class Imbalance Handling
- **SMOTE Implementation**: Synthetic Minority Oversampling Technique
- **Balanced Dataset Creation**: Addressing skewed target distribution

### 3. Model Training
- **Algorithm**: Random Forest Classifier
- **Hyperparameter Tuning**: GridSearchCV optimization
- **Cross-Validation**: K-fold validation for robust evaluation

### 4. Model Evaluation
- **Performance Metrics**: Accuracy, Precision, Recall, F1-Score
- **Confusion Matrix**: Classification performance visualization
- **Feature Importance**: Analysis of most predictive features

## 📈 Expected Results
The model achieves robust performance in predicting income classification with:
- Balanced precision and recall through SMOTE
- Optimized hyperparameters via GridSearch
- Comprehensive feature engineering pipeline

## 🔧 Usage Examples

### Basic Usage
Load and run the complete notebook
jupyter notebook "Income Classification with SMOTE and GridSearch.ipynb"


### Key Code Sections
1. **Data Loading & Exploration**
2. **Preprocessing Pipeline Setup**
3. **SMOTE Application**
4. **GridSearch Implementation**
5. **Model Training & Evaluation**
6. **Results Visualization**

## 📝 Project Workflow
1. **Data Import**: Load UCI Adult dataset
2. **Exploratory Data Analysis**: Understand data distribution and patterns
3. **Data Cleaning**: Handle missing values and outliers
4. **Feature Engineering**: Transform and encode features
5. **Class Balancing**: Apply SMOTE technique
6. **Model Selection**: Implement Random Forest with GridSearch
7. **Performance Evaluation**: Assess model metrics
8. **Results Interpretation**: Analyze feature importance and predictions

## 🤝 Contributing
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/enhancement`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/enhancement`)
5. Create a Pull Request

## 📄 License
This project is open source and available under the [MIT License](LICENSE).

## 🏷️ Tags
`machine-learning` `classification` `smote` `gridsearch` `random-forest` `uci-dataset` `income-prediction` `data-science` `python` `scikit-learn`

## 👨‍💻 Author
**vaibhavr54** - [GitHub Profile](https://github.com/vaibhavr54)

## 📞 Contact
For questions or suggestions, please open an issue in this repository.

---
⭐ **Star this repository if you find it helpful!** ⭐
