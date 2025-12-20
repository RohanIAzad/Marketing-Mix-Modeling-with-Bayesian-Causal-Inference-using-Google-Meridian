## Marketing Mix Modeling with Bayesian Causal Inference using Google Meridian

This repository demonstrates an end-to-end Marketing Mix Modeling (MMM) workflow using Google Meridian, an open-source Bayesian framework for estimating the causal, incremental impact of marketing channels on business outcomes.

The project walks through theory, data exploration, modeling assumptions, channel selection, Bayesian estimation, and budget optimization, focusing on decision-oriented causal inference rather than attributio


### Repository Structure
```
├── EDA.ipynb
│   Exploratory data analysis:
│   - Spend distribution & coverage
│   - Time series trends
│   - Correlation analysis
│   - Multicollinearity (VIF)
│
├── MMM Project.ipynb
│   Core modeling notebook:
│   - Channel selection
│   - Meridian configuration
│   - Bayesian MMM estimation
│   - Contribution & response curve analysis
│   - Budget optimization
│
├── data/
│   ├── MMM_Data_synthetic_modified.csv
│   └── model_input2.csv
│
├── outputs/
│   ├── summary_output2.html
│   └── optimization_output.html
```
