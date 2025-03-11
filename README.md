# Student-Performance-Predication
Overview
This project predicts student performance in final exams based on study hours and previous exam scores using a Linear Regression model. The dataset includes information about students' study habits and past performance to help educators and students make data-driven decisions.

Dataset
The dataset consists of the following features:

StudentID: Unique identifier for each student (not used in prediction).
StudyHours: Number of hours a student studies.
PreviousScores: Scores obtained in past exams.
FinalExamScore: Actual performance in the final exam (target variable).
Technologies & Libraries Used
Python
pandas - Data processing and manipulation.
numpy - Numerical computing.
matplotlib - Data visualization.
scikit-learn - Machine learning model training and evaluation.
Project Structure
bash
Copy
Edit
/student-performance-prediction
│-- student_data.csv         # Dataset
│-- student_prediction.py    # Python script for model training & prediction
│-- README.md                # Project documentation
Implementation Steps
Load Dataset - Read the student data from a CSV file.
Data Preprocessing - Remove unnecessary columns and prepare data for training.
Train Model - Use Linear Regression to train the model.
Evaluate Model - Assess the model’s accuracy using MAE and R² scores.
Visualize Results - Create scatter plots for study hours vs. final exam scores and previous scores vs. final exam scores.

Results
Mean Absolute Error (MAE): Measures the average error in predictions.
R-squared (R²) Score: Shows how well the model fits the data.

Visualization
The project includes the following scatter plots:
📌 Study Hours vs. Final Exam Scores
📌 Previous Scores vs. Final Exam Scores
