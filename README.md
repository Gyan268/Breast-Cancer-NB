# 🧠 Breast Cancer Prediction using Naive Bayes

This project applies the **Naive Bayes classification algorithm** to predict whether a tumor is benign or malignant using the **Breast Cancer Wisconsin dataset**. It provides a straightforward example of a supervised machine learning pipeline using Python and scikit-learn.

## 📂 Project Structure

- `Breast-Cancer-NB.ipynb`: Jupyter Notebook containing data preprocessing, visualization, model training, and evaluation.
- `breast-cancer-wisconsin.csv`: The dataset used for model training and testing.

## 📊 Dataset Overview

The **Breast Cancer Wisconsin (Diagnostic) dataset** includes features computed from digitized images of fine needle aspirates (FNAs) of breast masses. Each record represents characteristics of the cell nuclei present in the image.

**Features:**
- `Clump Thickness`
- `Uniformity of Cell Size`
- `Uniformity of Cell Shape`
- `Marginal Adhesion`
- `Single Epithelial Cell Size`
- `Bare Nuclei`
- `Bland Chromatin`
- `Normal Nucleoli`
- `Mitoses`

**Target:**
- `Class` (2 = benign, 4 = malignant)

## 🚀 Workflow

1. **Data Preprocessing**
   - Load and clean the dataset
   - Handle missing values
   - Encode categorical variables

2. **Exploratory Data Analysis (EDA)**
   - Distribution plots
   - Class balance checking

3. **Model Building**
   - Train/Test split
   - Naive Bayes classifier (GaussianNB)
   - Model training and prediction

4. **Evaluation**
   - Confusion matrix
   - Accuracy, precision, recall, and F1-score

## 📈 Results

The model achieves high accuracy with minimal preprocessing. It's a good example of how probabilistic models like Naive Bayes can perform well even with relatively small datasets.

## 📦 Dependencies

Install required packages using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## ▶️ Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/Gyan268/breast-cancer-nb.git
   cd breast-cancer-nb
   ```

2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook Breast-Cancer-NB.ipynb
   ```

3. Run the notebook cells to see the analysis and model in action.

## 📚 References

- scikit-learn Naive Bayes: https://scikit-learn.org/stable/modules/naive_bayes.html
