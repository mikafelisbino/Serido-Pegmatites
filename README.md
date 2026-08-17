# Serido-Pegmatites
Data analysis and machine learning project developed in Python using Google Colab. The data comes from mapped pegmatites in the Seridó Province (RN-PB), northeastern Brazil.

# Statistical Analysis and Data Exploration of Pegmatite Dikes from the Seridó Pegmatite Province

This repository contains the computational workflow developed as part of an undergraduate research project and Bachelor's thesis, focusing on the statistical characterization of pegmatite dikes within the Seridó Pegmatite Province, northeastern Brazil.

The study employs Python-based data analysis techniques to investigate the geometric properties of mapped pegmatite bodies, providing quantitative support for geological interpretation through exploratory data analysis and statistical inference.

---

## Project Overview

Pegmatite dikes were previously mapped using high-resolution aerial imagery and false-color Principal Component Analysis (PCA) composites within a Geographic Information System (QGIS). Geometric attributes extracted from these mapped bodies constitute the dataset analyzed in this study.

The notebook documents the complete analytical workflow, including data preprocessing, exploratory statistical analysis, sampling methods, and statistical inference.

---

## Dataset

The dataset includes geometric and spatial attributes of pegmatite bodies, such as:

- Pegmatite identification code
- Dike length
- Thickness (when available)
- Azimuth
- Centroid coordinates
- Classification into 19 sub-swarms

The data were produced during geological mapping conducted for academic research purposes.

---

## Objectives

The primary objectives of this study are:

- Perform data cleaning and preprocessing.
- Explore the statistical properties of pegmatite geometries.
- Characterize the distribution of dike lengths and thicknesses.
- Assess sampling variability through Bootstrap resampling.
- Demonstrate the Central Limit Theorem using the geological dataset.
- Compare statistical behavior among different pegmatite sub-swarms.
- Support geological interpretation through quantitative statistical analysis.

---

## Methodology

### 1. Data Import

- Import raw dataset
- Correct formatting inconsistencies
- Convert variables to appropriate data types

### 2. Data Preprocessing

The preprocessing workflow includes:

- Removal of invalid observations
- Handling missing values
- Duplicate detection
- Validation of azimuth measurements
- Standardization of numerical variables

### 3. Exploratory Data Analysis (EDA)

The exploratory analysis includes:

- Histograms
- Boxplots
- Scatter plots
- Descriptive statistics
- Measures of central tendency
- Measures of dispersion
- Comparative analyses among pegmatite sub-swarms

---

## Statistical Methods

The notebook applies several classical statistical techniques, including:

- Descriptive Statistics
- Frequency Distributions
- Skewness Analysis
- Central Limit Theorem
- Bootstrap Resampling
- Confidence Interval Estimation
- Comparison between Mean and Median

The analyses indicate that pegmatite length distributions exhibit strong positive skewness, suggesting that the median provides a more robust measure of central tendency than the arithmetic mean.

---

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Statsmodels
- Google Colab
- QGIS

---

## Repository Structure

```
.
├── Serido_Pegmatites.ipynb
├── README.md
└── data/
```

---

## Installation

Clone this repository:

```bash
git clone https://github.com/mikafelisbino/Serido-Pegmatites.git
```

Install the required Python packages:

```bash
pip install pandas numpy matplotlib seaborn scipy statsmodels
```

Open the notebook using Google Colab or Jupyter Notebook and execute the cells sequentially.

---

## Main Outcomes

- Comprehensive preprocessing of the geological dataset.
- Statistical characterization of pegmatite geometries.
- Application of the Central Limit Theorem to geological data.
- Confidence interval estimation using Bootstrap resampling.
- Comparative statistical analysis among pegmatite sub-swarms.

---

## Author

**Mika Rodrigues Felisbino**

Bachelor's Thesis — University of São Paulo (USP)

This repository contains the computational analyses developed during the Data Analysis and the Machine Learning for Geosciense courses with data from my undergraduate research project on the characterization of pegmatite dikes from the Seridó Pegmatite Province.
