# HR_Attrition_People_analytics
This project uses an Employee Attrition dataset from Kaggle to simulate a real-world **People Analytics** workflow:
cleaning HR data, exploring drivers of attrition, training a predictive model, and generating actionable
insights for HR and leadership.

The main goal is to:
- Predict whether an employee is likely to **stay** or **leave**
- Identify key factors driving attrition
- Provide risk scores (`submission.csv`) that HR could use to prioritize retention efforts

---

## 🧩 Dataset

- Source: Kaggle – *Employee Attrition Classification Dataset*
- https://www.kaggle.com/datasets/stealthtechnologies/employee-attrition-dataset
- Target variable: `Attrition` (`Stayed` / `Left`)
- Files:
  - `data/raw/train.csv` – training data with labels
  - `data/raw/test.csv` – test data without labels
  - `data/predictions/submission.csv` – model predictions (attrition probabilities) for the test set

---

## 🗂 Project Structure

```text
.
├── data/
│   ├── raw/               # original CSVs (train/test)
│   ├── processed/         # cleaned and encoded data
│   └── predictions/       # model outputs (submission.csv)
├── notebooks/             # Google Colab / Jupyter notebooks
├── src/                   # reusable Python scripts (optional)
├── models/                # saved models (optional)
├── reports/               # executive summaries, findings, etc.
├── visuals/               # plots and dashboard screenshots
└── README.md

