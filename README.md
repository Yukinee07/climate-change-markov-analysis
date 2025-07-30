# Climate Change Emissions Analysis Using Markov Chain Modeling 🌍📊

A rigorous analytical project investigating the dynamics of greenhouse gas emissions and their long-term impact on global climate change by applying discrete-time homogeneous Markov chain models.

---

## Project Overview

Climate change, fueled by increasing greenhouse gas emissions, poses one of the most critical challenges worldwide. This project analyzes carbon dioxide (CO₂) and other potent greenhouse gases' historical emission data from ten key countries — Australia, Ukraine, Malaysia, United Kingdom, Russia, India, France, Japan, Germany, and Canada.

By employing Markov chain models, we examine emission state transitions over time, calculate steady-state probabilities, and forecast the persistence of emission levels. This offers a mathematical and data-driven approach to understand which factors most significantly influence climate change and aids in the formulation of targeted mitigation policies.

---

## What is the Problem?

- The rapid and unprecedented rise in atmospheric greenhouse gases exacerbates global warming.
- Identifying which gases and which nations contribute most to sustained high emissions remains complex.
- Current prediction methods require robust mathematical models that consider temporal state dependencies.

---

## Solution Approach

- **Markov Chain Modeling**: Utilizes transition probability matrices and stochastic processes to model emission level changes.
- **State Classification**: Emissions categorized into Low, Medium, and High states based on statistical thresholds.
- **Eigenvalue and Steady-State Analysis**: Computes long-term probabilities of persistent emission states and convergence time.
- **Country- and Gas-Specific Analysis**: Distinguishes key driving factors and regional emission behaviors.

---

## Tools and Technologies Used

- Python (with NumPy, pandas for data processing and analysis)
- Linear algebra for Markov chain computations (eigenvalues, eigenvectors)
- Microsoft Excel and CSV for dataset management
- Detailed technical report in Word/PDF format documenting methodology, results, and insights.

---

## How to Use This Repository

### 1. Dataset

- The project uses historical GHG emissions data sourced from World Bank datasets covering years from 1970 to 2023.
- Data covers CO₂ and combined other Greenhouse gases (HFCs, PFCs, SF₆).

### 2. Code

- Python scripts perform data cleaning, Markov chain modeling, computation of transition matrices, steady-state probabilities, and visualization.
- Key functionality includes:
  - Defining and populating transition matrices per country and gas.
  - Computing eigenvalues/vectors, steady-state distributions, and convergence times.
  - Reporting long-term emission trends and state stability.

### 3. Report

- A comprehensive project report presenting introduction, problem statement, related works, detailed methodology, full result analysis, and conclusive insights.
- Includes tables, charts, and interpretive discussion of country-wise emission trends and implications.

### 4. Running the Code

- Install necessary Python packages (numpy, pandas).
- Load datasets into dataframes.
- Configure classification thresholds and Markov transition matrices.
- Execute scripts to generate analyses and results.
- Refer to the project report for interpretation.

---

## Repository Contents
/datasets            # Raw and processed greenhouse gas emission data
/analysis_scripts    # Python scripts for Markov modeling & calculations
/outputs             # Transition matrices, steady-state distributions, plots
/Project_Report.pdf  # Full detailed project documentation and findings
/README.md           # This file.


---

## Key Findings

- CO₂ emissions are the leading long-term driver of climate change in the analyzed countries.
- Several developing nations show strong convergence to persistently high emission states.
- Other greenhouse gases contribute less consistently but remain important in select regions.
- Without mitigation, many countries are forecasted to sustain high emission levels, urging urgent policy interventions.

---

## References

- World Bank Greenhouse Gas Emissions Datasets
- Liu & Raftery, 2021; Karasoulas et al., 2023; Wan et al., 2024, and other related research.

---

## Contributors

- Muhammad Umair Asyraaf Bin Samsuri
- Yusuf Mohammad Yunus
- Alnatsheh Huthifa M J
- Muhammad Aiman Bin Abdul Raza

---
_For detailed methodology and results, please consult the [Project Report PDF](Project_Report.pdf) included in this repository._


