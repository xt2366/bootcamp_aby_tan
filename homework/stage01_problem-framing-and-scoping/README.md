# Project Title: To what extent do external risk factors (climate change, raw material costs, consumer demand shifts) affect Patagonia’s revenue?

**Stage:** Problem Framing & Scoping (Stage 01)

## Problem Statement
* Patagonia’s revenue depends on a mix of internal performance and external risks that are difficult to control. Rising raw material costs (e.g., cotton, wool), shifts in consumer demand toward sustainable products, and climate change–related disruptions in supply chains or seasonal demand may significantly impact sales. Identifying which factors matter most provides critical insight for forecasting financial performance and assessing long-term risks.
* Revenue forecasting under uncertainty helps Patagonia plan production, manage supply chain exposure, and guide investment in sustainability initiatives. For broader stakeholders such as investors, policymakers, and ESG analysts, quantifying the link between external risks and financial performance can support better decision-making around corporate resilience.

## Stakeholder & User
* Who decides? Patagonia’s executive team
* Who uses the output? Financial planning analysts, Risk managers, sustainability officers
* Timing & workflow context: Quarterly revenue planning cycles and long-term sustainability strategy reviews


## Useful Answer & Decision
Framing: Predictive + Descriptive
Metric: Relative contribution of each external risk factor to revenue variance
Artifact to Deliver: A Python-based model that quantifies revenue sensitivity to risk factors, plus visualizations (time-series plots, factor importance charts)

## Assumptions & Constraints
<Bullets: data availability, capacity, latency, compliance, etc.>
Revenue and financial data for Patagonia (private company) may be limited; may need to use industry benchmarks, retail sector indices, or proxy data (e.g., outdoor apparel market reports).
Climate change data (temperature, weather variability) available from public datasets (NOAA, NASA).
Commodity/raw material prices (cotton, wool, polyester) available from financial data providers.
Consumer demand signals may come from retail sales indices or Google Trends as proxies.
Limited computing resources; focus on reproducible, medium-scale modeling.

## Known Unknowns / Risks
<Bullets: what’s uncertain; how you’ll test or monitor>

## Lifecycle Mapping
Goal → Stage → Deliverable
- <Goal A> → Problem Framing & Scoping (Stage 01) → <Deliverable X>
- ...

## Repo Plan
/data/ — student activity and engagement data
/src/ — processing and modeling scripts
/notebooks/ — EDA, prototyping, and reports
/docs/ — stakeholder memos, slides
README will be updated as the project advances. Repo link and updates shared with collaborators and instructors.