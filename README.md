
# 🏥 Hospital Digital Twin Dashboard

Interactive healthcare analytics dashboard built using **R Shiny** to simulate patient flow, monitor hospital operations, and explore healthcare insights through interactive visualisation.

---

## 📌 Overview

The Hospital Digital Twin Dashboard is an R Shiny application designed to provide an interactive representation of hospital operations.

This project integrates multiple healthcare datasets including patient information, outpatient records, medical records, and clinical indicators to support operational analysis and decision-making.

The dashboard allows users to monitor hospital activity, explore patient trends, analyse healthcare data, and simulate operational scenarios.

---

## ✨ Features

- Interactive R Shiny dashboard
- Patient analytics and monitoring
- Medical record exploration
- Blood pressure and health analysis
- Outpatient department insights
- Hospital operational visualisation
- Digital Twin simulation module

---

## 📂 Project Structure

```plaintext
hospital-digital-twin-dashboard/
│
├── app.R
├── README.md
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
├── screenshots/
│   ├── dashboard_overview.png
│   ├── patient_flow.png
│   └── simulation.png
│
└── www/
```

---

## 📊 Dashboard Pages

### Overview
- Total patients
- Summary KPIs
- Operational monitoring

### Patient Analytics
- Patient type analysis
- Patient information overview
- Patient distribution

### Clinical Analytics
- Medical records analysis
- Blood pressure monitoring
- Health metrics

### Patient Flow
- Department activity
- Outpatient trends
- Service utilisation

### Digital Twin Simulation
- Capacity modelling
- Scenario simulation
- Resource utilisation

---

## 🗃 Dataset

| Dataset | Description |
|----------|-------------|
| CheckPatientType | Patient classification |
| Fill_Information | Patient demographic information |
| MedicalRecord1–4 | Clinical and healthcare records |
| OutPatientDepartment | Outpatient activity |
| CheckBloodPressure | Patient vital signs |

---

## 🛠 Technologies Used

- R
- R Shiny
- shinydashboard
- tidyverse
- ggplot2
- plotly
- DT
- janitor
- lubridate

---

## 🚀 Installation

Clone repository:

```bash
git clone https://github.com/yourusername/hospital-digital-twin-dashboard.git
```

Move into project:

```bash
cd hospital-digital-twin-dashboard
```

Install required packages:

```r
install.packages(c(
"shiny",
"shinydashboard",
"tidyverse",
"plotly",
"DT",
"janitor",
"lubridate"
))
```

Run application:

```r
shiny::runApp()
```

---

## 📷 Dashboard Preview

### Dashboard Overview

![Overview](screenshots/dashboard_overview.png)

---

### Patient Analytics

![Patient Analytics](screenshots/patient_flow.png)

---

### Digital Twin Simulation

![Simulation](screenshots/simulation.png)

---

## 🔮 Future Enhancements

- Real-time patient monitoring
- Predictive analytics
- Machine learning integration
- Occupancy forecasting
- AI-powered healthcare insights

---

## 👩‍💻 Author

**Subbulakshmi Natarajan**

Healthcare Analytics • Data Analytics • Business Intelligence • R Shiny

LinkedIn: *(Add your LinkedIn URL)*

---

⭐ If you found this project useful, consider giving it a star.ing, feel free to star the repository.
