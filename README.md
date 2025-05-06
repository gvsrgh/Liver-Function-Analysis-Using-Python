# Liver Function Analysis Using Python

## Members

* **G. Venkata Sai Ram** (22501A0557)
* **Aakash Kodali** (22501A0501)
* **G. Rani** (22501A0562)
* **B.T. Thanusri** (22501A0528)
* **A. Mrudula** (23505A0501)

## 🥅 Goals of the Project

* Develop a predictive model to identify potential liver dysfunction using machine learning.
* Utilize real-world medical data to analyze liver function parameters effectively.
* Improve diagnostic accuracy and enable early intervention in liver-related disorders.
* Gain experience in using Python libraries for data science and healthcare analytics.

## 🔄 Process

1. **Data Collection**: Acquired a liver patient dataset from Kaggle containing 583 records with 10 medical features.
2. **Data Preprocessing**:

   * Handled missing values (e.g., imputation in the `Albumin_and_Globulin_Ratio` column).
   * Encoded categorical values such as `Gender`.
   * Scaled features using `StandardScaler` for model efficiency.
3. **Model Building**:

   * Used **Logistic Regression** for binary classification.
   * Trained the model with stratified train-test split for balanced class representation.
4. **Evaluation**:

   * Evaluated using Accuracy, Precision, Recall, F1-Score, AUC-ROC, and Confusion Matrix.
5. **Result**:

   * Achieved reliable prediction accuracy with potential to enhance via advanced algorithms in future iterations.

## 🧩 Details of Features

* **Age**: Patient age
* **Gender**: Male/Female
* **Total\_Bilirubin**: Amount of bilirubin in blood
* **Direct\_Bilirubin**: Conjugated bilirubin level
* **Alkaline\_Phosphotase**: Enzyme level, important liver function indicator
* **Alamine\_Aminotransferase (ALT)**: Enzyme related to liver inflammation
* **Aspartate\_Aminotransferase (AST)**: Enzyme, often used in liver tests
* **Total\_Protiens**: Protein level in the blood
* **Albumin**: Main protein in blood plasma
* **Albumin\_and\_Globulin\_Ratio**: Protein ratio indicating liver health
* **Dataset (Target)**:

  * 1: No liver dysfunction
  * 2: Possible liver dysfunction
