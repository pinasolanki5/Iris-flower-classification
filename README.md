 🌸 Iris Flower Classification – Machine Learning Project

> ✅ **This project was completed as part of my AI AND ML Internship at [CloudCredits](https://cloudcredits.in/)**

---

This project uses machine learning to classify iris flowers into three species — *Setosa*, *Versicolor*, and *Virginica* — based on their petal and sepal measurements. It follows a standard end-to-end data science pipeline.

---

## 📌 Objective

To build a classification model that accurately predicts the species of an iris flower based on four key features:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

---

## 🧠 Problem Type

**Supervised Machine Learning** – Multiclass Classification Problem

---

## 📁 Dataset

The Iris dataset is a built-in dataset available in `sklearn.datasets` containing 150 records:
- 3 classes (50 samples each)
- 4 numerical features

---

## 🔍 Project Pipeline

1. **Define the Problem** – Understand the objective and target  
2. **Collect & Prepare Data** – Load dataset and clean it (no missing values)  
3. **Exploratory Data Analysis (EDA)** – Visualize feature relationships and correlations  
4. **Feature Engineering** – Use relevant features as-is (no new features needed)  
5. **Split the Data** – Train/Test split (80/20)  
6. **Choose a Model** – Used Decision Tree Classifier  
7. **Train the Model** – Fit model to training data  
8. **Evaluate the Model** – Accuracy, Confusion Matrix, Classification Report  


## 📊 Visualizations Included

- ✅ Pairplot of all features  
- ✅ Correlation heatmap  
- ✅ Boxplots by species  
- ✅ Histograms of features  
- ✅ Confusion Matrix heatmap  

---

## 📈 Model Performance

- **Algorithm Used**: `DecisionTreeClassifier` from `scikit-learn`  
- **Accuracy Achieved**: ~96% on test data  
- **Metrics Evaluated**:
  - Accuracy Score  
  - Confusion Matrix  
  - Precision, Recall, F1-score  

---

## 📦 Technologies Used

- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---

## 🛠️ How to Run This Project

Follow these steps to run the project on your local machine:

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/iris-flower-classification.git

Navigate to the Project Folder
cd iris-flower-classification

Create a Virtual Environment
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate

. Install Dependencies
pip install -r requirements.txt

5. Launch Jupyter Notebook
jupyter notebook

6. Open iris_classification.ipynb and Run All Cells
You can now explore the notebook, run the model, and view results!

🌟 Acknowledgement
✅ Completed during Internship at CloudCredits

Dataset: Iris Dataset - UCI

Tools: scikit-learn, seaborn, matplotlib



