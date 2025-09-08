# ENEN90032 Assignment - Data Analysis

This repository contains code and notebook files for the ENEN90032 assignment.  
The analysis is based on rainfall datasets and is structured into six main questions (Q1–Q6).

## 📂 Files Included
- `enen90032_assignment_all.ipynb` → Jupyter Notebook with all assignment code and structure.
- `Q_TKN_data.csv` → Example dataset (you can replace with your own).
- `requirements.txt` → Python dependencies required to run the notebook.
- `README.md` → Instructions for setup and execution.

---

## ⚙️ Setup Instructions

Follow these steps to run the notebook on your machine:

### 1. Create a Virtual Environment

#### On Linux / macOS:
```bash
python3 -m venv venv
source venv/bin/activate
```

#### On Windows (Command Prompt):
```bash
python -m venv venv
venv\Scripts\activate
```

#### On Windows (PowerShell):
```bash
python -m venv venv
venv\Scripts\Activate.ps1
```

---

### 2. Install Dependencies

Make sure you have `pip` installed and up to date, then run:

```bash
pip install --upgrade pip
pip install -r requirements.txt
```

---

### 3. Launch Jupyter Notebook

Once dependencies are installed, launch Jupyter Lab or Notebook:

```bash
jupyter notebook
```
or
```bash
jupyter lab
```

Open `environment analysis.ipynb` and run the cells in order.

---

## ✅ Notes
- Place your rainfall datasets (CSV files) in the same folder as the notebook.
- Replace the dataset names in the notebook if you use custom files.
- Ensure your Python version is **3.8+**.

---

## 🔗 Troubleshooting
- If you get kernel errors in Jupyter, restart the kernel after activating the virtual environment.
- On Windows, if activation fails, try running PowerShell as **Administrator** and use:
  ```powershell
  Set-ExecutionPolicy Unrestricted -Scope Process
  ```
  Then activate again.

---

Happy analyzing! 🎉