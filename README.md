Breast Cancer Classification using Machine Learning

📌 Project Overview

This project implements multiple supervised machine learning classification algorithms to predict whether a breast tumor is benign or malignant. The analysis is performed using the Breast Cancer Wisconsin dataset available in the scikit-learn library.

The main objective is to understand how different classification models behave on the same dataset and how data preprocessing and algorithm choice affect prediction performance.

📊 Dataset Information

* Source: sklearn.datasets
* Dataset Name: Breast Cancer Dataset
* Problem Type: Binary Classification
* Samples: 569
* Features: 30 numerical medical measurements
* Target Variable:

  * 0 – No Breast Cancer
  
  * 1 – Has Breast Cancer

The dataset is clean, structured, and suitable for supervised learning.

🧠 Algorithms Implemented:

The following supervised classification algorithms are used in this project:

1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier
4. Support Vector Machine (SVM)
5. k-Nearest Neighbors (k-NN)

Each algorithm is trained and evaluated to compare performance and understand model behavior.

This selection allows comparison between:

* Linear vs non-linear models
* Single models vs ensemble methods
* Distance-based vs margin-based approaches

⚙️ Data Preprocessing

The following preprocessing steps were applied:

* Basic data inspection and statistical analysis
* Verification of missing or inconsistent values
* Feature scaling to standardize value ranges where required
* Train-test split for model evaluation

📈 Model Evaluation

The models are evaluated using standard classification metrics:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix

These metrics help assess both correctness and reliability of predictions.

Key Takeaways

1. Feature scaling is essential when features have different value ranges.
2. Simple models like Logistic Regression provide strong baselines.
3. Decision Trees are interpretable but can overfit.
4. Random Forest improves stability and generalization.
5. SVM delivers strong performance when data is well-separated.

Overall, Random Forest and SVM showed the most consistent and reliable results for this dataset.

🛠️ Tools and Libraries Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

✅ Conclusion

The results show that proper data preprocessing and the choice of algorithm significantly impact model performance. Ensemble and margin-based models such as Random Forest and Support Vector Machine provided strong and consistent results for this dataset.

This project highlights the importance of preprocessing, model comparison, and evaluation in medical classification tasks.

▶️ How to Run the Project

1. Clone this repository
2. Open the Jupyter Notebook file
3. Run the cells sequentially

No external dataset download is required, as the data is loaded directly from sklearn.

👤 Author

Nikhil Gopi
