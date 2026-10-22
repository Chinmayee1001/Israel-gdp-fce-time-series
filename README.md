# Israel GDP–FCE Time-Series Analysis (1970–2025)

## Project Overview

This project examines the long-run relationship and short-run dynamics between Gross Domestic Product (GDP) and Final Consumption Expenditure (FCE) in Israel over the period 1970–2025. The analysis was conducted using EViews 11.

## Research Objective

To investigate the time-series properties of GDP and FCE, examine whether the variables share a long-run equilibrium relationship, and study their dynamic interactions and predictive relationships.

## Methodology

The analysis includes:

- Descriptive statistics
- Augmented Dickey–Fuller (ADF) unit root tests
- Engle–Granger cointegration testing
- Error Correction Model (ECM)
- VAR lag-length selection
- Johansen cointegration testing
- Vector Error Correction Model (VECM)
- Toda–Yamamoto causality testing
- Impulse Response Functions (IRF)
- Forecast Error Variance Decomposition (FEVD)
- VECM residual diagnostic tests

## Key Findings

- Both logged GDP and logged FCE were non-stationary in levels and stationary in first differences, consistent with I(1) processes.
- The Johansen procedure indicated one cointegrating relationship at the 5% significance level.
- The Engle–Granger residual-based test provided only borderline evidence of cointegration at the 10% level.
- In the VECM, the adjustment coefficient for FCE was statistically significant at the 5% level, while the GDP adjustment coefficient was not.
- The Toda–Yamamoto modified Wald tests did not find statistically significant Granger causality in either direction at the 5% level.
- Residual diagnostics indicated serial correlation, non-normality, and heteroskedasticity, which warrant caution when interpreting statistical inference.

## Limitations

The findings describe statistical relationships and dynamic interactions; they do not establish structural causality. The residual diagnostic results suggest that inference should be interpreted cautiously. Interpretation also depends on the price basis and measurement of the underlying GDP and FCE series.

## Repository Contents

- `report/` — Final project report in PDF format.
- `eviews/` — EViews workfile used for the analysis.

## Software

EViews 11

## Author

Economics postgraduate research project.
