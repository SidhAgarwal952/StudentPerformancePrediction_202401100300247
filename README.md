# StudentPerformancePrediction_202401100300247

This project predicts students' final exam scores based on their study hours and previous scores using a machine learning model.

Dataset
The dataset contains the following features:

StudyHours: Number of hours a student studied
PreviousScores: Scores from previous exams
FinalExamScore: Target variable (student's final score)
Technologies Used
Python
Pandas
NumPy
Scikit-learn
Matplotlib
Installation
Clone this repository:
bash
Copy
Edit
git clone https://github.com/your-username/student-performance-prediction.git
Navigate to the project directory:
bash
Copy
Edit
cd student-performance-prediction
Install required dependencies:
bash
Copy
Edit
pip install -r requirements.txt
Usage
Run the script:
bash
Copy
Edit
python student_performance.py
The model will train and display evaluation metrics.
A graph will be generated comparing actual vs. predicted scores.
Project Workflow
Load and preprocess the dataset.
Split the dataset into training and testing sets.
Train a Random Forest Regressor model.
Evaluate model performance using Mean Absolute Error (MAE), Mean Squared Error (MSE), and R² Score.
Visualize actual vs. predicted values using a scatter plot.
Results
The trained model provides accurate predictions of student performance, helping educators understand key factors affecting scores.

Future Improvements
Add more features like attendance, assignments, and class participation.
Experiment with different machine learning models.
Deploy as a web app for real-time predictions.
