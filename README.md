# Streaming Platform Analysis Project 🎬📊

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)
[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange)](https://jupyter.org/)

An analytical project exploring TV show trends across streaming platforms, providing insights for content strategy and viewer engagement.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Dataset Description](#dataset-description)
3. [Key Analyses](#key-analyses)
4. [Technical Stack](#technical-stack)
5. [Getting Started](#getting-started)
6. [Sample Findings](#sample-findings)
7. [Contributors](#contributors)


## Project Overview
This project analyzes TV show distribution across major streaming platforms (Netflix, Hulu, Prime Video, Disney+) to identify:
- Genre popularity trends
- Rating distribution patterns
- Platform-specific content strategies
- Predictive relationships between critic scores

**Key Objectives:**
1. Identify high-performing content characteristics
2. Compare platform rating distributions
3. Predict IMDb scores from Rotten Tomatoes ratings
4. Provide actionable insights for content development

## 🗄️ Dataset Description
The dataset contains TV show information with the following features:

| Feature        | Type      | Description                          |
|----------------|-----------|--------------------------------------|
| Title          | Nominal   | Show name                            |
| Year           | Interval  | Release year                         |
| Age            | Ordinal   | Content rating (e.g., 18+, 16+)      |
| IMDb           | Ratio     | Rating (0-10 scale)                  |
| Rotten Tomatoes| Ratio     | Score percentage (0-100%)            |
| Netflix/Hulu/Prime Video/Disney+ | Binary | Platform availability (1/0) |

**Data Quality:** 
Contains 2,500+ entries with checks for:
- Missing values handling
- Duplicate removal
- Outlier detection
- Data type validation

## Key Analyses
### Exploratory Data Analysis
- Distribution visualizations (histograms, box plots)
- Platform availability comparisons
- Age rating distributions
- Score correlation analysis (IMDb vs Rotten Tomatoes)

### Hypothesis Testing
- T-tests for rating differences between platforms
- Confidence interval calculations (95% confidence level)
- Statistical significance testing

### Predictive Modeling
- IMDb score prediction using Linear Regression
- Feature engineering for improved accuracy
- Model evaluation (RMSE, R² scores)

## Technical Stack
**Core Libraries:**
- **Data Handling:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn
- **Statistics:** SciPy, Statsmodels
- **Machine Learning:** Scikit-learn
- **Web Scraping:** BeautifulSoup

**Tools:**
- Jupyter Notebook
- Python 3.8+

## 🚀 Getting Started
### Prerequisites
- Python 3.8+
- Jupyter Notebook

### Installation:

### 1. Clone Repository

```bash
git clone https://github.com/moaahil1110/streaming-platform-analysis.git
```

### 2. Run It on Jupyter Notebook
  **a) In the Jupyter interface, click on:**
```bash
streaming-platform-analysis.ipynb
```
  **b) Run all cells sequentially:**
  
  **c) View results inline with code**


## Sample Findings:
- Platform-specific rating distributions (Netflix vs Hulu)
- Strong correlation (r = 0.78) between IMDb and Rotten Tomatoes scores
- Regression model achieves R² score of 0.63
- Significant rating differences between platforms (p < 0.05)

**Contributors:**

1. <a href="https://github.com/moaahil1110"> moaahil1110</a>

2. <a href="https://github.com/Shehzaad-khan"> Shehzaad-khan</a>

3. <a href="https://github.com/MohammedAffanKhan779"> MohammedAffanKhan779</a>

4. <a href="https://github.com/mohdmirpes"> mohdmirpes</a>
