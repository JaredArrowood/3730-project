# Stocks-Project

## Prerequisites

1. create the virtual encvironment
   python3 -m venv venv

2. activate the venv
   .\venv\Scripts\activate.ps1 (for powershell)

   .\venv\Scripts\activate.bat (for cmdline)

   can also just try running activate if neither work

(if your system says you can run scripts, run:
Get-ExecutionPolicy -Scope CurrentUser
if it is restricted or undefined, run:
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser)

3. install requirements
   pip install -r requirements.txt

## Goals

1. Find stock price data from several years ago.
2. feed that data into a machine learnng model to find the best time to buy or sell stocks.
3. visualize the trends and correlations of the data to find the most useful parameters in the stock data.
