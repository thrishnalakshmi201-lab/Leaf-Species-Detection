#  Leaf Species Detection using Machine Learning

## 📌 Project Overview

This project demonstrates the classification of Iris flower species using a Machine Learning algorithm. A Decision Tree Classifier is trained to predict the species of an Iris flower based on four measurements.

The model classifies flowers into three categories:
- Setosa
- Versicolor
- Virginica

## 🎯 Project Objectives

- Understand the basics of Machine Learning classification.
- Explore and analyze the Iris dataset.
- Train a Decision Tree classification model.
- Evaluate model performance using accuracy.
- Understand the effect of tree depth on model accuracy.
- Predict the species of a new flower using the trained model.

## 📊 Dataset Information

The project uses the classic Iris dataset containing 150 flower records.

**Features:**
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

**Target Variable:** Species

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## 🤖 Machine Learning Algorithm

**Decision Tree Classifier**

A Decision Tree is a supervised Machine Learning algorithm used for classification. It learns decision rules from the training data to predict the flower species.

## ⚙️ Project Workflow

1. Import required Python libraries.
2. Load the Iris dataset.
3. Perform Exploratory Data Analysis (EDA).
4. Visualize the dataset.
5. Select features and target variables.
6. Split the dataset into training and testing sets (80:20).
7. Train the Decision Tree Classifier.
8. Evaluate the model using accuracy score.
9. Analyze the effect of maximum tree depth.
10. Predict the species of a new flower.

## 📁 Project Structure

```text
Leaf-Species-Detection/
│
├── data/
│   └── iris.csv
│
├── 01_leaf_species_detection.ipynb
│
├── README.md
│
├── requirements.txt
│
└── .gitignore
```

## 🚀 How to Run the Project

**Step 1: Clone the repository**

```bash
git clone https://github.com/YOUR-USERNAME/iris-flower-species-classification.git
```

**Step 2: Navigate to the project folder**

```bash
cd iris-flower-species-classification
```

**Step 3: Install the required libraries**

```bash
pip install -r requirements.txt
```

**Step 4: Run the Jupyter Notebook**

```bash
jupyter notebook
```

Open `01_leaf_species_detection.ipynb` and run the cells.

## 📈 Model Evaluation

The model performance is evaluated using the accuracy score on the test dataset.

The project also compares test accuracy for different values of `max_depth` to understand how tree depth affects model performance.

## 🔮 Sample Prediction

The model accepts four flower measurements:

- Sepal Length: 5.1
- Sepal Width: 3.5
- Petal Length: 1.4
- Petal Width: 0.2

It predicts the corresponding Iris flower species.

## 📚 Learning Outcomes

- Understanding supervised Machine Learning.
- Working with datasets using Pandas.
- Data visualization using Matplotlib.
- Building a Decision Tree Classifier.
- Evaluating classification models.
- Making predictions using trained models.

git clone https://github.com/thrishnalakshmi201-lab/Leaf-Species-Detection.git
cd Leaf-Species-Detection
