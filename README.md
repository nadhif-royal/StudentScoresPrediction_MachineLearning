# Student Scores Prediction - Machine Learning
Student Scores Prediction with Machine Learning is a project that I got from the 18.0 data series in the AI/ML field organized by dibimbing.id
This project explores different machine learning models to predict student scores based on available data. The goal is to compare the performance of **Linear Regression, Decision Tree, and Random Forest** to determine which model provides the most accurate predictions.

## 📌 Why This Project?

Predicting student performance is crucial in educational settings, as it helps educators identify students who may need additional support. By leveraging machine learning, we can analyze patterns in student data and make **data-driven predictions** to enhance learning strategies and outcomes.

## 📊 Dataset

The dataset (`student_scores.csv`) contains:
- **Study Hours**: Number of hours a student studies.
- **Scores**: The corresponding exam scores.

## 🏆 Models Used

1. **Linear Regression**  
   - Assumes a straight-line relationship between study hours and scores.
   - Works well for simple relationships but struggles with complex patterns.

2. **Decision Tree**  
   - Captures non-linear relationships but is prone to overfitting.
   - Performs better than linear regression but may require tuning.

3. **Random Forest**  
   - An ensemble of multiple decision trees to improve accuracy.
   - Reduces overfitting and provides the most reliable predictions.

## 🔍 Results & Insights

| Model            | R² Score |
|-----------------|----------|
| **Linear Regression** | 0.967 |
| **Decision Tree** | 0.946 |
| **Random Forest** | 0.981 |

- **Random Forest achieved the best accuracy (R² = 0.981)**, making it the most reliable model for predicting student scores.
- **Decision Tree performed well** but had overfitting tendencies.
- **Linear Regression was too simplistic** for this dataset.

## 📂 Project Files

- `StudentScorePrediction_MachineLearning.ipynb` → Jupyter Notebook with code and analysis.
- `student_scores.csv` → Dataset used for training and testing.
- `Presentation - Student Score Prediction.pdf` → Summary of findings and visualizations.

## Contact
👤 Nadhif Rif’at Rasendriya
🔗 [LinkedIn](https://www.linkedin.com/in/royalnadhif50/)
