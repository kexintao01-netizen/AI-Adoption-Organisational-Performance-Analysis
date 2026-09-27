# AI-Adoption-Organisational-Performance-Analysis
This project explores the key factors associated with successful AI implementation in organisations using Python-based data analytics and machine learning techniques.
# AI Adoption & Organisational Performance Analysis

## Overview

This project explores the key factors associated with successful AI implementation in organisations using Python-based data analytics and machine learning techniques.

The analysis focuses on whether organisational AI capability, investment, and employee training are associated with improvements in business performance, including productivity, revenue growth, innovation, and cost reduction.

The main research question is:

**What are the key factors that influence successful AI implementation in organisations?**

---

## Dataset

The dataset contains **43 variables** describing organisational AI adoption and business performance.

The analysis covers factors such as:

- AI adoption rate
- AI maturity
- Years of AI usage
- Number of AI tools used
- Active AI projects
- AI budget allocation
- AI investment per employee
- Employee AI training
- Workforce reskilling

Organisational performance is evaluated using:

- Productivity change
- Revenue growth
- Innovation score
- Cost reduction

> The original dataset used for this academic analysis is not redistributed in this repository.

---

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Methodology

The project follows a structured business analytics workflow:

### 1. Data Preparation
- Checked missing values and duplicated observations
- Selected relevant AI capability and organisational performance variables
- Applied **Min-Max normalisation** to variables measured on different scales

### 2. Correlation Analysis
Correlation analysis was used to examine relationships between AI-related organisational factors and business performance indicators.

### 3. Group Comparison
Organisations were compared across:

- Different AI adoption stages
- Different levels of employee AI training

### 4. Regression Analysis
Linear regression models were developed to estimate the relationship between AI-related factors and productivity improvement.

The models were evaluated using:

- R² Score
- Mean Absolute Error (MAE)

### 5. Data Visualisation
Heatmaps, boxplots, scatterplots, and regression coefficient charts were used to communicate the main findings.

---

## Key Findings

### AI Capability

AI maturity showed the strongest relationship with productivity improvement.

The correlation between AI maturity and productivity change was approximately **0.74**, while AI adoption rate also showed a strong positive relationship of approximately **0.67**.

The AI capability regression model achieved:

- **R²: 0.557**
- **MAE: 3.001**

AI maturity had the largest positive regression coefficient among the capability variables.

The results also suggest that simply using AI for a longer period or increasing the number of AI tools does not necessarily produce stronger organisational outcomes.

---

### Investment & Employee Training

Employee AI training showed a strong relationship with productivity improvement, with a correlation of approximately **0.63**.

AI budget allocation also demonstrated a relatively strong relationship with productivity improvement, at approximately **0.60**.

The investment and training regression model achieved:

- **R²: 0.499**
- **MAE: 3.200**

Among these variables, **AI training hours** had the strongest positive regression coefficient, followed by AI budget allocation.

---

### AI Adoption Stage

Organisations at more advanced stages of AI adoption showed stronger average organisational performance.

For example, average productivity improvement increased across the adoption stages:

| AI Adoption Stage | Average Productivity Change |
|---|---:|
| None | 2.39% |
| Pilot | 6.17% |
| Partial | 12.03% |
| Full | 19.79% |

Similar patterns were observed for revenue growth, innovation, and cost reduction.

---

## Business Insights

The analysis suggests that successful AI implementation depends on more than simply adopting AI technologies.

Organisations may generate greater value from AI by focusing on:

- Building organisational AI maturity
- Investing in employee AI training and reskilling
- Integrating AI into existing workflows and decision-making processes
- Managing AI projects strategically rather than simply increasing the number of tools or projects
- Developing responsible AI governance and risk-management practices

Overall, **organisational readiness and workforce capability appear to be important components of successful AI implementation**.

---

## Limitations

This analysis focuses primarily on AI capability, investment, and employee training factors.

Governance-related variables such as data privacy, regulatory compliance, AI ethics committees, and AI risk management were identified as potentially important areas but were not fully analysed in the current project.

The results identify statistical relationships within the dataset and should not be interpreted as establishing causal relationships.

---

## Future Development

Potential extensions of this project include:

- Analysing AI governance and risk-management factors
- Applying additional machine learning models
- Comparing model performance using cross-validation
- Investigating industry-level differences in AI adoption
- Developing an AI implementation success prediction model

---

## Repository Structure

```text
AI-Adoption-Organisational-Performance/
│
├── AI_Adoption_Organisational_Performance_Analysis.ipynb
└── README.md
```

---

## Author

**Kexin Tao**

MSc Digital Engineering Management  
University College London

GitHub: `kexintao01-netizen`
