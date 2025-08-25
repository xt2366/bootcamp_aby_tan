# External Risk Factors and Revenue Sensitivity: A Case Study on Patagonia

**Stage:** Problem Framing & Scoping (Stage 01)

## Problem Statement
* **To what extent do external risk factors (climate change, raw material costs, consumer demand shifts) affect Patagonia’s revenue?**
* Patagonia is an American outdoor clothing and gear brand founded in 1973 by Yvon Chouinard, known for its commitment to high-quality, durable products and significant environmental activism. The company donates 1% of its sales to environmental nonprofits through its "1% for the Planet" initiative, runs a program to repair and resell its own clothing through its Worn Wear program, and has a mission to "save our home planet".
* Patagonia’s revenue depends on a mix of internal performance and external risks that are difficult to control. Rising raw material costs (e.g., cotton, wool), shifts in consumer demand toward sustainable products, and climate change–related disruptions in supply chains or seasonal demand may significantly impact sales. Identifying which factors matter most provides critical insight for forecasting financial performance and assessing long-term risks.
* Revenue forecasting under uncertainty helps Patagonia plan production, manage supply chain exposure, and guide investment in sustainability initiatives. For broader stakeholders such as investors, policymakers, and ESG analysts, quantifying the link between external risks and financial performance can support better decision-making around corporate resilience.

## Stakeholder & User
* **Who decides?** Patagonia’s executive team
* **Who uses the output?** Financial planning analysts, Risk managers, sustainability officers
* **Timing & workflow context:** Quarterly revenue planning cycles and long-term sustainability strategy reviews


## Useful Answer & Decision
* **Framing:** Predictive + Descriptive
* **Metric:** Relative contribution of each external risk factor to revenue variance
* **Artifact to Deliver:** A Python-based model that quantifies revenue sensitivity to risk factors, plus visualizations (time-series plots, factor importance charts)

## Assumptions & Constraints
* Revenue and financial data for Patagonia may be limited; may need to use industry benchmarks, retail sector indices, or proxy data (e.g., outdoor apparel market reports).
* Climate change data (temperature, weather variability) available from public datasets (NOAA).
* Commodity/raw material prices (cotton, wool, polyester) available from financial data providers.
* Consumer demand signals may come from retail sales indices or Google Trends as proxies.
* Limited computing resources; focus on reproducible, medium-scale modeling.

## Known Unknowns / Risks
* Patagonia is privately held so detailed revenue data may not be fully available.
* External risk factors may be correlated, making attribution difficult.
* Data granularity mismatch (e.g., quarterly revenue vs. daily commodity prices).
* Climate impacts may be long-term and nonlinear, requiring simplifying assumptions.
* Validation risk: results may be hard to benchmark against proprietary internal models.

## Lifecycle Mapping
Goal → Stage → Deliverable
1. Define the research problem: To what extent do external risk factors (climate change, raw material costs, consumer demand shifts) affect Patagonia’s revenue?\
→ stage01_problem-framing-and-scoping/\
→ Problem statement markdown + repo plan

2. Set up tools and workflow\
→ stage02_tooling-setup_slides-outline/\
→ GitHub repo, folder tree, README, slides outline

3. Strengthen Python fundamentals for analysis\
→ stage03_python-fundamentals/\
→ Practice notebooks on data manipulation & visualization

4. Acquire relevant datasets (Patagonia revenue proxies, raw material prices, climate/weather data, consumer demand indices)\
→ stage04_data-acquisition-and-ingestion/\
→ Data ingestion scripts + raw datasets in /data/

5. Store and organize datasets\
→ stage05_data-storage/\
→ Structured data files (CSV/Parquet) + schema documentation

6. Preprocess data (cleaning, missing values, aligning different data sources)\
→ stage06_data-preprocessing/\
→ Preprocessed datasets + preprocessing scripts

7. Check outliers and document risk assumptions (e.g., abnormal spikes in cotton prices, demand shocks)\
→ stage07_outliers-risk-assumptions/\
→ Outlier analysis notebook + markdown of assumptions

8. Explore the data (correlations between external factors and revenue, initial visualizations)\
→ stage08_exploratory-data-analysis/\
→ EDA notebook with summary stats, time-series plots

9. Engineer features (lagged raw material costs, seasonal demand indices, climate anomalies)\
→ stage09_feature-engineering/\
→ Feature dataset + feature engineering notebook

10. a. Model factor impacts using regression (e.g., OLS to estimate effect of external risks on revenue)\
→ stage10a_modeling-linear-regression/\
→ Regression results, coefficients, and performance metrics\
b. Build forecasting/time-series models (e.g., ARIMA for revenue, classification for “high vs low growth” periods)\
→ stage10b_modeling-time-series-and-classification/\
→ Forecasting notebook + model evaluation metrics


## Repo Plan
/data/ — student activity and engagement data\
/src/ — processing and modeling scripts\
/notebooks/ — EDA, prototyping, and reports\
/docs/ — stakeholder memos, slides\
README will be updated as the project advances.<br />
Repo link and updates shared with collaborators and instructors.