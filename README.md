Breast Cancer Classification using SVM
This project applies Support Vector Machines (SVM) for binary classification on the Breast Cancer dataset. It compares Linear SVM and Non-linear SVM (RBF kernel) performance, along with hyperparameter tuning and visualization.

📁 Dataset
Dataset: breast-cancer.csv

Source: UCI Machine Learning Repository

Classes:

M: Malignant (mapped to 1)

B: Benign (mapped to 0)

Total features: 30 numeric measurements of cell nuclei from digitized images of breast mass samples.

🛠️ Tools & Libraries
Python 3

Scikit-learn

Pandas

NumPy

Matplotlib

📌 Objectives
Load and preprocess the breast cancer dataset.

Train a Linear SVM and an RBF (non-linear) SVM.

Tune hyperparameters using GridSearchCV.

Evaluate models using accuracy, confusion matrix, and classification report.

Visualize:

2D PCA projection of dataset.

Accuracy comparison bar chart of different SVM models.

⚙️ Methodology
Data Preprocessing

Drop non-informative columns (id, Unnamed: 32 if present).

Map diagnosis values: M → 1, B → 0.

Scale features using StandardScaler.

Model Training

Linear SVM using kernel='linear'

RBF SVM using kernel='rbf'

Model Evaluation

Accuracy score

Confusion matrix

Classification report

Hyperparameter Tuning

Parameters: C, gamma

Grid Search with 5-fold Cross Validation

Visualization

PCA projection of data (pre-SVM)

Bar chart comparing SVM accuracies


