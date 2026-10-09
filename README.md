# Oral Cancer Prediction Using Machine Learning

## About the Project

This project explores the use of machine learning algorithms to classify oral cancer diagnoses using patient demographic details, lifestyle habits, and clinical symptoms. It uses Python for data analysis, preprocessing, visualization, model training, and performance evaluation.

The main objective is to compare different classification algorithms and understand the challenges of predicting oral cancer using pre-diagnostic features.

## Objectives

- Analyze and explore the dataset using Exploratory Data Analysis (EDA).
- Clean and preprocess data for machine learning.
- Identify and remove features that may cause data leakage.
- Apply feature encoding and scaling techniques.
- Perform Principal Component Analysis (PCA) for dimensionality analysis and visualization.
- Train and compare multiple machine learning classification models.
- Evaluate model performance using standard classification metrics.

## Dataset

- **Dataset:** Oral Cancer Prediction Dataset
- **Total Records:** 84,922
- **Total Attributes:** 25
- **Target Variable:** Oral Cancer (Diagnosis)
- **Problem Type:** Supervised Binary Classification
- **Train-Test Split:** 80:20

The dataset contains demographic information, lifestyle risk factors, oral symptoms, and diagnosis labels.

Post-diagnosis attributes and non-predictive identifiers are excluded from the final feature set to reduce data leakage.

## Technologies Used

- Python
- Jupyter Notebook / Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Machine Learning Algorithms

The project compares six classification algorithms:

1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier
4. K-Nearest Neighbors (KNN)
5. Support Vector Machine (SVM)
6. Gaussian Naive Bayes

## Project Workflow

1. Dataset loading and inspection
2. Exploratory Data Analysis (EDA)
3. Data cleaning and preprocessing
4. Categorical feature encoding
5. Data leakage prevention
6. Stratified train-test splitting
7. Feature scaling
8. Principal Component Analysis (PCA)
9. Model training and evaluation
10. Performance comparison and conclusion

## Evaluation Metrics

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC
- Confusion Matrix

## Results

After removing post-diagnosis features, the evaluated models achieved approximately **50% test accuracy**.

This result indicates that the remaining features in the dataset provide limited predictive information for distinguishing between the two diagnosis classes. It also highlights the importance of preventing data leakage when developing machine learning models.

## How to Run the Project

### 1. Clone the Repository

```bash
git clone <your-repository-url>
cd <your-repository-name>
```

### 2. Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### 3. Open the Notebook

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Alternatively, upload `MLOralCancerFinal.ipynb` to Google Colab.

### 4. Load the Dataset

Place the dataset in the appropriate location and update the file path in the notebook before running the cells.

**Note:** The dataset file must be obtained separately if it is not included in this repository.

## Project Structure

```text
Oral-Cancer-Prediction-ML/
├── MLOralCancerFinal.ipynb
├── ML_PROJECT_REPORT.pdf
└── README.md
```

## Limitations

- The models achieved performance close to random classification after data leakage was removed.
- The results depend on the quality and reliability of the dataset.
- The project is intended for academic learning and experimentation.

## Disclaimer

This project is developed for educational and research purposes only. It is not a clinically validated diagnostic system and must not be used to diagnose oral cancer or make medical decisions.

## Authors

- Nehang Majethiya


## Academic Information

**Degree:** Master of Computer Applications (MCA)  
**University:** Marwadi University  
**Academic Year:** 2026–2027

**Project Guide:** Dr. Divyakant Meva
