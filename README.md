# Fama-French and CAPM Model Validation: An Empirical Study on Return Predictability

Welcome to our comprehensive analysis of the Fama-French and CAPM models! This repository investigates the efficacy of widely used asset pricing models in explaining stock returns over the past 30 years, using empirical factor data sourced from the **Kenneth R. French Data Library**.

## 📊 Project Overview

The Capital Asset Pricing Model (CAPM) and the Fama-French three-factor model have long been the cornerstones of modern financial theory, used to describe the relationship between expected return and market risk. However, financial markets evolve, and so does the validity of these models. This project rigorously tests whether these models still hold up in explaining asset returns over the past three decades.

## 🧪 Key Findings

Our analysis shows that **neither CAPM nor the Fama-French models adequately explain stock returns** for the 30 years leading up to today. This challenges conventional wisdom and highlights potential gaps in these models’ ability to account for modern market dynamics. Here are some detailed observations:
- **CAPM**: Fails to account for the cross-sectional variation in stock returns, indicating a significant limitation in using a single risk factor (the market).
- **Fama-French Model**: Despite adding size and value factors, the model also falls short, leaving a substantial portion of return variability unexplained.

## 📚 Data Source

All factor data used in this analysis were sourced from the **Kenneth R. French Data Library**, a reliable and extensively cited resource in financial research. The data includes market risk, size, and value factors, which form the foundation of our validation study.

## 🛠️ Methodology

1. **Data Collection**: We pulled 30 years of monthly factor data from the Kenneth R. French Data Library and stock returns from a comprehensive financial database.
2. **Model Implementation**: Implemented the CAPM and Fama-French models to estimate factor exposures and explained variances.
3. **Performance Evaluation**: Conducted out-of-sample tests and statistical significance assessments to evaluate model effectiveness.

## 🚀 Key Takeaway

Our study raises important questions about the relevance of traditional asset pricing models in contemporary financial markets. The inability of both models to explain recent return dynamics suggests a need for more sophisticated models or the inclusion of additional factors to capture modern investment patterns.

Another interesting thought is that while the Fama French model could explain the returns back when it was introduced in 1993, it can be hypothesized that the mass publication of the results have causes the alphas to be competed away.  

## 📂 Repository Structure

- **Assignment2_v2.pynb**: The python notebook that compares the key metrics across the two models against time.
- **Assignment2_v2 tool.pynb**: The python notebook gives our users a tool to test these models for whichever period they are interested in
- **Project Report**: This is the executive memo, which presents a thorough account of the theory, analysis and findings.
- **Presentation - Empirical Finance**: This is a quick reference presentation for users to skim through the most important points
- **Excel Worksheet**: As good practice, this analysis was also performed using Excel
- **Project II Data File**: This is the data file sourced from Kenneth R French Data Library, that has been used throughout the analysis

## 💡 Future Directions

The limitations identified in this analysis open avenues for exploring alternative models, such as multi-factor models that incorporate momentum, liquidity, or even machine learning-based approaches. Further research can also focus on shorter time periods or specific sectors to identify potential anomalies.

📚 Course Project Details

This project was completed as part of FIN 684F: Investment Theory and Advanced Corporate Finance, under the guidance of Professor M. Sury. The study was a collaborative effort with my group mates:

	•	Tom Starkie
	•	Lindsay Bartol
	•	Biagio Alessandrello

We are all part of the MSBA ’25 cohort at McCombs School of Business, UT Austin.

Feel free to explore the repository, run the models, and contribute your own insights. We hope this project provides valuable food for thought for researchers and practitioners in the field of financial economics!
