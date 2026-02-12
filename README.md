# Financial-Dashboard
Shiny app for financial dashboard using R

# Project-2 

## Public Financial Data for Investment Analysis with  Shiny App Dashboard 

### Team members: Vaibhav Alluri, Chaitanya Sai Pammi, Venkata Bhavana Tangirala 

## Dataset and Sources 
The dataset for this project was sourced from publicly available platforms like Yahoo 
Finance and Morningstar. Yahoo Finance provided historical performance data for the 
Motilal Oswal Flexi Cap Fund, including detailed historical NAV (Net Asset Value) data 
(Yahoo Finance). 
In addition, Morningstar offered comprehensive data on the fund’s 
holdings, sector allocations, and returns, which was crucial for understanding the overall 
composition of the fund. The Motilal Oswal Asset Management website also contributed 
valuable historical NAV data (Motilal Oswal Historical NAV), and further fund portfolio 
details were accessed via Value Research Online. 

## Choice of Inputs and Outputs 
The key input in this project was the investment amount, which allowed us to simulate 
different investment scenarios. Historical performance data was used to calculate average 
returns over various time periods. The main output was an interactive dashboard designed 
for investors, which displayed the portfolio composition across different sectors and asset 
classes using pie charts and stacked bar charts. These visualizations provided a clear 
breakdown of the fund’s holdings and sector allocations. Additionally, an investment return 
calculator was integrated to project potential returns based on user input. 

## Analysis for Dashboard Creation 
To create the dashboards, we first analyzed the portfolio composition, including the 
distribution of assets across various sectors. This helped in choosing appropriate 
visualizations like pie charts to represent sector allocation and stacked bar charts to depict 
sector-wise returns over time. We also analyzed historical performance data to calculate 
average returns and simulate future performance scenarios, which were incorporated into 
the investment return calculator. 
## What Went Well 
Creating the visualizations was straightforward using R and libraries like ggplot2. The charts 
provided clear, intuitive insights into the fund’s structure. 

## What Was Challenging 
Integrating the visualizations into the Shiny app and ensuring smooth interactivity required 
careful planning, as did debugging the dynamic components. 

## Conclusion 
This project successfully combined financial data with interactive visualizations, helping 
investors understand portfolio performance and make informed investment decisions. 

## Link of the shiny app: 

https://clarksonuniv.shinyapps.io/Vaibhav_Chaitanya_Bhavana_Project_2/ 

## Citations 
1. Yahoo Finance. (n.d.). Motilal Oswal Flexi Cap Fund – Historical Data. Retrieved 
December 3, 2024, from https://finance.yahoo.com/quote/0P00012ZRM.BO/history 
2. Motilal Oswal Asset Management. (n.d.). Historical NAV. Retrieved December 3, 
2024, from https://www.motilaloswalmf.com/nav/historical-nav 
3. Value Research Online. (n.d.). Motilal Oswal Flexi Cap Fund Direct Plan – Portfolio. 
Retrieved December 3, 2024, from 
https://www.valueresearchonline.com/funds/26125/motilal-oswal-flexi-cap-fund
direct-plan/?utm_source=direct-click&utm_medium=vro
funds&utm_content=Motilal+Oswal+Flexi+Cap+Fund&utm_campaign=vro
search#fund-portfolio 
4. Morningstar India. (n.d.). Motilal Oswal Flexi Cap Fund Direct Plan - Detailed 
Portfolio. Retrieved December 3, 2024, from 
https://www.morningstar.in/mutualfunds/f00000te7d/motilal-oswal-flexicap-dir
gr/detailed-portfolio.aspx 
