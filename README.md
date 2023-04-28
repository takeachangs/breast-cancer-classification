# breast-cancer-classification

## Background 
Breast cancer is a major health concern that affects millions of people around the world. Early detection and accurate diagnosis are critical for successful treatment of breast cancer. Medical imaging technology has become an important tool in the detection and diagnosis of breast cancer. In recent years, machine learning algorithms have been increasingly used to analyze medical images and assist in the diagnosis of breast cancer.

## tldr;
In this project, I have used features of tumors and Support Vector Machine (SVM) to classify tumors into malignant or benign. 

## About the dataset
In the dataset, there are 32 features with 569 datapoints. The target variable of this data is "diagnosis", and it consists of either "M" which stants for Malignant and "B" which stands for Benign. 

## Evaluation 
- Linear SVM yielded an accuracy of 94%, weighted average precision of 94%, and weighted averaged recall of 94%. 
- Scaling using StandardScalar improved the model as the accuracy, weighted average precision, and the weighted average recall all increased to 98%. 
- To further increase the accuracy, I ran a Poly SVM and a RBF SVM. 
  - Poly SVM: I chose gamma to be 30, C to be 1. Accuracy was 92%, weighted average precision of 97%, and weighted average recall of 96%. 
  - RBF SVM: I chose gamma to be 0.01, C to be 1. Accuracy, weighted average precision and weighted average recall all yielded 99%. 
- The highest score of my parameter search is 98% when C= 5 and kernel is Linear 
