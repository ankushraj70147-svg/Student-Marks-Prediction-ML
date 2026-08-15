# Student Marks Prediction Using Machine Learning

## 📌 Project Overview

This project predicts a student's final examination marks using Machine Learning techniques.

The model uses student-related academic features such as attendance, internal test marks, assignment score, and daily study hours to predict the final exam marks.

## 🎯 Objective

The main objective of this project is to build a Machine Learning model that can predict student final exam marks based on their academic performance and study habits.

## 📊 Dataset

The dataset contains the following features:

| Feature | Description |
|---|---|
| Attendance | Student attendance percentage |
| Internal Test 1 | Marks obtained in Internal Test 1 |
| Internal Test 2 | Marks obtained in Internal Test 2 |
| Assignment Score | Assignment marks |
| Daily Study Hours | Average hours studied per day |
| Final Exam Marks | Final examination marks (Target) |

## 🤖 Machine Learning Algorithms

The following regression algorithms were tested:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Support Vector Regressor (SVR)
- K-Nearest Neighbors (KNN)

## 📈 Model Evaluation

The models were evaluated using the **R² Score**.

The dataset was divided into:

- 80% Training Data
- 20% Testing Data

## 🏆 Best Model

The best-performing model was:

**Linear Regression**

R² Score:

**0.8297**

Therefore, Linear Regression was selected as the final model for student marks prediction.

## 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- Matplotlib
- Scikit-learn
- Machine Learning

## 🔄 Project Workflow

1. Dataset Loading
2. Data Preprocessing
3. Feature Selection
4. Train-Test Split
5. Model Training
6. Model Evaluation
7. Best Model Selection
8. Student Marks Prediction

## 🚀 How to Run

1. Download or clone this repository.
2. Open the `.ipynb` file in Google Colab or Jupyter Notebook.
3. Upload the dataset.
4. Run the notebook cells sequentially.
5. Enter student information to predict final exam marks.

## 📌 Result

The project successfully predicts student final exam marks using Machine Learning.

Among the tested algorithms, **Linear Regression achieved the best R² Score of 0.8297**.

## 🔮 Future Scope

- Add more student-related features.
- Use a larger real-world dataset.
- Improve model performance through hyperparameter tuning.
- Develop a web-based interface for predictions.
- Deploy the model as an online application.

## 👨‍💻 Author

**Ankush Raj**

BCA Student
