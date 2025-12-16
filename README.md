The Healthcare Mini Project is a console-based application developed using Python as part of a first-semester academic curriculum. The project aims to demonstrate how fundamental programming concepts can be applied to solve basic healthcare-related problems in a structured and logical manner. It integrates multiple small utilities into a single system to provide an introductory understanding of healthcare data handling and decision logic.

⚠ Disclaimer: This application is intended strictly for educational purposes and does not provide medical diagnosis or treatment. Users should always consult qualified medical professionals for healthcare decisions.

2. Objectives
To apply Python fundamentals in a real-world inspired project
To implement menu-driven program flow
To practice conditional logic and function design
To handle CSV files for basic data analysis
To improve problem-solving and logical reasoning skills

3. Features Description
3.1 BMI Calculator
Accepts user height and weight as input
Calculates Body Mass Index (BMI) using the standard formula
Categorizes the result as Underweight, Normal, Overweight, or Obese
Provides basic health and lifestyle suggestions based on BMI category


3.2 General Illness Symptom Checker
Collects common symptoms such as fever, cough, fatigue, body pain, etc.
Uses conditional decision logic to identify possible illness categories
Provides precautionary advice for awareness
Includes emergency warning scenarios

3.3 Age Group Analysis
Reads patient data from a CSV file
Classifies patients into predefined age groups:

Child
Teen
Young Adult
Middle Age
Senior

Displays distribution statistics for analysis

3.4 Appointment Token Generator
Accepts patient names
Generates sequential appointment tokens
Stores generated tokens in a CSV file for record keeping

4. Technologies Used
Python – Core programming language
Pandas – CSV file handling and data analysis

5. Programming Concepts Applied

Conditional statements (if-elif-else)
Functions and modular programming
Lists and variables
File handling using CSV
User input and output formatting

6. Project Structure
├── main.py
├── fake_patient.csv
├── AppointmentTokens.csv
└── README.md

7. How to Execute
Install Python on your system
Install required library:
pip install pandas


Run the program:
python main.py


Follow the menu options displayed in the console

8. Limitations
No graphical user interface
Illness checker is rule-based and not medically accurate
No persistent storage for user history

9. Future Enhancements
Add GUI using Streamlit or Tkinter
Expand symptom database
Integrate visual charts for age analysis
Improve accuracy using machine learning models

10. Team Members

Aditi Naveen Sajjan
Aishwarya Mohan Kumar
Akshara Azhagesan
Aadi Astral Lal
