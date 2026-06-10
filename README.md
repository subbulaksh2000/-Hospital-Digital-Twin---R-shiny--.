🏥 Hospital Digital Twin Dashboard using R Shiny
<p align="center">
R Shiny • Healthcare Analytics • Patient Flow • Digital Twin Simulation

Building a data-driven hospital operations dashboard to simulate patient movement, monitor healthcare performance, and support operational decision-making.

</p>
📌 Project Overview

The Hospital Digital Twin Dashboard is an interactive healthcare analytics application developed using R Shiny.

This project creates a simplified digital representation of hospital operations by integrating patient records, outpatient information, medical records, and operational indicators into a unified dashboard.

The objective is to simulate and monitor hospital performance in near real-time to support healthcare planning and improve patient experience.

🎯 Project Objectives
Monitor patient admissions and flow across hospital services
Visualise operational healthcare metrics
Analyse patient distribution and service utilisation
Support data-driven decision making
Simulate hospital capacity and operational scenarios
Build a foundation for digital twin healthcare applications
🗂 Dataset Overview

The dashboard integrates multiple healthcare datasets.

Dataset	Description
CheckPatientType.csv	Patient category and classification
Fill_Information.csv	Patient demographic and registration information
MedicalRecord1–4.csv	Medical encounter and treatment records
OutPatientDepartment.csv	Outpatient department activity
CheckBloodPressure.csv	Patient vital signs and blood pressure data
🧩 Dashboard Features
1. Executive Overview

Monitor overall hospital performance through KPI indicators.

Metrics

✅ Total Patients
✅ Active Records
✅ Average Blood Pressure
✅ Department Distribution
✅ Patient Type Breakdown

2. Patient Flow Analytics

Track patient movement and operational behaviour.

Visualisations
Patient Registration Trends
Patient Type Distribution
Service Utilisation
Operational Load Monitoring
3. Clinical Analytics

Analyse patient health information.

Visualisations
Blood Pressure Monitoring
Medical Record Distribution
Clinical Activity Overview
4. Digital Twin Simulation

Simulate operational scenarios.

Example Scenarios
Scenario	Output
Increase patient arrivals	Capacity impact
Increase department demand	Resource utilisation
Higher outpatient volume	Predicted congestion
Patient redistribution	Operational balance
🛠 Technology Stack
Frontend
R Shiny
Shinydashboard
Data Processing
dplyr
tidyr
janitor
lubridate
Visualisation
ggplot2
plotly
DT
📂 Project Structure
hospital-digital-twin-dashboard/
│
├── data/
│   ├── CheckPatientType.csv
│   ├── Fill_Information.csv
│   ├── MedicalRecord1.csv
│   ├── MedicalRecord2.csv
│   ├── MedicalRecord3.csv
│   ├── MedicalRecord4.csv
│   ├── OutPatientDepartment.csv
│   └── CheckBloodPressure.csv
│
├── app.R
├── README.md
├── screenshots/
│   ├── overview.png
│   ├── patient_flow.png
│   └── simulation.png
│
└── docs/
🚀 Installation

Clone repository:

git clone https://github.com/yourusername/hospital-digital-twin-dashboard.git

Install dependencies:

install.packages(c(
"shiny",
"shinydashboard",
"tidyverse",
"plotly",
"DT",
"janitor",
"lubridate"
))

Run:

shiny::runApp()
📈 Future Enhancements
Machine Learning prediction
Patient admission forecasting
Hospital occupancy prediction
AI healthcare assistant
Real-time dashboard integration
Digital twin scenario optimisation
💡 Key Learning Outcomes
R Shiny application development
Healthcare analytics
Dashboard design
Data integration
Operational simulation
Digital twin concepts
👩‍💻 Author

Subbulakshmi Natarajan
Data Analytics | Healthcare Analytics | Business Intelligence | R Shiny

LinkedIn: (Insert profile)

⭐ If you found this project interesting, feel free to star the repository.
