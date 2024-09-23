# Edupulse-ReportHub

EduPulse ReportHub is a Streamlit-based web app designed to generate insightful student performance reports from CSV files. This app offers detailed subject-wise and overall performance analysis for educational institutions, enabling teachers and administrators to assess student outcomes with ease.

Features
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

Clone this repository:

bash
Copy code
git clone https://github.com/yourusername/edupulse-reporthub.git
cd edupulse-reporthub
Install the required dependencies:

bash
Copy code
pip install -r requirements.txt
Run the Streamlit app:

bash
Copy code
streamlit run app.py
Access the app in your browser at:

arduino
Copy code
http://localhost:8501
CSV File Format
Ensure your CSV file follows this format:

Reg No.	Name	Subject 1	Subject 2	...	Subject N
101	John Doe	85	78	...	92
102	Jane Smith	66	89	...	74
Note: The app will automatically detect non-subject columns like Reg No. and Name and exclude them from analysis.

How to Deploy
Option 1: Deploy on Streamlit Community Cloud
Push your app to a GitHub repository.
Go to Streamlit Cloud, link your GitHub repo, and deploy!
Option 2: Deploy on Heroku
Create a Procfile with the following content:
arduino
Copy code
web: streamlit run app.py
Push to Heroku using Git and deploy your app.
For detailed instructions, see Streamlit Deployment Documentation.

Report Overview
The generated report will include:

Institution Name & Department: Centered at the top of the report.
Overall Performance Summary: Including pass/fail percentages.
Subject-wise Performance: Breakdown of student success in each subject.
Multiple Subject Failure Count: A table showing the number of students who failed in 1, 2, 3, or more subjects.
Top & Least Performers: Separate sections highlighting the top 5 and least 5 students.
Customization Options
You can easily customize the app's appearance and behavior by modifying the app.py file. Feel free to:

Change the color scheme and UI elements.
Customize the report format, fonts, and additional content.
