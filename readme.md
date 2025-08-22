# Healthcare Appointment No-Show Analysis

## Project Overview
This project analyzes a dataset of medical appointments in Brazil to identify factors that influence whether a patient will show up for their appointment. The goal is to derive insights that could help healthcare providers reduce no-show rates.

## Dataset Source
The "No-Show Appointments" dataset was sourced from [Kaggle](https://www.kaggle.com/datasets/joniarroba/noshowappointments).

## Key Questions Explored
1.  What is the overall show-up rate?
2.  Does the waiting time between scheduling and appointment affect no-shows?
3.  Do SMS reminders effectively reduce no-shows?
4.  How does a patient's age influence their likelihood to show up?

## Tools & Technologies Used
- **Python:** Core programming language.
- **Pandas & NumPy:** For data cleaning and manipulation.
- **Matplotlib & Seaborn:** For data visualization.
- **Jupyter Notebook:** For interactive analysis and documentation.

## Key Insights
- **Waiting Time is the Strongest Predictor:** Longer waiting times correlate strongly with higher no-show rates.
- **SMS Reminders Were Ineffective:** Surprisingly, the group that received SMSes had a higher no-show rate, suggesting the SMS strategy was targeted at a high-risk group and/or was not effective.
- **Age Plays a Role:** Young adults had the highest no-show rate, while seniors had the highest show rate.

## How to Run This Project
1.  Clone this repository.
2.  Ensure you have Python and Jupyter installed.
3.  Install the required libraries: `pip install pandas numpy matplotlib seaborn jupyter`
4.  Open the `healthcare_analysis.ipynb` notebook in Jupyter or VS Code and run all cells.