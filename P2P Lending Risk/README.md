# Customer Segmentation & Risk Analysis

## Project Overview

This project explores peer-to-peer (P2P) lending data from Prosper, a U.S.-based online lending platform. The goal was to identify risk trends in borrower demographics and understand which types of borrowers may present higher or lower default risk. This exploratory analysis focuses on income, occupation, DTI ratio, homeownership, and borrower location using data from 2010 to 2014.

Data used in this project was obtained from [Kaggle - Prosper Loan Data](https://www.kaggle.com/datasets/henryokam/prosper-loan-data?select=prosperLoanData.csv)


## Objectives

- Analyze borrower characteristics to assess relative risk

- Identify patterns in delinquency rates across income levels, occupations, and states

- Provide actionable insights for lenders or analysts interested in P2P credit risk

## Data Processing & Visualization Tools

Google Sheets - data cleaning; metric calculations

Tableau - data visualization

## Dashboard Preview

![P2P Lending Risk Dashboard](P2P%20Lending%20Risk.png)




View the dashboard: [Click here to view on Tableau Public](https://public.tableau.com/app/profile/ari.lim.reyes/viz/P2PLendingRisk_17442426603830/ProsperLoanRiskDashboard)


## Business Insights

#### Based on the findings from this exploratory analysis, several strategic insights emerge:

- Tighten Credit Policies for Mid-Income Borrowers: Borrowers earning between $50k–$74,999 showed the highest number of delinquencies. Prosper may benefit from re-evaluating approval criteria or interest rates for this segment, especially when paired with non-traditional occupations like “Other.”


- Enhance Risk Screening for High DTI Borrowers: Borrowers with incomes above $100k had the highest average DTI ratios (24%), suggesting that higher earners may still be overleveraged. Incorporating more detailed credit data (e.g., mortgage load, revolving debt) could improve screening.


- Geographic Risk Profiling: Maine exhibited the highest rate of delinquencies by state. Region-specific lending policies or increased monitoring may be appropriate for high-risk states.


- Occupation-Based Risk Scoring: The "Other" occupation category appears repeatedly in higher-risk borrower profiles. Developing occupation-specific risk tiers could help improve default prediction and loan pricing models.

## What I'd Do Next


Learn predictive modeling techniques to forecast default risk

