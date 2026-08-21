<div align="center">

# 🧠 AI Material Science Laboratory

### 🚀 Python • Pandas • NumPy • Matplotlib • Data Analysis • Machine Learning

<img src="https://readme-typing-svg.herokuapp.com?font=Poppins&size=24&pause=1000&color=00C2FF&center=true&vCenter=true&width=700&lines=Welcome+to+AI+Material+Science+Labs!;Python+for+Material+Engineering;Data+Analysis+%7C+Visualization+%7C+Machine+Learning;Learn+by+Hands-on+Jupyter+Notebooks" />

![Python](https://img.shields.io/badge/Python-3.12-blue?style=for-the-badge\&logo=python)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge\&logo=jupyter)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge\&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Scientific-blue?style=for-the-badge\&logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-green?style=for-the-badge\&logo=matplotlib)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange?style=for-the-badge\&logo=scikit-learn)

---

> 📚 Practical AI & Material Science notebooks for learning Python programming, data analysis, material properties, scientific visualization, Materials Project API, and machine-learning-ready data processing.

</div>

---

# 📂 Repository Structure

```text
📦 AI-Material-Science
 ├── 📁 Module_1
 │   ├── 📓 Module 1 S01.ipynb
 │   ├── 📓 Module 1 S02.ipynb
 │   ├── 📓 Module 1 S03.ipynb
 │   ├── 📓 Module 1 S04.ipynb
 │   ├── 📓 Module 1 S05.ipynb
 │   ├── 📓 Module 1 S06.ipynb
 │   ├── 📓 Module 1 S07.ipynb
 │   └── 📓 Module 1 S08.ipynb
 │
 ├── 📁 Module_2
 │   ├── 📓 Module 2 S01.ipynb
 │   └── 📓 Module 2 S02.ipynb
 │
 ├── 📄 perovskites_data.csv
 ├── 📄 perovskites_report.html
 └── 📄 README.md
```

---

# 📘 Notebook Overview

# 🔵 Module 1 — Python & Material Science Fundamentals

## 📓 Module 1 S01.ipynb

### 🏗️ Material Properties using Python

✨ **Topics Covered**

* Dictionary Creation
* Material Database
* Atomic Number
* Density
* Material Properties
* Python Basics
* Data Storage

🎯 **Learning Outcome**

✔ Learn how to organize engineering material data using Python dictionaries.

---

## 📓 Module 1 S02.ipynb

### 📊 Material Data Processing

✨ **Topics Covered**

* NumPy
* Arrays
* Scientific Computation
* Material Dataset Handling
* Data Processing
* Engineering Calculations

🎯 **Learning Outcome**

✔ Understand numerical computing techniques used in Material Science.

---

## 📓 Module 1 S03.ipynb

### 📈 Periodic Table Visualization

✨ **Topics Covered**

* Matplotlib
* Transition Metals
* Charts
* Graphs
* Scientific Visualization

🎯 **Learning Outcome**

✔ Visualize engineering datasets with professional graphs.

---

## 📓 Module 1 S04.ipynb

### 🔥 Thermal Conductivity Analysis

✨ **Topics Covered**

* Thermal Conductivity
* Material Comparison
* Bar Charts
* Data Visualization

🎯 **Learning Outcome**

✔ Compare thermal properties of different engineering materials visually.

---

## 📓 Module 1 S05.ipynb

### 📋 Multi-Material Dataset

✨ **Topics Covered**

* Pandas DataFrame
* Multiple Materials
* Material Database
* Engineering Data Analysis

🎯 **Learning Outcome**

✔ Build and analyze structured material datasets.

---

## 📓 Module 1 S06.ipynb

### 🤖 AI Workflow & Git Basics

✨ **Topics Covered**

* Pandas
* Dataset Creation
* Git Commands
* Version Control
* AI Project Workflow

🎯 **Learning Outcome**

✔ Learn professional project management using Git with AI notebooks.

---

## 📓 Module 1 S07.ipynb

### 🔑 Materials Project API Setup

✨ **Topics Covered**

* Materials Project API
* API Key Configuration
* MPRester Initialization
* Environment Variables
* `.env` Configuration

🎯 **Learning Outcome**

✔ Learn how to configure and connect Python applications to the Materials Project API.

---

## 📓 Module 1 S08.ipynb

### 🔥 Materials Data Retrieval and Visualization

✨ **Topics Covered**

* Materials Project API
* Data Retrieval
* Pandas DataFrame
* Data Visualization

🎯 **Learning Outcome**

✔ Learn how to retrieve materials data from the Materials Project API and visualize it using Python.

---

# 🟣 Module 2 — Materials Data Engineering & Analysis

## 📓 Module 2 S01.ipynb

### 🔬 Materials Project Data Retrieval & Dataset Creation

✨ **Topics Covered**

* Materials Project API
* `MPRester`
* API Authentication
* Perovskite Materials
* Band Gap Data
* Formation Energy
* Lattice Volume
* Pandas DataFrames
* Data Merging
* CSV Dataset Creation

The notebook retrieves materials matching the required chemical formulas from the Materials Project and extracts properties including **Material ID, formula, band gap, formation energy per atom, and volume**.

The retrieved datasets are converted into Pandas DataFrames, merged using `Material_ID`, and exported as `perovskites_data.csv`.

🎯 **Learning Outcome**

✔ Learn how to retrieve real materials-science data from the Materials Project API.

✔ Understand how to convert API results into structured Pandas DataFrames.

✔ Learn how to merge material-property datasets.

✔ Create a reusable CSV dataset for further AI and machine-learning analysis.

### 📊 Dataset Generated

```text
perovskites_data.csv
```

The dataset contains material information such as:

| Column             | Description                           |
| ------------------ | ------------------------------------- |
| `Material_ID`      | Materials Project material identifier |
| `Formula`          | Chemical formula                      |
| `Bandgap`          | Band gap value                        |
| `Formation_Energy` | Formation energy per atom             |
| `Volume`           | Material volume                       |

---

## 📓 Module 2 S02.ipynb

### 🧹 Materials Dataset Profiling & Missing Value Imputation

✨ **Topics Covered**

* Pandas
* Dataset Loading
* Automated Data Profiling
* `ydata-profiling`
* Missing Data Analysis
* Mean Imputation
* KNN Imputation
* Scikit-Learn
* Data Preprocessing

The notebook loads the `perovskites_data.csv` dataset generated in Session 09 and displays the first records.

It then creates an automated profiling report using `ProfileReport` and saves it as:

```text
perovskites_report.html
```

The notebook also demonstrates two missing-value handling strategies:

```text
Mean Imputation
        ↓
SimpleImputer(strategy="mean")

KNN Imputation
        ↓
KNNImputer(n_neighbors=5)
```

Both approaches are applied to the `Bandgap` column.

🎯 **Learning Outcome**

✔ Learn how to inspect a scientific dataset automatically.

✔ Generate an HTML data-profiling report.

✔ Understand missing-value problems in material datasets.

✔ Apply Mean Imputation.

✔ Apply KNN Imputation.

✔ Prepare datasets for future machine-learning workflows.

### 📄 Report Generated

```text
perovskites_report.html
```

---

# 🛠 Technologies Used

| Technology               | Purpose                         |
| ------------------------ | ------------------------------- |
| 🐍 Python                | Programming                     |
| 📊 Pandas                | Data Analysis                   |
| 🔢 NumPy                 | Numerical Computing             |
| 📈 Matplotlib            | Visualization                   |
| 📒 Jupyter Notebook      | Interactive Coding              |
| 🌐 Materials Project API | Materials Data Retrieval        |
| 🔬 MPRester              | Materials Project Python Client |
| 🤖 Scikit-Learn          | Data Preprocessing              |
| 📋 ydata-profiling       | Automated Dataset Profiling     |
| 🌳 Git                   | Version Control                 |

---

# 🎯 Learning Objectives

### Module 1

✅ Python Programming

✅ Material Property Analysis

✅ Engineering Data Handling

✅ Scientific Visualization

✅ Dataset Management

### Module 2

✅ Materials Project API

✅ Real Materials Dataset Retrieval

✅ Perovskite Data Analysis

✅ Pandas DataFrame Operations

✅ Dataset Merging

✅ CSV Dataset Creation

✅ Automated Data Profiling

✅ Missing Value Handling

✅ Mean Imputation

✅ KNN Imputation

✅ AI/ML-ready Data Preparation

---

# 🚀 Getting Started

## 1️⃣ Clone the Repository

```bash
git clone <repository-url>
```

## 2️⃣ Enter the Repository

```bash
cd AI-Material-Science
```

## 3️⃣ Install Required Libraries

```bash
pip install pandas numpy matplotlib jupyter
```

For Module 2:

```bash
pip install mp-api python-dotenv scikit-learn ydata-profiling
```

## 4️⃣ Start Jupyter Notebook

```bash
jupyter notebook
```

Open the notebooks and execute the cells one by one.

---

# 🔬 Module 2 Workflow

```text
        Materials Project API
                 │
                 ▼
        ┌─────────────────┐
        │   Module 2 S01  │
        │ Data Retrieval  │
        └────────┬────────┘
                 │
                 ▼
       Materials Properties
                 │
                 ▼
        Pandas DataFrames
                 │
                 ▼
       Merge Material Data
                 │
                 ▼
      perovskites_data.csv
                 │
                 ▼
        ┌─────────────────┐
        │   Module 2 S02  │
        │ Data Profiling  │
        └────────┬────────┘
                 │
                 ▼
       Dataset Analysis
                 │
                 ▼
        Missing Values
                 │
          ┌──────┴──────┐
          ▼             ▼
   Mean Imputation   KNN Imputation
          │             │
          └──────┬──────┘
                 ▼
        ML-Ready Dataset
```

---

# 📁 Generated Files

Module 2 generates important data-analysis files:

```text
📦 Module_2
 ├── 📓 Module 2 S01.ipynb
 ├── 📓 Module 2 S02.ipynb
 ├── 📊 perovskites_data.csv
 └── 📄 perovskites_report.html
```

---

# 🌟 Skills You'll Gain

* Python Programming
* Pandas Data Analysis
* NumPy Scientific Computing
* Material Science Data Handling
* Materials Project API
* API-Based Data Retrieval
* Perovskite Dataset Creation
* Scientific Visualization
* Dataset Profiling
* Missing Data Handling
* Mean Imputation
* KNN Imputation
* Machine Learning Data Preparation
* Git & GitHub Workflow
* Jupyter Notebook Usage

---

# 📚 Course Modules

| Module       | Topic                                       | Status |
| ------------ | ------------------------------------------- | ------ |
| Module 1 S01 | Material Properties                         | ✅      |
| Module 1 S02 | Data Processing                             | ✅      |
| Module 1 S03 | Visualization                               | ✅      |
| Module 1 S04 | Thermal Analysis                            | ✅      |
| Module 1 S05 | Material Dataset                            | ✅      |
| Module 1 S06 | AI Workflow & Git                           | ✅      |
| Module 1 S07 | Materials Project API                       | ✅      |
| Module 1 S08 | Materials Data Visualization                | ✅      |
| Module 2 S01 | Materials Data Retrieval & Dataset Creation | ✅      |
| Module 2 S02 | Data Profiling & Missing Value Imputation   | ✅      |

---

# 🔮 Future Modules

Possible upcoming topics:

```text
Module 3
│
├── Machine Learning for Materials
├── Feature Engineering
├── Regression Models
├── Classification
└── Model Evaluation

Module 4
│
├── Materials Property Prediction
├── Random Forest
├── XGBoost
├── Neural Networks
└── AI-Based Materials Discovery
```

---

# ⭐ Repository Highlights

```text
🐍 Python
      ↓
📊 Data Analysis
      ↓
🔬 Materials Project
      ↓
📋 Materials Dataset
      ↓
🧹 Data Cleaning
      ↓
🤖 Machine Learning
      ↓
🚀 AI for Materials Science
```

---

<div align="center">

## ⭐ If you found this repository useful, don't forget to Star it!

### Happy Learning 🚀

### 🧪 AI • Materials • Data • Python • Machine Learning

**Made by Murari Singh**

</div>
