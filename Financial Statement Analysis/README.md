# Financial Analysis: Rivian vs. Robinhood

## Project Overview
This project compares the financial health and performance of two high-growth companies that went IPO (initial public offering) in 2021: Rivian (ticker symbol: RIVN), and Robinhood (ticker symbol: HOOD). It provides important financial information from past years to aid in predicting the company's future outlook.
The goal is to simply analyze each company’s fundamentals and create a sensitivity analysis using metrics commonly used by investors and analysts, including revenue growth, margins, debt levels, and free cash flow.

## Objectives
- Understand and compare the financial position of two companies in different industries (EV manufacturing, and fintech investment platform)  
- Practice working with financial statement data from 10-K reports (2021-2024)  
- Build analysis tools using Google Sheets formulas and visualizations  
- Demonstrate a simplified version of financial modeling and valuation

## TL;DR

This analysis compares two high-growth companies: Rivian (EV manufacturer), and Robinhood (Fintech investment platform). Rivian’s metrics reflect a capital heavy, early stage company steadily improving its margins and cash flow. Robinhood shows the volatility of a digital business model, with rapid swings in profitability and growing debt levels despite having no physical product. Rivian appears to be progressing toward operational operational efficiency, while Robinhood’s high debt-to-equity ratio and fluctuating free cash flow suggest the need for further investigation into its long term strategy. These findings highlight how analyzing financial statements across different business models can provide valuable insights into risk, scalability and future growth potential.

## Tools Used
- Google Sheets – Data entry, formulas, charts
- EDGAR (SEC.gov) – Financial data from 10-K filings

## Dataset
- Source: Manually extracted from SEC 10-K filings for Rivian (RIVN) and Robinhood (HOOD) (2021–2024)
- Key fields:
  - Revenue  
  - Cost of Revenue  
  - Operating Expenses  
  - Gross / Net Income  
  - Total Assets  
  - Total Liabilities  
  - Shareholder Equity  
  - Operating Cash Flow  
  - CapEx

## Metrics & Analysis Performed
- Revenue Growth = % change year over year (YoY)  
- Gross Profit Margin = Gross Profit ÷ Revenue  
- Operating Expense Ratio = Operating Expenses ÷ Revenue  
- Debt-to-Equity Ratio = Liabilities ÷ Equity  
- Free Cash Flow (FCF) = Operating Cash Flow – CapEx  
- FCF Margin = FCF ÷ Revenue  
- Sensitivity Analysis for valuation inputs  
- Simple DCF Model estimating company value based on future FCF

# Financial Analysis RIVN vs HOOD

![Financial Statement Comparison Summary](Financial%20Statement%20Comparison%20Summary.png)

### ✅  Revenue Growth: How quickly each company increases its total sales year over year.

- RIVN showed exponential early growth (2,914% in 2022) likely due to launching production and delivering vehicles. This revenue growth slowed dramatically to 167% in 2023 and just 12% in 2024 due to supply chain disruptions and the company intentionally pausing production to focus on preparing for their new R2 vehicle line.

- HOOD saw a sharp -25% revenue decline in 2022 primarily due to the combined effects of a bear market, and a drop in monthly active users. This revenue growth rebounded strongly to 37% in 2023 and 58% in 2024 due to market recovery, and platform expansion with an introduction of new product offerings (IRA’s, credit cards, and brokerage services).

### ✅  Profit Margin: How much each company keeps after costs, as a percentage of revenue to show efficiency and profitability.

- RIVN has a negative gross profit margin (-188% in 2022, and -45% in 2023) meaning they spend more than they earn to produce its vehicles. They have growing revenue, but are still unprofitable and heavily in the investment phase. Although RIVN is still negative in 2024 (-24%), the improving trend suggests cost structure is getting better - perhaps with improvement in production efficiency or economies of scale starting to kick in. This analysis aligns with capital intensive industries like EV’s, which require much longer investment horizons to achieve profitability.

- HOOD reported negative net profit margin (75% in 2022, and -29% in 2023) showing their losses narrowing YoY. In 2024, they became profitable earning 47¢ for every $1 of revenue. The shift in profitability might be due to rebound trading activity, improved user monetization from the addition of services (credit card, margin, subscriptions, etc), and operational cost cutting. This analysis reveals that fintech platforms can scale profit quickly, but face their own market risks.

### ✅  Operating Expense Ratio: How much a company spends on running its business relative to its income

- RIVN spent more than 2x its revenue in 2022 (225%) just on operations, not including manufacturing costs. It cut spending dramatically over the next two years (83% in 2023, and 70% in 2024) signaling a trend in the right direction. 

- HOOD spent just under 2x its revenue in 2022 (174%) likely due to platform development, and marketing. It cut expenses over the next two years (128% in 2023, and 64% in 2024), which aligns with the company turning profitable in 2024. This suggests the company is entering a more mature phase with a leaner and better cost structure.

### ✅  Debt-to-Equity Ratio: How much a company relies on debt versus its own capital to finance operations.

- RIVN had very little debt in 2022 (0.29), but it took on more debt over the next couple of years (0.83 in 2023, and 1.35 in 2024). This increase suggests RIVN is likely taking on debt to finance operations, R&D, and factories, which is expected for a capital-intensive growing company.

- HOOD reported moderate debt in 2022 (0.70), but more than doubled its debt over the next couple of years (1.63 in 2023, and 2.28 in 2024). This increase might signal more aggressive expansion or financial risk, which investors may watch closely.

### ✅  FCF Margin: How much free cash a company earns for every $1 of revenue to understand profitability from cash flow.

- RIVN was initially burning more than double its revenue in cash (-222% in 2022), but reported tremendous improvement (-86% in 2023, and -11% in 2024) nearly breaking even on cash flow in 2024. These results suggest RIVN is scaling efficiently and could hit positive FCF soon.

- HOOD reported negative cash flow in 2022 (-58%), then showed a huge positive cash flow in 2023 (94%) potentially due to higher revenues from newly released services. But cash flow dipped slightly back to negative in 2024 (-0.30%), which raises questions about cash flow challenges. 

### ✅  Sensitivity Analysis RIVN vs. HOOD

A sensitivity analysis was created to understand how changes in key variables (revenue growth, margins, etc.) impact the financial outcome and future performance for RIVN and HOOD. This measurement is used to help assess risk and uncertainty in forecasts and models.

To assess the financial resilience and profitability potential of RIVN and HOOD, a sensitivity analysis using the base year 2024 was conducted. The analysis modeled 2025 FCF outcomes under various assumptions of revenue growth (0% to 30%) and gross margin (40% to 60%).

- RIVN benefits significantly from higher gross margins. Even without revenue growth, it turns cash flow positive at 50% gross margin. These results show if RIVN can scale production and increase gross margin, achieving a positive FCF is highly attainable.

![RIVN Sensitivity Table](RIVN%20Sensitivity%20Table.png)


- HOOD is highly sensitive to both gross margin and revenue growth. Even as revenue growth increases, gross margin has to increase significantly to achieve a positive FCF. These results show if HOOD can shift toward higher margin products they could scale to a positive FCF.

![HOOD Sensitivity Table](HOOD%20Sensitivity%20Table.png)

## Where to Invest

While both Rivian and Robinhood are high-risk investments, Rivian carries greater uncertainty due to its heavy cash burn, unproven production scale, and dependence on future vehicle success. Robinhood, though facing regulatory and market risks, has shown signs of profitability and operates with lower capital intensity. Investors should assess their risk tolerance before investing with either company.

## What Next?
- Add more companies for comparison  
- Incorporate real-time data using APIs (e.g., Yahoo Finance or Alpha Vantage)   
- Create an interactive Tableau dashboard to visualize changes in metrics over time

## Links
- Google Sheets (View Only)**: [Financial Statement Analysis - Sheets](https://docs.google.com/spreadsheets/d/1Ua-LBp_QRy8ak5t_DwKuKpUFflWGAKySn7LgvB4jA_g/edit?usp=sharing)

