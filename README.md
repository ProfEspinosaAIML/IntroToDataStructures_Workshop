# 📊 Introduction to Data Structures Workshop

Welcome to the **Intro to Data Structures Workshop** — a hands-on introduction to how data is stored, organized, and analyzed in the context of **Machine Learning**.  
This workshop is designed for students who want to bridge the gap between **theory and practice**, using Python and Jupyter notebooks as their playground.  

---

## 🔑 What You’ll Learn

- **Core Data Structures**  
  Understand the foundations of working with data in Python:
  - Lists, dictionaries, and sets.
  - Tabular data with **pandas DataFrames**.
  - Practical patterns for organizing and retrieving data efficiently.

- **Statistical Exploration**  
  Learn to summarize and interpret datasets with **Measures of Central Tendency**:
  - **Mean**: the arithmetic average.  
  - **Median**: the middle value that resists outliers.  
  - **Mode**: the most common observation.  

  And extend the analysis with **Measures of Dispersion**:
  - **Range**: how spread out the values are.  
  - **Variance and Standard Deviation**: quantify variability beyond averages.  

- **Visualization and Interpretation**  
  See the statistics come alive:
  - Plot data distributions.  
  - Highlight the **median** and other summary statistics on real-world datasets.  
  - Develop intuition for when each measure is most useful.  


## 🚀 Why This Matters

Machine Learning is built on **data representation** and **statistical understanding**.  
Before training models, practitioners must:
- Clean and structure datasets.  
- Recognize patterns in the data.  
- Understand variability and bias through descriptive statistics.  

This workshop equips you with those fundamental skills, so you can move confidently into more advanced ML concepts.


## 🛠️ How to Get Started

You’ll run this workshop in a Jupyter notebook environment, using Python libraries such as **pandas**, **matplotlib**, and **numpy**.  
The following section explains the **setup process** step by step, so you can clone the repository, install dependencies, and start experimenting with the notebooks right away.

---

# 🔧 Setup Instructions — IntroToDataStructures_Workshop

This guide explains how to set up the project locally, install dependencies, and run the Jupyter notebook.  


## 1. Clone the Repository
```bash
git clone https://github.com/ProfEspinosaAIML/IntroToDataStructures_Workshop.git
cd IntroToDataStructures_Workshop
```

## 2. Create a Virtual Environment
Using Python 3.9+ is recommended.

Git Bash / Linux / macOS:
```bash
python -m venv .venv
source .venv/bin/activate
```

PowerShell (Windows):
```bash
python -m venv .venv
.venv\Scripts\Activate
```

## 3. Install Dependencies
PS or Git Bash
```bash
pip install -r requirements.txt
```

## 4. Launch Jupyter Notebook
Make sure your virtual environment is active. Then run:
```bash
jupyter notebook
```

## 5. Replicate the working environment
This ensures you are using the same library versions and dependencies:
```bash
pip install --upgrade -r requirements.txt
```

** Now you can work on the project **

## 6. (Optional) Deactivate Environment
When done, deactivate the virtual environment with:
```bash
deactivate
```
