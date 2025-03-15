# Machine Learning Algorithm's Effect on Predictive Analytics in Healthcare - A Diabetes Risk Case Study

## Overview
This study explores the impact of various **Machine Learning (ML)** algorithms on predicting Type 2 Diabetes (T2D) using the **Diabetes Health Indicators Dataset**. It aims to identify which algorithms provide the most accurate and reliable predictions, assisting healthcare professionals in early detection and treatment. The paper evaluates models such as **Logistic Regression**, **Random Forest**, **Decision Tree**, **Neural Network**, **K-Nearest Neighbour (KNN)**, and **Support Vector Machine (SVM)**.

## Key Objectives
- Assess the performance of ML models in predicting T2D.
- Evaluate algorithms based on metrics like **Accuracy**, **Precision**, **Recall**, **Balanced Accuracy**, and **AUC-ROC**.
- Recommend enhancements for practical healthcare applications of these models.

## Key Features
1. **Data Preprocessing**:
   - Applied techniques like **SMOTE** to handle class imbalance.
   - Feature selection via **Exploratory Data Analysis (EDA)**.
   - Standardized features and used 80-20 train-test splitting with cross-validation.

2. **Machine Learning Models**:
   - **Logistic Regression**: Baseline model with strong interpretability and consistent results.
   - **Random Forest**: Achieved highest accuracy (83.66%) but suffered from low specificity.
   - **Neural Network**: Exhibited best-balanced accuracy (74.63%) and AUC (0.83).
   - **Decision Tree**: Moderate performance with a balanced accuracy of 70.02%.
   - **KNN**: Performed moderately with high specificity (78.58%).
   - **SVM**: Reliable balanced accuracy (74.40%) but computationally intensive.

3. **Evaluation Metrics**:
   - Accuracy and balanced accuracy for overall model performance.
   - Precision and recall to minimize false positives and negatives.
   - AUC-ROC scores to evaluate class separation capability.

## Key Findings
- **Neural Networks** are the most effective overall due to their balanced performance across all metrics.
- **Random Forest** demonstrates the highest accuracy but has issues with false positives.
- Models like **KNN** and **SVM** excel in specific areas, such as identifying non-diabetic patients.
- Logistic Regression remains a robust baseline, favored for its simplicity and efficiency in healthcare settings.

## Recommendations for Future Work
1. **Hybrid Models**: Combine strengths of algorithms like Neural Networks and Logistic Regression for ensemble-based approaches.
2. **Feature Engineering**: Incorporate genetic or longitudinal health data for improved prediction.
3. **Cost-Sensitive Learning**: Address trade-offs between false positives and negatives in medical contexts.
4. **Real-Time Predictive Systems**: Develop tools that utilize continuously updated health data.

## Limitations
- **Computational Resources**: Intensive algorithms like SVM required down-sampled datasets.
- **Class Imbalance**: While SMOTE helped, challenges remain with real-world data generalization.
- **Interpretability**: Models like Random Forest and Neural Networks lack transparency, complicating healthcare adoption.

## Implications
This research highlights the transformative potential of ML in healthcare, especially for early diabetes detection. It underscores the value of neural networks for real-world applications and the importance of model refinement to handle challenges such as overfitting and interpretability.

## Authors
- **Darshan Patel**  
  MSc Data Science and Analytics  
  Brunel University London  
  Academic Year: 2023-2024  
