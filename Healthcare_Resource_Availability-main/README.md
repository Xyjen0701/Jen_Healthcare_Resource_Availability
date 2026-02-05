# Healthcare_Resource_Availability

This project focuses on analyzing global healthcare disparities by predicting life expectancy using a wide range of country-level indicators from the World Bank. The goal is to understand how health outcomes are influenced by factors like healthcare access, public health investments, and socio-economic conditions, while ensuring fairness across income groups.

# Project Objective
To build a predictive model that
- Accurately estimates life expectancy across countries
- Identifies key drivers of global health outcomes
- Ensures equitable performance across all income groups

# Models & Methodology
## Models tested:
- Random Forest
- LightGBM
- XGBoost
Each model was evaluated under three configurations: baseline, feature-engineered, and bias-mitigated.

## Final model selected:
- Bias-mitigated XGBoost: chosen for its strong performance and improved fairness across income groups

## Techniques used:
- Feature engineering (rolling averages, lags, delta features)
- Bias mitigation (removed features highly correlated with income group)
- SHAP analysis for model interpretability

# Project Structure
├── Data/           # Raw and reference data

├── Docs/           # Placeholder for documentation

├── Models/         # Final saved model file

├── Notebooks/      # Holds copies of our weekly notebooks

├── Reports/        # Holds copies of our weekly reports
