# Altman Z-Score & Financial Dashboard

This project is a quarterly financial analysis dashboard that automatically pulls company data from the SEC EDGAR API, merges it with market prices from Alpha Vantage, and computes the Altman Z-Score, a widely used measure of financial health and bankruptcy risk.  
The dashboard also calculates quarterly returns, derives key financial ratios, and visualizes trends from 2015 to the present.  
The goal is to provide a replicable, transparent, and data-driven way to evaluate the financial stability and performance of publicly traded U.S. companies.  

The Z-Score combines five financial ratios that measure liquidity, profitability, leverage, and market value:
Z = 1.2A + 1.4B + 3.3C + 0.6D + 1.0 E

Where:
A = Working Capital / Total Assets
B = Retained Earnings / Total Assets
C = Operating Income / Total Assets
D = Market Value of Equity / Total Liabilities
E = Revenue / Total Assets
The dashboard classifies Z-Score ranges into:
Z < 1.8 → Distress Zone
1.8 ≤ Z ≤ 3.0 → Grey Zone
Z > 3.0 → Safe Zone


<img width="948" height="818" alt="image" src="https://github.com/user-attachments/assets/e9a40c74-c3a3-4065-914d-5c4e08b72c6c" />
<img width="947" height="723" alt="image" src="https://github.com/user-attachments/assets/e406e3c8-c558-4234-b8b7-1776f60faf0d" />
