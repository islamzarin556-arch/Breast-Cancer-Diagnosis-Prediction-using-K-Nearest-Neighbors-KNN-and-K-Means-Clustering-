Breast Cancer Diagnosis Classification
This project is a machine learning application that is used to analyze and categorize data of breast cancer (Benign vs. Malignant). It does the preprocessing of data, unsupervised clustering (K-Means), and supervised classification (K-Nearest Neighbors).

Dataset
The data set utilized in the project is the Breast Cancer Wisconsin (Diagnostic) Data Set.

Input File: Dataset.csv

Target Variable: diagnosis (Malignant, B = Benign)

Prerequisites
The project will be constructed to work in Google Colab. The python libraries needed are as follows:

pandas

numpy

matplotlib

seaborn

scikit-learn

How to Run
Load the notebook on Google Colab.

Run the script.

File Upload: This script will make you upload a file. Press the button which is in the output area and which is titled Choose Files, and then choose your Dataset.csv file on your local computer.

The file will be read automatically in the script and the analysis will be carried out.

Methodology
Data Cleaning:

Eliminates redundant columns (id, Unnamed: 32).

Coded the column with diagnosis (Benign:0, Malignant: 1).

Preprocessing:

The Min-Max Normalization is used to scale features as well so that all of the values fall within the range 0 to 1.

The data is divided into Training and Testing sets (75 and 25 percent).

In the Unsupervised Learning (K-Means) model, the clusters are constructed directly:<|human|>Unsupervised Learning (K-Means):

Clusters data into 2 groups in order to see natural separation.

A comparison of clusters with real diagnosis labels.

Supervised Learning (KNN):

Training a K-Nearest Neighbors classifier with k= 7.

Assesses the performance on the test set.

Output & Evaluation
The following are the results of the script:

Data Info: Basic statistics and null.

Clustering Crosstab: A table of comparison of K-Means clusters with real labels.

Accuracy Score: This is the overall accuracy of KNN model.

Classification Report: Precision, Recall, and F1-score score of the two classes.

Confusion Matrix: A heatmap chart of the actual and intended labels.
