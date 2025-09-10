# 🔧 Setup Instructions — IntroToDataStructures_Workshop

This guide explains how to set up the project locally, install dependencies, and run the Jupyter notebook.  

---

## 1. Clone the Repository
```bash
git clone https://github.com/<your-username>/IntroToDataStructures_Workshop.git
cd IntroToDataStructures_Workshop

## 2. Create a Virtual Environment
Using Python 3.9+ is recommended.

> Git Bash / Linux / macOS:
python -m venv .venv
source .venv/bin/activate

> PowerShell (Windows):
python -m venv .venv
.venv\Scripts\Activate

## 3. Install Dependencies
> PS or Git Bash
pip install -r requirements.txt

## 4. Launch Jupyter Notebook
Make sure your virtual environment is active. Then run:
jupyter notebook

## 5. Replicate the working environment
This ensures you are using the same library versions and dependencies:
pip install --upgrade -r requirements.txt

** Now you can work on the project **

## 6. (Optional) Deactivate Environment
When done, deactivate the virtual environment with:
deactivate
