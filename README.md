Vital Signs: Multi-Task AI Profiler for Global Health

Project Overview

This project analyzes the World Health Organization (WHO) Life Expectancy dataset covering 193 countries. Moving beyond basic predictive modeling, this project implements a complete end-to-end AI pipeline to categorize global health tiers, detect socio-economic anomalies, and mathematically simulate the impact of future financial policies.

Key Features & Methodology

Dimensionality Reduction (PCA): Compressed 20 overlapping features into 2 primary axes ("Overall Health Wealth" and "Disease/Mortality") to map the global health landscape.

Unsupervised Health Profiling (K-Means): Grouped 193 nations into 3 distinct Health Tiers without relying on predefined human bias.

Crisis & Anomaly Detection (Tuned DBSCAN): Configured density-based clustering to automatically flag outlier nations experiencing unique localized health or economic crises.

Supervised Life Expectancy Prediction: Built a Voting Regressor Ensemble (Ridge + Lasso + Random Forest) to capture both linear financial scaling and complex non-linear health boundaries.

Prescriptive Policy Simulator: Engineered a "What-If" sensitivity analysis to test a 10% global increase in health expenditure, proving that financial inflation alone does not raise life expectancy without underlying infrastructure improvements.

Technologies Used

Language: Python

Data Processing: Pandas, NumPy

Machine Learning: Scikit-Learn (PCA, K-Means, DBSCAN, Ridge, Lasso, Random Forest, VotingRegressor)

Visualization: Matplotlib, Seaborn

Why This Matters (SDG 3 Impact)

This pipeline successfully demonstrates how advanced ensemble algorithms can transition from predictive analytics (guessing the future) to prescriptive analytics (advising on real-world policy). It highlights that achieving UN Sustainable Development Goal 3 requires holistic, multi-faceted intervention rather than isolated financial changes.

How to Run the Project

Clone the repository: git clone https://github.com/yourusername/vital-signs-ai.git

Install dependencies: pip install pandas numpy scikit-learn matplotlib seaborn

Run the Jupyter Notebook to view the full pipeline and policy simulation.
