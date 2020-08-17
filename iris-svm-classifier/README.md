# **Iris Flower Classification using SVM**

**Author:** SandeepTeja Sundara  

---

## **Project Overview**

This project demonstrates how to build a **Support Vector Machine (SVM)** classifier to predict the species of an Iris flower based on four features:

- **Sepal Length**  
- **Sepal Width**  
- **Petal Length**  
- **Petal Width**

The model is trained on the famous **Iris dataset**, originally introduced by **R.A. Fisher** in 1936. It is widely used as a classic dataset in classification and pattern recognition.

---

## **Dataset Summary**

- **Total Samples:** 150  
- **Number of Classes:** 3  
  - *Iris Setosa*  
  - *Iris Versicolour*  
  - *Iris Virginica*  
- **Features:**  
  - Sepal length (cm)  
  - Sepal width (cm)  
  - Petal length (cm)  
  - Petal width (cm)  
- **Missing Values:** None  
- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/iris)

---

## **Technologies & Libraries**

- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Pickle

---

## **Model Details**

- **Algorithm:** Support Vector Classifier (**SVC**)  
- **Data Split:** 80% Training / 20% Testing  
- **Model Accuracy:** **>96%** on test data  
- **Evaluation Metrics:**  
  - Accuracy Score  
  - Precision, Recall, F1-Score (via Classification Report)

---

## **Visualizations**

The notebook includes insightful visualizations to understand the data:

- **Pairplot**: To visualize pairwise feature relationships and class separability  
- **Bar Chart**: To show average feature values across each species  

All plot images are saved under the `plots/` directory.

---

## **Sample Predictions**

The trained model is saved as `SVM.pickle` and can be reused to predict new data.

---

## **Repository Structure**

├── iris_classifier.ipynb       # Main notebook
├── iris.data                   # Dataset file
├── SVM.pickle                  # Saved SVM model
├── plots/                      # Folder with saved plots
│   ├── pairplot.png
│   └── barplot.png
└── README.md                   # Project documentation

---

## **Getting Started**

To get a local copy of this project up and running, follow these steps:

### **Clone the Repository**

```bash
git clone https://github.com/Sandetej/Data_Science_Projects-.git
cd Data_Science_Projects-/iris-svm-classifier
```

## **Install Dependencies**

Make sure you have Python and pip installed. Then run:

```bash
pip install -r requirements.txt