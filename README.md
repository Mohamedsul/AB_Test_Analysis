# 🚀 A/B Testing Portfolio Project: Landing Page Optimization

## 📊 Project Overview

This project demonstrates end-to-end A/B testing analysis for a landing page optimization scenario. Using real-world data from "Practical Statistics for Data Scientists," I analyzed user engagement metrics to determine which web page presentation drives better performance.

**🎯 Business Problem**: A company selling high-value services needed to determine which of two web presentations was more effective at engaging potential customers. Due to long sales cycles, they used time-on-page as a proxy metric for sales effectiveness.

## 🔑 Key Results

- **📈 Page B showed 24.3% higher engagement** (166.1s vs 133.6s average)
- **📊 Statistical Analysis**: Not significant (p=0.318) due to small sample size
- **📏 Effect Size**: Medium effect (Cohen's d = 0.33) suggests practical difference
- **⚡ Power Analysis**: Current test has 31% power; need ~64 sessions per group for 80% power

## 🛠️ Technical Skills Demonstrated

### Statistical Analysis
- Hypothesis testing (two-sample t-tests)
- Effect size calculation (Cohen's d)
- Power analysis and sample size planning
- Confidence interval estimation
- Assumption testing (normality, equal variance)

### Python & Data Science
- **Pandas** & **NumPy**: Data manipulation and analysis
- **SciPy**: Advanced statistical testing
- **Matplotlib** & **Seaborn**: Professional data visualization
- **Jupyter Notebooks**: Interactive analysis and documentation

### Business Acumen
- A/B testing methodology
- Proxy metric validation
- Statistical vs. practical significance
- Business-focused recommendations

## 📁 Project Structure

```
ab-testing-portfolio/
├── data/
│   └── web_page_data.csv
├── notebooks/
│   ├── ab_testing_analysis.ipynb
│   └── visualization_utils.ipynb
│   └── statistical_summary.ipynb
├── results/
│   └── figures/
│       ├── distribution_comparison.png
│       ├── summary_dashboard.png
│       └── hypothesis_test_results.png
├── README.md

```

## 📊 Data Description

- **Source**: 36 user sessions across two landing pages
- **Page A**: 21 sessions (control group)
- **Page B**: 15 sessions (treatment group)
- **Metric**: Time spent on page (proxy for conversion potential)
- **Range**: 21-357 seconds of engagement time

## 🔬 Analysis Methodology

### 1. Exploratory Data Analysis
- Descriptive statistics comparison
- Distribution analysis and visualization
- Outlier detection and data quality checks

### 2. Statistical Testing
```python
# Hypothesis Setup
H₀: μ_B - μ_A = 0  (no difference)
H₁: μ_B - μ_A > 0  (Page B has higher engagement)
α = 0.05
```

### 3. Results Interpretation
- Statistical significance assessment
- Effect size calculation and interpretation
- Business impact evaluation

## 📈 Key Visualizations

### Distribution Comparison
Box plots and histograms showing engagement time distributions for both pages, revealing higher central tendency for Page B despite overlap.

### Statistical Dashboard
Professional summary visualization including:
- Mean comparison with error bars
- Individual session scatter plots
- Distribution overlays
- Test statistics summary

## 💼 Business Recommendations

### Primary Finding
While Page B shows **24.3% higher engagement**, the difference is **not statistically significant** with the current sample size.

### Recommendations
1. **Short-term**: Insufficient evidence to deploy Page B immediately
2. **Long-term**: Run larger test with ~64 sessions per group for conclusive results
3. **Validation**: Monitor actual conversion rates if proceeding with Page B
4. **Methodology**: Consider A/A testing to validate measurement system

## 🚀 How to Run This Analysis

### Prerequisites
```bash
pip install pandas numpy scipy matplotlib seaborn jupyter
```

### Execution
```bash
git clone https://github.com/[username]/ab-testing-portfolio
cd ab-testing-portfolio
jupyter notebook notebooks/ab_test_analysis.ipynb
```

Or run the standalone script:
```bash
python src/ab_testing_analysis.py
```

## 📚 What This Project Demonstrates

### For Data Analyst Roles
- **Statistical rigor**: Proper hypothesis testing methodology
- **Business translation**: Converting statistical results into actionable insights
- **Experimental design**: Understanding A/B testing best practices
- **Data visualization**: Creating compelling, professional charts

### Technical Competencies
- **Python proficiency**: Clean, documented, reproducible code
- **Statistical knowledge**: Beyond basic t-tests to effect sizes and power
- **Communication skills**: Technical results explained for business stakeholders
- **Project organization**: Professional structure and documentation

## 🔗 Connect & Learn More
- **Portfolio**:https://mohamedsul.github.io/portfolio/ 
- **Email**:Mohsul659@gmail.com

---

⭐ **If you found this analysis helpful, please star this repository!**

*This project showcases real-world A/B testing scenarios that data analysts encounter daily in conversion optimization and experimentation roles.*
