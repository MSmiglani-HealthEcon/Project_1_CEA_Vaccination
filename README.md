💉 Cost-Effectiveness Analysis of a Vaccination Programme
Overview

This project conducts a cost-effectiveness analysis (CEA) of a vaccination programme aimed at preventing an infectious disease. Using a simplified economic evaluation framework, the analysis estimates total vaccination costs, healthcare costs averted, and the cost-effectiveness ratio (CER) expressed as cost per case prevented.
The project demonstrates foundational health economics concepts commonly applied in public health decision-making and vaccination policy evaluation.

Objectives
-Quantify total vaccination programme costs
-Estimate the number of disease cases prevented
-Calculate treatment costs averted due to vaccination
-Determine net programme cost
-Compute the cost-effectiveness ratio (CER)

Project Structure
Health-Economics-P1_Cost-Effectiveness-Vaccination/
│
├── data/
│   └── vaccination_inputs.csv
│
├── notebooks/
│   └── P1_cost_effectiveness_vaccination.ipynb
│
├── outputs/
│   └── cost_effectiveness_results.csv
│
├── report/
│   └── Project_1_Vaccination_CEA_Report.docx
│
└── README.md

Health Problem Addressed
-Infectious diseases impose substantial clinical and economic burdens on healthcare systems. Vaccination programmes are a core preventive public health strategy, but require upfront investment. Health economic evaluation helps policymakers determine whether such programmes represent good value for money relative to treatment costs avoided.

Data Sources
-Dataset: vaccination_inputs.csv

Parameters included:
-Target population size
-Vaccine cost per person
-Administration cost per person
-Baseline disease incidence
-Vaccine efficacy
-Treatment cost per case

All parameters are illustrative and used for educational demonstration.

Methodology
1. Cost Estimation

Total vaccination cost calculated as:
𝑃𝑜𝑝𝑢𝑙𝑎𝑡𝑖𝑜𝑛×(𝑉𝑎𝑐𝑐𝑖𝑛𝑒 𝐶𝑜𝑠𝑡+𝐴𝑑𝑚𝑖𝑛𝑖𝑠𝑡𝑟𝑎𝑡𝑖𝑜n 𝐶𝑜𝑠𝑡)

2. Effect Estimation

Cases prevented estimated using:
Population×Baseline Incidence×Vaccine Efficacy

3. Cost Offsets

Treatment costs averted calculated as:
Cases Prevented×Treatment Cost Per Case

4. Economic Evaluation

Net cost: Total Vaccination Cost−Treatment Costs Averted

Cost-effectiveness ratio (CER):
CER= Cases Prevented/Net Cost
	​

Key Results (Example Output)
-Total vaccination cost:        INR 2,500,000
-Treatment costs averted:       INR 15,000,000
-Net cost:                      INR -12,500,000
-Cost-effectiveness ratio:      INR -41,667 per case prevented

Interpretation
-The negative net cost indicates the vaccination programme is cost-saving
-A negative CER implies the intervention both reduces disease burden and saves money
-Such outcomes strongly support adoption from an economic standpoint

Policy Relevance
-This analysis illustrates how CEA informs:
-Vaccine funding decisions
-Preventive healthcare prioritisation
-Resource allocation under budget constraints
-It mirrors methodologies used by HTA agencies, Ministries of Health, and global health organisations.

Tools & Technologies
-Python: pandas, numpy
-Jupyter Notebook
-Excel (optional for tabulation)
-Limitations & Future Extensions
-Static, single-year analysis
-No discounting or time horizon
-No quality-adjusted life years (QALYs)
-No sensitivity analysis
-Potential enhancements:
-Incremental cost-effectiveness ratio (ICER)
-Probabilistic sensitivity analysis
-Multi-year modelling with discounting
-Extension to cost-utility analysis

Author

Mansimran Singh Miglani
MSc (Medical Biotechnology & Business Management)
Aspiring Health Economist / Policy Analyst
