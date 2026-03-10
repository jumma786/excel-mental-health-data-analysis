# 📊 UK Workplace Mental Health Analysis (Excel Project)

## Project Overview
This project analyzes workplace mental health survey data from UK employees to identify the workplace factors most strongly associated with mental health issues.

The goal of the analysis is to identify the most important drivers of mental health risk so organisations can prioritise interventions that improve employee wellbeing and productivity.

The dataset was filtered to include only respondents from the United Kingdom, resulting in a sample of **1,458 respondents**. :contentReference[oaicite:0]{index=0}

---

## Business Question
How can UK organisations improve employee mental health outcomes through workplace design and support?

The analysis focuses on identifying the workplace factors most strongly associated with poor mental health outcomes.

---

## Tools Used
- Microsoft Excel
- Pivot Tables
- Data Segmentation
- Descriptive Analysis
- Data Quality Checks

---

## Data Cleaning & Validation
Several checks were performed to ensure data quality:

- Validated 1–10 scale ranges for mental health indicators
- Checked for out-of-range values
- Flagged implausible work hour values
- Standardized segmentation fields for analysis :contentReference[oaicite:1]{index=1}

---

## Key Segmentation Variables
To enable meaningful analysis, the following segmentation fields were created:

### Hours_Band
Working hours grouped into categories:

| Hours | Category |
|------|------|
| ≤35 | Up to 35 hours |
| 36–45 | Standard hours |
| 46–55 | Long hours |
| 56+ | Very long hours |

### Stress_Band

| Score | Category |
|------|------|
| 1–3 | Low |
| 4–7 | Medium |
| 8–10 | High |

### Support_Clarity
- Support available
- No support
- Not sure about support

---

## Core Metric
The key outcome measure used in the analysis is:

**Mental Health Issue Rate**

Issue Rate =  
Employees reporting a mental health issue  
÷ Total employees in segment × 100 :contentReference[oaicite:2]{index=2}

---

## Key Insights

### Stress is the strongest predictor
Employees reporting higher stress levels show dramatically higher mental health issue rates. :contentReference[oaicite:3]{index=3}

### Long working hours increase risk
Mental health issue rates increase significantly when employees work more than 45 hours per week. :contentReference[oaicite:4]{index=4}

### Hybrid work is not automatically protective
Employees working hybrid arrangements still experience high issue rates when stress levels are elevated. :contentReference[oaicite:5]{index=5}

### Lack of clarity about support increases risk
Employees who are unsure about available mental health support show higher mental health issue rates. :contentReference[oaicite:6]{index=6}

---

## Risk Hotspots Identified

High-risk groups include:

- Hybrid workers with medium or high stress
- Employees aged 36–45 experiencing high stress
- Employees working long hours under high pressure :contentReference[oaicite:7]{index=7}

---

## Recommendations

### Improve manager capability
Train managers to recognise stress early and adjust workloads where possible.

### Make support visible
Ensure employees clearly understand what mental health support services are available.

### Intervene earlier
Focus on employees reporting medium stress before issues escalate.

---

## Author
Jumma Mohammad  
Data Analyst Portfolio Project  
Birmingham, United Kingdom
