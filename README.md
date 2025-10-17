# Data Analysis and Probability Distributions

## Overview

This project explores real-world datasets to understand **statistical distributions, relationships, and predictive insights**.  
It focuses on **probability distribution visualization**, **correlation analysis**, and **basic regression/classification modeling** using Python.

The notebook integrates datasets related to student performance and heart disease, performing comparative analysis with graphical and descriptive statistics.

---

## Table of Contents
- [Datasets](#datasets)
- [Methodology](#methodology)
- [Results](#results)
- [Technologies Used](#technologies-used)
- [Usage](#usage)

---

## Datasets

1. **`student_score.csv`**
   - Contains student marks and study hours.
   - Used to model relationships and predict student performance.

2. **`heart-disease-dataset.csv`**
   - Medical dataset with patient attributes like age, cholesterol, and heart disease presence.
   - Used to study correlations and probability distributions for classification.

3. **`Excel Sample-probability-distributions-graph.xlsx`**
   - Supporting spreadsheet used for generating probability distribution graphs.

---

## Methodology

- **Data Preprocessing**:
  - Handling missing values.
  - Renaming and standardizing column labels.
  - Generating descriptive statistics.

- **Exploratory Data Analysis (EDA)**:
  - Histogram, boxplot, and distribution visualization.
  - Correlation matrix and scatter plots.
  - Comparative distribution graphs for both datasets.

- **Probability & Statistics**:
  - Computation of mean, median, variance, and standard deviation.
  - Visualization of probability density and cumulative distribution.
  - Application of normal and binomial distribution fitting.

- **Modeling**:
  - Linear regression on student scores.
  - Logistic regression or classification visualization for heart disease.

---

## Results

- Identified **strong positive correlation** between study hours and student scores.
- Found **age and cholesterol** as top correlated factors with heart disease risk.
- Demonstrated **normal-like distributions** for multiple attributes in both datasets.
- Generated multiple visualizations and Excel-supported distribution plots.

*(All figures are displayed directly in the Jupyter Notebook.)*

---

## Technologies Used

- **Language:** Python 3.9+  
- **Libraries:**
  - Pandas
  - NumPy
  - Matplotlib / Seaborn
  - SciPy / Statsmodels
  - Scikit-learn
- **Tools:**
  - Jupyter Notebook
  - Microsoft Excel

---

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/mehmet-akif/data-analysis-probability-distributions.git
   cd data-analysis-probability-distributions
   ```

2. Install required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn scipy scikit-learn
   ```

3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook Lab-4-AKIF_SIPAHI.ipynb
   ```

4. Run all cells to view:
   - Statistical analyses  
   - Probability distribution graphs  
   - Regression/classification outputs  


---


## License

This project is open-source under the **MIT License**.
