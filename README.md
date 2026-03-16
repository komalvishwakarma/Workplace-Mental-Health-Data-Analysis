# Workplace Mental Health Data Analysis

## Project Overview

Mental health has become a critical concern in today's workforce, especially in the technology and corporate sectors. This project explores mental health awareness and treatment patterns among working professionals using data from a global mental health survey.

The analysis uses **Exploratory Data Analysis (EDA)** techniques to uncover patterns, perceptions, and influencing factors related to mental health treatment, stigma, and employer support.

The objective of this project is **not to build predictive models**, but to derive meaningful insights from self-reported survey data that can help inform workplace mental health policies.

---

## Problem Statement

To identify key trends and barriers affecting mental health support and treatment among working professionals through exploratory data analysis.

---

## Dataset Overview

The dataset contains **1,259 survey responses** with **27 different features** related to mental health and workplace environment.

Key variables include:

- Age
- Gender
- Country
- Work interference due to mental health
- Mental health treatment history
- Family history of mental illness
- Employer-provided benefits
- Availability of care options
- Leave policies for mental health support

---

## Data Cleaning & Preparation

Several preprocessing steps were performed to ensure reliable analysis.

### Age Filtering
Unrealistic ages below **15** or above **80** were removed from the dataset.

### Gender Normalization
Different representations of gender were standardized.

Examples:

- "M", "male", "Malr" → **Male**
- Similar cleaning steps were applied for **Female**

### Missing Values Handling

Some variables contained missing entries:

- `self_employed`
- `work_interfere`

These were filled with **"Don't know"** or suitable placeholders to avoid dropping valuable survey responses.

---

## Exploratory Data Analysis (EDA)

The analysis explored how different demographic, workplace, and personal factors influence mental health treatment behavior.

---

## Key Findings & Insights

### Age Distribution

The highest concentration of respondents fell within the **26–35 age group**.

This group also showed the **highest proportion of individuals who had sought mental health treatment**.

---

### Gender vs Treatment

After cleaning the gender data:

- **Males were the most represented group** in the dataset.
- **Females were more likely to seek treatment** compared to males.

This suggests potential gender differences in mental health awareness or willingness to seek help.

---

### Remote Work & Treatment

Interestingly, individuals working **remotely were less likely to seek mental health treatment** compared to those working onsite.

Possible reasons include:

- Reduced social interaction
- Lower visibility of mental health struggles
- Fewer employer interventions in remote environments

---

### Employer Support & Benefits

A strong relationship was observed between **employer support and treatment-seeking behavior**.

Employees whose organizations provided:

- Mental health benefits
- Care options
- Support policies

were significantly **more likely to seek treatment**.

This highlights the importance of workplace mental health infrastructure.

---

### Family History & Work Interference

Respondents with a **family history of mental illness** were more likely to seek treatment.

Additionally, employees who reported that mental health **interfered with their work** (even occasionally) also showed higher treatment rates.

---

### Country-wise Distribution

Countries with the highest number of survey responses included:

- United States
- United Kingdom
- Canada
- India

The **United States showed the highest reported treatment rates**, likely due to better awareness and access to mental health services.

Other countries showed mixed patterns influenced by workplace culture and support systems.

---

### Communication with Supervisors

Employees who felt **comfortable discussing mental health with supervisors** were more likely to seek treatment.

This highlights the importance of **psychological safety in the workplace**.

Organizations that promote open conversations around mental health can significantly improve employee well-being.

---

## Conclusion

The analysis highlights several key factors influencing mental health treatment among working professionals, including workplace support, cultural attitudes, family history, and communication with supervisors.

The findings emphasize that organizations play a crucial role in shaping employee mental health outcomes. By providing better support systems, encouraging open conversations, and implementing mental health policies, companies can significantly improve employee well-being.

---

## Repository Structure

- README.md
- dataset
- analysis_notebook.ipynb
