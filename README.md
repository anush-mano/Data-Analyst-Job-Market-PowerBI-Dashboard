# Data Analyst Job Market Analysis — Power BI

## 📌 Project Overview

This project analyzes **Data Analyst job postings** to understand the skills employers are looking for, where jobs are located, and how jobs are offered across different work modes.

An interactive **3-page Power BI dashboard** was created to explore job market trends and provide useful insights for aspiring Data Analysts.

---

## 🛠️ Tools & Technologies

* **Power BI**
* **Power Query**
* **DAX**
* **Excel / CSV**
* **Data Cleaning & Transformation**
* **Data Modeling**
* **Star Schema**

---

## 📂 Dataset

**Dataset:** Data Analyst Job Postings
**Source:** [Kaggle — Data Analyst Job Postings](https://www.kaggle.com/datasets/asaniczka/data-analyst-job-postings)
**Author:** asaniczka

The dataset contains job posting information including:

* Job Title
* Company
* Job Location
* Search City
* Search Country
* Job Level
* Job Type
* Job Skills
* Job Summary
* First Seen Date

> **Note:** The original CSV dataset is not included in this repository because of its file size. The dataset can be accessed from the original Kaggle source above.


---

## 📊 Dashboard Pages

### 1️⃣ Overview

Provides a high-level view of the Data Analyst job market.

**Key visuals:**

* Total Job Postings
* Remote Jobs
* Job Postings by Search Country
* Job Type Distribution
* Job Level Distribution

---

### 2️⃣ Skills Analysis

Explores the skills most frequently mentioned in Data Analyst job postings.

**Key visuals:**

* Top 10 Most Demanded Skills
* Top 5 Skills by Job Type
* Skill Demand by Job Level
* Total Skill Mentions
* Interactive Job Type Slicer

---

### 3️⃣ Location & Work Mode

Analyzes where Data Analyst jobs are located and how they are offered.

**Key visuals:**

* Top 10 Job Locations
* Job Postings by Work Mode
* Work Mode by Top 10 Locations

Work modes include:

* Remote
* Hybrid
* Onsite

---

## 🧮 DAX & Data Analysis

The project uses DAX measures and calculations including:

* `SUM`
* `AVERAGE`
* `COUNT`
* `DISTINCTCOUNT`
* `CALCULATE`

The project also demonstrates:

* Measures
* Calculated Columns
* Filter Context
* Interactive Slicers
* Data Modeling

---

## 🔍 Key Analysis Areas

The dashboard allows users to explore:

* Most demanded Data Analyst skills
* Skill demand across job types
* Skill demand across job levels
* Most common job locations
* Remote, Hybrid and Onsite job distribution
* Job market information using interactive filters

---

## 📸 Dashboard Preview

### Overview

<img width="906" height="510" alt="Overview" src="https://github.com/user-attachments/assets/35a77c5f-a716-4c7d-a845-47e853023b4f" />


### Skills Analysis

<img width="906" height="508" alt="Skill_Analysis" src="https://github.com/user-attachments/assets/980f49d8-1c12-4ace-8dd7-2ddfbdf49506" />


### Location & Work Mode

<img width="905" height="506" alt="Location Work_Mode" src="https://github.com/user-attachments/assets/e4826002-dc71-4746-8edf-8e67c103df5a" />


---

## 📁 Project Structure

```text
Data-Analyst-Job-Market-PowerBI
│
├── Dashboard
│   └── Data_Analyst_Job_Market.pbix
│
├── Data
│   └── postings.csv
│
├── Screenshots
│   ├── Overview.png
│   ├── Skills_Analysis.png
│   └── Location_Work_Mode.png
│
└── README.md
```

---

## 🎯 Project Objective

The objective of this project is to transform raw job posting data into an **interactive and easy-to-understand Power BI dashboard** that can be used to explore Data Analyst job market patterns.

The project demonstrates practical skills in **data cleaning, transformation, data modeling, DAX, and dashboard development**.
