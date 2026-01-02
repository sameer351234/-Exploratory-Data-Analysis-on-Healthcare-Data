📌 Project Overview
This project analyzes healthcare appointment data to identify factors that influence whether patients show up for their scheduled appointments. Using Python, Pandas, and data visualization libraries, the analysis focuses on understanding patient behavior, waiting time effects, SMS reminders, and age-based trends to uncover insights that can help improve appointment attendance.

📊 Dataset
Source: Kaggle – Medical Appointment No Shows Dataset
File: KaggleV2-May-2016.csv

Records: ~110,000 medical appointments

Key Attributes:
Patient age
Scheduled date vs appointment date
SMS reminders
Attendance status (Show / No-Show)

⚙️ Features & Data Processing
Data inspection and validation
Handling missing values and duplicates
Column renaming for consistency
Date parsing and normalization

Feature engineering:
Waiting time between scheduling and appointment
Appointment day of the week
Patient age grouping

🧪 Exploratory Data Analysis (EDA)

The project includes multiple visual analyses to understand appointment behavior:
Overall Attendance Distribution
Pie chart showing show vs no-show percentage
Impact of SMS Reminders
Count plot analyzing attendance with and without SMS
Age Group Analysis
Bar chart comparing show-up rates across age groups

🔍 Key Insights
Waiting Time Matters: Longer waiting times are associated with higher no-show rates.
SMS Reminders Were Ineffective: Patients who received SMS reminders showed a higher no-show rate, indicating reminders may be targeted at high-risk patients.
Age Influences Attendance: Young adults had the highest no-show rate, while seniors showed better attendance.
Behavioral Patterns: Appointment attendance varies significantly across demographic and scheduling factors.

🛠️ Tools & Technologies
Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook
