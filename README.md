# 🚗 ACIS Insurance Analytics

A data analytics project for **AlphaCare Insurance Solutions (ACIS)**. This project focuses on analyzing insurance claims to uncover patterns in customer risk using EDA (Exploratory Data Analysis), and ensures reproducibility with DVC.

---

## 📊 Project Overview

- **Goal:** Analyze historical claim data to optimize marketing and identify low-risk customers.
- **Task 1:** EDA — explore loss ratio, regional risk, vehicle claims, and trends.
- **Task 2:** DVC — version control for datasets, ensuring reproducibility.

---

## 🛠️ Setup Instructions

### 🔁 1. Clone the Repo

```bash
git clone https://github.com/selambeyu/acis-insurance-analytics.git
cd acis-insurance-analytics
## 2. Set up Virtual Environment
python -m venv env
source env/bin/activate  # or env\Scripts\activate on Windows


## 3. Install Dependencies
pip install -r requirements.txt
## 4. Run the Notebook
jupyter notebook notebooks/task_1_eda.ipynb

# Set up DVC
dvc init
dvc remote add -d localstorage /your/local/path
dvc pull  # Download data files tracked by DVC

