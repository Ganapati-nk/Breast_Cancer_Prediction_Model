# Breast Cancer Diagnosis Project

This project utilizes the **Breast Cancer Wisconsin (Diagnostic) Data Set** to create a predictive model for diagnosing breast cancer. The dataset contains features computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. These features describe characteristics of the cell nuclei present in the image.

## Objective

The main objective of this project is to build a machine learning model that can accurately classify tumors as <span style="color:red">benign</span> or <span style="color:red">malignant</span> based on the input features.

## Dataset Overview

- Number of instances: 569
- Number of attributes: 32 (ID, diagnosis, and 30 real-valued input features)
- Class distribution: 357 benign, 212 malignant

## Model

The model used for this project is **Logistic Regression**, a commonly used algorithm for binary classification tasks.

### Performance

The model's performance was evaluated using cross-validation. The results are as follows:

`Cross-Validation Accuracy: 0.95 ± 0.03`

## Conclusion

The Logistic Regression model achieved a high level of accuracy in classifying breast tumors as benign or malignant, demonstrating the effectiveness of this approach in medical diagnostics.
