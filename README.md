# PCOS Detection Using Machine Learning Algorithms

## Abstract

This research paper focuses on predicting the likelihood of Polycystic Ovarian Syndrome (PCOS) in women of reproductive age using machine learning and data mining techniques. PCOS is a prevalent endocrine condition that, if detected early, can prevent long-term health complications. The study employs various classification algorithms, including Logistic Regression, Naive Bayes Classification, KNN, Random Forest Classification, and Support Vector Machine (SVM), to efficiently predict PCOS based on factors such as follicle number, skin darkening, hair growth, weight gain, menstrual cycle regularity, and fast food consumption.

The results reveal that the Support Vector Machine algorithm achieves the highest accuracy in predicting PCOS, outperforming the other algorithms. The study highlights the significance of feature selection and algorithm choice in creating precise predictive models, demonstrating the potential of machine learning in healthcare.

## Introduction

Polycystic Ovarian Syndrome affects up to 13% of women in the reproductive age group, leading to various clinical symptoms and complications. Early detection is crucial for timely intervention and prevention of further health issues. This study explores the use of machine learning to predict PCOS based on factors such as age, weight, and lifestyle choices like fast food consumption.

## Methodology

- **Data Preprocessing**: The dataset is cleaned, missing values imputed, and non-informative attributes removed.

- **Feature Selection**: Highly correlated attributes such as 'Follicle No (L)', 'Follicle No (R)', 'Fast food', 'Pimples', 'Cycle Regularity', 'Skin Darkening', 'Hair Growth', and 'Weight Gain' are selected for analysis.

- **Classification Algorithms**:
    1. **Logistic Regression**: A statistical approach for binary classification.
    2. **Naive Bayes Classification**: Assumes feature independence.
    3. **Random Forest Classifier**: An ensemble method combining multiple decision trees.
    4. **KNN Classification**: Utilizes nearest neighbors to classify data points.
    5. **Support Vector Machine (SVM)**: Seeks to find the optimal hyperplane for classification.

## Results

- **Logistic Regression**: Achieved 84% accuracy in predicting PCOS.
- **Naive Bayes Classification**: Achieved 82% accuracy.
- **Random Forest Classifier**: Achieved an impressive 90.02% accuracy.
- **KNN Classification**: Achieved a high accuracy of 92.63%.
- **Support Vector Machine**: Outperformed all others with a remarkable 93.25% accuracy.

## Conclusion

This study compared various machine learning classifiers for PCOS detection, with SVM emerging as the most accurate predictor. SVM's ability to handle high-dimensional data and clear class separation makes it a promising tool for PCOS diagnosis. Early detection using machine learning can assist medical professionals in providing timely interventions for at-risk patients, emphasizing the potential of data-driven approaches in healthcare.

---

*Note: This README summarizes the key findings and methods from the research paper on PCOS detection using machine learning algorithms. Please refer to the full research paper for detailed insights and methodology.*
