# Stroke Prevention at the Census Tract Level
An examination of EQI (EPA) data as it relates to health outcomes and risks (CDC), particularly that of stroke.

## Executive summary: 

**A Problem and an Opportunity**.  Stroke is a leading cause of death and long-term disability among Americans with more than 800,000 total occurrences annually in the United States. Annual costs for treatment are estimated to be $56 billion per year [6], with more comprehensive estimates reaching past $100 billion per year [8]. Yet stroke rates are highly correlated to chronic health conditions like diabetes and poor cardiovascular health and statistics from the American Heart Association suggest that as much as 80% of heart disease and stroke is preventable through intervention and lifestyle changes.

**Our Recommendation**. We recommend using a tract-level stroke prevalence model to identify communities in the US that can remain invisible within state or county-level statistics.

**Why tract-level prediction matters**.  Stroke burden varies 2.3-fold between states, but the most striking disparities are within counties — the ten highest-prevalence census tracts include four neighborhoods inside a single Ohio county (Cuyahoga / Cleveland), invisible at the state level.

**What we built**. Using CDC PLACES health data integrated with EPA Environmental Quality Index (EQI) measurements at the census tract level (71,000 tracts), we trained an XGBoost model that achieves R^2=0.99 nationwide and identifies the highest-burden neighborhoods within each state.

**This model makes targeted intervention possible using a novel level of analysis**.  Intervention strategies can include increased local public health education and screening campaigns, recreation infrastructure investment in low physical activity areas, and EMS placement decisions at neighborhood resolution — a level of granularity that even county-level surveillance cannot always provide.
<img width="468" height="413" alt="image" src="https://github.com/user-attachments/assets/c90f3a87-bafc-464e-88ea-7a03e2fd8cf1" />

