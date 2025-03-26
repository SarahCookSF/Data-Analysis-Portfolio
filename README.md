# Data-Analysis-Portfolio

# Smoking Regression Analysis (BRFSS 2015 - Louisiana)

This project uses BRFSS (Behavioral Risk Factor Surveillance System) 2015 survey data for Louisiana to explore correlations between smoking and variables such as sex, marital status, and binge drinking behavior.

## Tools
- Stata `.do` file for variable generation, regression analysis, and heteroskedasticity tests

## Key Findings
- Women are ~2.9% less likely to smoke than men.
- Married individuals are ~4.6% less likely to smoke than those never married.
- Binge drinkers show a slight negative correlation with smoking (~1.76%).
- Pregnant women are ~5.23% less likely to smoke than non-pregnant women.

Both Breusch-Pagan and White tests indicate evidence of heteroskedasticity in initial models, which was reduced in models replacing `sex` with `pregnant`.

## File
- `smoking_regression_analysis.do`: Full Stata script including regression modeling and interpretation.
