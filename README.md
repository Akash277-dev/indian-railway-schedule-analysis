# 🚆 Train Schedule Analysis & Interactive Route Enquiry System

> **Internship Project** — Sysslan IT Solutions  
> **Tool:** Python · Jupyter Notebook  
> **Levels Completed:** 1 through 6 (All Levels + Capstone)

---

## 📌 Project Overview

A comprehensive data analysis project built on Indian Railways schedule data. The project progresses through six structured levels — from basic data exploration to an interactive route enquiry system — demonstrating end-to-end data analysis skills using Python.

---

## 📁 Repository Structure

```
train-schedule-analysis/
│
├── Source_Code/
│   └── Train_Schedule_Analysis.ipynb   # Main Jupyter Notebook (all 6 levels)
│
├── Dataset/
│   ├── Dataset1.csv                    # Raw train schedule dataset
│   └── cleaned_dataset.csv            # Cleaned & preprocessed dataset
│
├── Outputs/
│   ├── level4_visualization.png        # Journey Duration & Station Traffic Analysis
│   └── level5_visualization.png        # Advanced Station × Route Type Analysis
│
└── README.md
```

---

## 🔢 Project Levels

| Level | Title | Key Work |
|-------|-------|----------|
| **1** | Basic Data Review | Loaded dataset, inspected shape, dtypes, null values, basic stats |
| **2** | Data Cleaning | Handled missing values, standardized columns, formatted time fields |
| **3** | Exploratory Data Analysis | Frequency analysis, route distributions, station-wise counts |
| **4** | Journey Duration & Traffic Analysis | Avg duration by route type, top 15 high-traffic stations, route type distribution |
| **5** | Advanced Analysis | Station × Route Type heatmap, stacked bar charts |
| **6** | Interactive Route Enquiry System | User-input based train lookup, route filtering, live enquiry interface |

---

## 📊 Sample Visualizations

### Level 4 — Journey Duration & Station Traffic
![Level 4 Visualization](Outputs/level4_visualization.png)

**Key Findings:**
- Short routes average **2.6 hours**, Medium routes **10.5 hours**, Long routes **6.9 hours**
- **CST-Mumbai** is the highest-traffic station with 1000+ trains
- **74.1%** of all trains operate on Short routes

---

### Level 5 — Advanced Station × Route Type Analysis
![Level 5 Visualization](Outputs/level5_visualization.png)

**Key Findings:**
- **CST-Mumbai** handles the most diverse traffic — 937 Short, 34 Medium, 56 Long trains
- **Kalyan JN** leads in Long-route trains (201), making it a key intercity hub
- **Chennai Beach** and **Kurla** operate exclusively on Short routes

---

## ▶️ How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/<your-username>/train-schedule-analysis.git
   cd train-schedule-analysis
   ```

2. **Install dependencies**
   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

3. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook Source_Code/Train_Schedule_Analysis.ipynb
   ```

4. **Run all cells**  
   Go to `Kernel → Restart & Run All`

> ⚠️ Make sure `Dataset1.csv` is present in the `Dataset/` folder before running.

---

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green?logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-red)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-teal)

---

## 🏢 Internship Details

- **Organization:** Sysslan IT Solutions  
- **Project Title:** Train Schedule Analysis and Interactive Route Enquiry System Using Python  
- **Duration:** All 6 levels completed

---

## 👤 Author

**Akash**  
Aspiring Data Analyst | Python · SQL · Power BI  
[LinkedIn](https://www.linkedin.com/in/) · [GitHub](https://github.com/)
