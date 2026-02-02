# Rural Development Model (CMD-Based)

**Full Project Documentation & README**  
**Last updated:** May 2025  
**Author:** Prashanth Vanam  
**Project Type:** Command Line Application (CMD)  
**Location:** India  

---

## Project Overview

The **Rural Development Model (CMD)** is a **command-line based Python application** designed to analyze village development data and generate actionable insights for rural planning.

Unlike web-based systems, this project runs entirely through the **terminal/command prompt**, making it lightweight, fast, and suitable for academic demonstrations, research experiments, and data analysis workflows.

The system allows users to:

- Input structured village development data
- Analyze infrastructure, population, and resources
- Generate development metrics and scores
- Produce rule-based recommendations
- Save outputs as reports and analysis files

This project focuses on **logic, data processing, and analytics**, without relying on any web framework.

---

## Key Objectives

- Analyze rural development indicators programmatically
- Demonstrate data-driven planning through Python
- Provide a modular and extendable analytics model
- Enable reproducible results through command-line execution

---

## Features

- **CMD-Based Execution:** Fully runs from terminal / command prompt
- **Village Data Processing:** Reads structured rural datasets
- **Development Metrics:**  
  - Population growth analysis  
  - Resource availability scoring  
  - Infrastructure evaluation  
- **Rule-Based Recommendations:**  
  - Education  
  - Healthcare  
  - Roads & transport  
  - Water & sanitation  
  - Sustainability  
- **Output Generation:**  
  - Text-based summaries  
  - Structured result files  
- **Offline Friendly:** No internet or server required

---

## Tech Stack

| Layer | Technology | Purpose |
|------|------------|---------|
| **Language** | Python 3 | Core logic & analytics |
| **Execution** | Command Line (CMD) | User interaction |
| **Data Handling** | CSV / JSON / Python Data Structures | Input & processing |
| **Logic Engine** | Rule-based Python logic | Recommendations |
| **Outputs** | Filesystem (text/data files) | Result storage |

---


---

## Installation & Setup

### 1️⃣ Prerequisites

- Python ≥ 3.10
- Git (optional)
- Command Prompt / Terminal


```bash

### 2️⃣ Clone the Repository:
git clone https://github.com/iprashanthvanam/Rural-development-model-cmd.git
cd Rural-development-model-cmd

### 3️⃣ Create Virtual Environment (Recommended):

### Windows:
python -m venv venv
venv\Scripts\activate

### Linux / macOS:
python3 -m venv venv
source venv/bin/activate

### 4️⃣ Install Dependencies:
pip install -r requirements.txt

### Running the Application (CMD):
▶ Start the Program
python manage.py

or (if structured differently):
python rural_dev/main.py

### Application Flow
User runs the program from CMD
System prompts for village data (or reads from file)
Analytics engine processes the data
Metrics are calculated
Rule-based recommendations are generated
Results are saved to the outputs/ directory

### Sample Outputs:
Development score summaries
Infrastructure gap analysis
Recommendation reports
Processed datasets

### All generated files are stored inside:
outputs/
