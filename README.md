# P01 - Iris Flower Classification 

*A machine learning project to classify iris flowers using a Random Forest Classifier.*

---

## 1. Project Overview

This project aims to classify Iris flowers into one of three species (*Setosa, Versicolor, or Virginica*) based on their physical characteristics. The project utilizes the famous Iris dataset. The objective is to build a robust model that can accurately predict the species of an iris flower from its features.

---

## 2. Dataset

The Iris dataset contains samples of iris flowers. Each sample includes four features and a single target variable (species).

**Features:**
- `sepal length` (cm)
- `sepal width` (cm)
- `petal length` (cm)
- `petal width` (cm)

**Target Variable:**
- `Species`: Setosa, Versicolor, or Virginica

---

## 3. Methodology

A Random Forest Classifier from the Scikit-learn library was chosen for this task due to its effectiveness and ability to handle non-linear data. The project follows a standard machine learning workflow:
- **Data Loading and Exploration:** Using Pandas and Matplotlib/Seaborn to understand the dataset.
- **Model Training:** Training the Random Forest Classifier on the preprocessed data.
- **Model Evaluation:** Evaluating the model's performance using metrics like accuracy.

---

## 4. Results

The trained Random Forest model achieved a high accuracy score on the test set, demonstrating its effectiveness in distinguishing between the three iris species. The model achieved a **100% accuracy**, indicating a strong performance, mainly due to the use of a simple dataset like Iris.

---

## 5. Technologies & Libraries

- **Python**: The core programming language.
- **Pandas & NumPy**: For data manipulation and numerical operations.
- **Matplotlib & Seaborn**: For data visualization and exploratory data analysis.
- **Scikit-learn**: For machine learning model implementation (RandomForestClassifier).

---

## 6. How to Run the Project

To run this project, you need to have Python and the required libraries installed.

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/neel-09/P01-Iris-Classification.git](https://github.com/neel-09/P01-Iris-Classification.git)
    ```

2.  **Navigate to the project directory:**
    ```bash
    cd P01-Iris-Classification
    ```

3.  **Install the necessary libraries:**
    ```bash
    pip install pandas numpy scikit-learn matplotlib seaborn
    ```

4.  **Run the Jupyter Notebook:**
    Open the `P01_Iris_Classification.ipynb` file in Jupyter Notebook to view the code and run the cells.

---
