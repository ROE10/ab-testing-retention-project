# ab-testing-retention-project
# A/B Test: Reducing Customer Churn with Targeted Discounts

![Project Screenshot](./reports/executive_onepager_final.pdf)  
*One-page executive summary with insights and scenario analysis.*

---

## Project Overview
This project analyzes a subscription-based e-commerce platform to determine whether a **15% discount** can reduce customer churn while maximizing revenue.  

The project focuses on:  

- Business impact assessment  
- Actionable recommendations  
- Executive-ready deliverables  

The analysis demonstrates an **end-to-end data science workflow**: dataset simulation, A/B testing, revenue modeling, segmentation, scenario analysis, visualization, and executive deliverables.  

---

## Key Objectives
- Determine if offering a **15% discount reduces overall churn**  
- Measure **net revenue impact**  
- Identify which **customer segments (High, Mid, Low CLV)** benefit most  
- Provide **data-driven recommendations**  

---

## Project Structure
ab-testing-retention-project/
├── data/
│ └── ab_test_retention_dataset.csv # Simulated dataset
├── notebooks/
│ └── 01_ab_test_analysis.ipynb # Full analysis and PDF generation
├── reports/
│ └── executive_onepager_final.pdf # Consulting-grade executive summary
├── venv/ # Virtual environment (ignored in Git)
├── requirements.txt # Python dependencies
└── README.md # Project documentation

---

## Methodology
1. **Data Preparation:** Simulated 20,000 customers with tenure, engagement, monthly spend, net revenue, churn, and customer segment (High/Mid/Low CLV).  
2. **A/B Testing:** Control (no discount) vs Treatment (15% discount).  
3. **Exploratory Analysis:** Churn trends, revenue distribution, segment-level insights.  
4. **Statistical Testing:** Two-proportion z-test and t-test to evaluate significance.  
5. **Financial Impact Analysis:** Net revenue impact before and after discounts; scenario analysis for mid-CLV customers.  
6. **Segment Analysis:** High, Mid, Low CLV to optimize discount strategies.  
7. **Executive Deliverable:** One-page PDF combining insights, charts, and scenario analysis.  

---

## Key Insights
- **Overall churn reduction:** 12.20% → 10.27%  
- **High-CLV customers:** Churn reduced from 8.79% → 5.93%  
- **Mid-CLV customers:** Moderate retention improvement  
- **Low-CLV customers:** Minimal impact  
- **Revenue impact:** Applying the discount indiscriminately reduces total revenue; targeting **high-CLV customers** maximizes ROI  
- **Scenario analysis:** Offering a **5% discount to mid-CLV customers** could improve retention while limiting revenue loss  

---

## Recommendation
- Offer the **15% discount exclusively to high-CLV customers**  
- Consider a **smaller discount for mid-CLV customers** in a follow-up experiment  
- Avoid discounting low-CLV customers — negligible retention impact  

---

## Deliverables
- **Notebook:** Full analysis, charts, statistical tests, and PDF generation  
- **PDF:** One-page consulting-grade executive summary (`reports/executive_onepager.pdf`)  
- **Scenario Analysis:** Revenue impact of mid-CLV 5% discount  

---

## Tools & Technologies
- **Python Libraries:** Pandas, NumPy, Matplotlib, Seaborn  
- **Environment:** Jupyter Notebook  
- **Output:** Charts and PDF reports  

---

License

This project is for portfolio purposes only and is not intended for commercial use.
---

Presenter

Oluwasegun Raphael
Data Analyst
