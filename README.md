# Social Media Addiction Analysis

![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python)  ![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

## Overview
This repository contains the code, datasets, and analysis for the dissertation:  
**“Understanding Social Media Addiction: Comparing Self-Reported and Behaviourally Calculated Addiction Levels.”**  

The study investigates social media usage patterns, identifies behavioral predictors of addiction, and compares self-reported versus behaviorally calculated addiction scores among university students. Insights aim to support digital well-being initiatives and interventions.


---

## Dataset

- **Source:** Kaggle   
- **Type:** Synthetic, generated using NumPy and pandas to simulate real-world social media usage  
- **Features:** Self-control, time spent, frequency, content genre, self-reported addiction  
- **Ethics:** Anonymized, no consent required, GDPR approval not applicable  

> Synthetic data ensures privacy while accurately simulating real-world social media behavior.

---

## Key Analyses

1. **Behavioural Addiction Calculation**
   - Computed normalized behavioral addiction scores from self-control and time spent  
   - Users categorized as Low, Medium, High addiction  

2. **Machine Learning Models**
   - Random Forest and XGBoost for prediction  
   - Hyperparameter tuning with GridSearchCV improved performance and reduced overfitting  
   - Key predictors: **self-control**, **satisfaction**, **productivity loss**  

3. **Association Rule Mining**
   - Night-time usage linked to high addiction, morning users linked to low addiction  
   - Patterns consistent in self-reported and behavioral metrics  

4. **Self-Reported vs Behavioral Addiction**
   - Participants often underestimated their addiction  
   - Highlights the importance of objective monitoring  

---

## Visualizations

- Addiction by content genre  
- Average addiction by location and platform  
- Behavioral patterns over time  
- Feature importance plots  

*(See the `plots/` folder for details.)*

---

## Ethical Considerations

- Dataset is synthetic and anonymized  
- No GDPR approval or consent required  
 

---

## Limitations & Future Work

- Small, synthetic dataset limits generalizability  
- Self-reported features may contain bias  
- Psychological and social variables (depression, anxiety, online harassment) not included  
- Future research could explore real-world consequences of social media addiction  

> Using this dataset, we analyzed factors like self-control, productivity loss, and age. Future studies could assess outcomes such as online harassment, bullying, and mental health effects, ideally with natural data instead of self-reported responses.

---

## Requirements

- Python 3.8+  
- Libraries: `pandas`, `numpy`, `scikit-learn`, `mlxtend`, `matplotlib`, `seaborn`  

Install dependencies via:

```bash
pip install -r requirements.txt
