# marketing-ab-testing-samples
Portfolio work samples demonstrating A/B testing for promo code impact on AOV in retail marketing analytics. Simulated data recreating real projects.

# A/B Testing Work Samples: Promo Code Impact on Retail AOV

Portfolio demonstrations of end-to-end A/B testing in marketing analytics, recreating analyses from my experience supporting a US retail client.

**Important Note**: These are proof-of-concept (PoC) recreations using **simulated data** that emulates real project datasets (due to NDA/privacy). Full code and dataset available in this repo for review/reproducibility.

## 1. Boosting Revenue with Promo Codes
A/B test evaluating 10% discount promo codes' impact on Average Order Value (AOV).

- Significant overall lift: +$3.34 AOV (p=0.0035, bootstrapped p=0.0001)
- Methods: EDA, assumption checks (Shapiro-Wilk, Levene’s), t-test, custom bootstrapping for imbalance, Cohen’s d
- Key skills: Statistical rigor, handling real-world issues, business translation

[View Jupyter Notebook](boosting-revenue-promo-codes.ipynb)  
[View Polished PDF Report](WorkSample-Boosting-Revenue-with-Promo-Codes.pdf)

## 2. Segmenting Promo Code Impact by Gender
Extension analyzing heterogeneous effects by gender segment.

- Females: Significant +$5.00 lift (p=0.0066, d=0.5279)
- Males: Non-significant +$2.51 lift (p=0.0890, d=0.2614)
- Methods: Segmentation, subgroup testing, bootstrapping, visualizations (violin plots)

[View Jupyter Notebook](Segmenting-Promo-Code-Impact-by-Gender_ABTesting.ipynb)  
[View Polished PDF Report](WorkSample-Segmenting-Promo-Code-Impact-by-Gender.pdf)

## How to Run
- Open .ipynb files directly in GitHub (renders code + outputs)
- Or clone the repo and run locally in Jupyter: `jupyter notebook`

Questions or want to discuss the real (anonymized) projects? Reach out!
