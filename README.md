# Edupulse-ReportHub

EduPulse ReportHub is a Streamlit-based web app designed to generate insightful student performance reports from CSV files. This app offers detailed subject-wise and overall performance analysis for educational institutions, enabling teachers and administrators to assess student outcomes with ease.

Features:


📋 CSV File Upload: Upload student performance data in CSV format.


📊 Data Visualization: Visuals for subject-wise performance and overall student statistics.


📈 Top and Least Performers: Automatically highlights the top 5 and least 5 students based on their scores.


🧮 Pass & Fail Analysis: Calculates overall pass and fail percentages for the class and per subject.


📚 Multiple Subject Failure Count: Identifies students who have failed in multiple subjects.


📃 Downloadable Report: Generate and download a 2-page report in Word format with performance summaries.


🎨 Colorful & Customizable Report: The report is well-formatted, colorful, and professional, with a focus on readability and aesthetics.



App Interface

Welcome Page:

Provides a brief introduction and a button to proceed to the analysis page.


Upload CSV:

Users can upload a CSV file containing student marks.

The CSV should contain student details like name, registration number, and subject-wise marks.


Generate Report:

After the CSV is uploaded, the app processes the data and generates the performance report, including:


Subject-wise pass/fail analysis.


Performance statistics for the top 5 and least 5 students.


Count of students failing in multiple subjects.



Download Report:

Users can download a detailed report in Word format with the institution name and department title included.



How to Run the App Locally


Prerequisites

Ensure you have Python installed on your system.



CSV File Format

Ensure your CSV file follows this format:


Reg No.	Name	Subject 1	Subject 2	...	Subject N


101	John Doe	85	78	...	92


102	Jane Smith	66	89	...	74


Note: The app will automatically detect non-subject columns like Reg No. and Name and exclude them from analysis.





