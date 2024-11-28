# 3730-Project

## Prerequisites

1. Create the Python virtual environment

   ```cmd
    python -m venv venv
   ```

2. Activate the venv

   - Windows PowerShell

   ```cmd
   .\venv\Scripts\activate.ps1
   ```

   - Command Prompt

   ```cmd
   .\venv\Scripts\activate.bat
   ```

   - If neither work

   ```cmd
   .\venv\Scripts\activate (if neither work)
   ```

   - If your system says you can't run scripts, run the flollowing command in PowerShell as an administrator:

   ```cmd
   Get-ExecutionPolicy -Scope CurrentUser
   ```

   - If it is restricted or undefined, run:

   ```cmd
   Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
   ```

3. Install requirements

   ```cmd
   pip install -r requirements.txt
   ```

## Goals

1. Find stock price data from several years ago.
2. feed that data into a machine learnng model to find the best time to buy or sell stocks.
3. visualize the trends and correlations of the data to find the most useful parameters in the stock data.
