Project Overview

This project is a real-time patient monitoring dashboard designed as a case study for a Philips R&D internship. It simulates the continuous monitoring of patient vitals such as Heart Rate, Blood Pressure, and SpO₂, detects abnormalities, and visualizes them dynamically on an interactive dashboard.
The system demonstrates Model-Based System Engineering, System Integration, and Automation

Key Features
Real-Time Data Simulation: Generates continuous patient vital readings every second.
Alert System: Automatically detects abnormal vitals using threshold-based logic.
Interactive Dashboard: Displays live charts and alert classifications.
Multi-Patient Monitoring: Tracks multiple patients simultaneously.
Deployment-Ready: Runs in Google Colab with Dash and Plotly.

| Technology    | Purpose                             |
| ------------- | ----------------------------------- |
| Python        | Core programming language           |
| Pandas        | Data processing                     |
| Plotly / Dash | Interactive dashboard visualization |
| Threading     | Real-time data simulation           |
| Google Colab  | Execution environment               |


System Design
Input:
Simulated patient vitals generated programmatically.

Data fields:
PatientID
HeartRate (beats per minute)
BP_Systolic (mmHg)
BP_Diastolic (mmHg)
SpO₂ (%)

Processing
Apply alert rules for each vital sign.
Store the last 100 readings for live monitoring.

Output
Heart Rate Chart: Line chart showing trends for all patients.
BP vs SpO₂ Scatter Plot: Alerts indicated via color coding.
Real-time refresh every 2 seconds.
