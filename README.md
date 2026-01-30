# AI-EXPERT-SYSTEM-FOR-A-SMALL-CLINIC
AI expert system utilizing a Decision Tree model to guide non-medical staff in evaluating patients.

INTRODUCTION
There is a frequent lack of medical professionals necessary to evaluate each patient immediately. Receptionists and other non-medical staff require quick guidance to determine
whether a patient should be referred to a physician or be provided with basic home remedy.
This project proposes development of an AI expert system that uses a Decision Tree model to provide advice based on input symptoms.
OBJECTIVES
I. Design an expert system that assists non-medical staff in patient diagnosis.
II. Design a prototype using decision trees for automatic learning.
ASSUMPTIONS
I. The receptionist records yes/no responses for 9 symptoms:
Fever, Cough, Sore Throat, Runny Nose, Body Ache, Sneezing, Headache, Fatigue, Short Breath.
II. The system provides decisions using scikit-learn library:
i. Refer to Doctor.
ii. Home Remedy Recommended.
III. The dataset represents common cold, flu, and allergy cases.
IV. The Decision Tree simulates rules such as:
a. IF Fever + Cough + Body Ache → Refer to Doctor
b. IF Sneezing + Runny Nose + No Fever → Home Remedy
Mild symptoms: Sneezing, coughing, sore throat, headache, runny nose.
Severe symptoms: Fever, body ache, short breath, Fatigue.
The model learns these patterns automatically.
AI ALGORITHM
The project uses the Decision Tree algorithm for classification.
It learns patterns from symptom data and predicts whether a patient should be referred to a
doctor.
Tools and Technologies
I. Python
II. scikit-learn
III. pandas
IV. matplotlib (for visualization)
V. Gradio
