## Human Gait Recognition System

This project is a simple Machine Learning-based Human Gait Recognition System developed using Python.
It analyzes walking patterns such as step length, stride width, walking speed, and body angle to identify different persons.

## Features
Data preprocessing using Pandas
Data visualization with Matplotlib and Seaborn
Correlation heatmap analysis
Random Forest Classifier for prediction
Confusion Matrix visualization
Human gait prediction system
## Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
## Installation

Install the required libraries using:

pip install pandas numpy matplotlib seaborn scikit-learn
## Project Structure
human_gait_recognition.py
README.md
requirements.txt
## Run the Project
Execute the Python file:

python human_gait_recognition.py
## Output
The project generates:
Statistical summary of data
Walking speed histogram
Scatter plot analysis
Correlation heatmap
Confusion matrix
Person ID prediction
## Machine Learning Model
Algorithm: Random Forest Classifier
Dataset Split: 70% Training / 30% Testing
## Example Prediction
new_person = [[68, 24, 4.1, 14]]
prediction = model.predict(new_person)
print(prediction)
