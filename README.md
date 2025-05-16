
Pairs Trading Using Cointegration
=================================

This repository contains the resources and code necessary to understand and implement a pairs trading strategy using cointegration. It includes a Jupyter Notebook for hands-on implementation and a report for conceptual understanding.

Table of Contents
-----------------
- Introduction
- Project Structure
- Dependencies
- Usage
- Results

Introduction
------------
Pairs trading is a market-neutral strategy that seeks to capitalize on pricing inefficiencies between two historically correlated assets. This project applies cointegration analysis to identify asset pairs with a long-term equilibrium relationship, allowing for the generation of more reliable trading signals.

Project Structure
-----------------
- Pairs_Trading.ipynb
  → Jupyter notebook implementing the pairs trading strategy step-by-step.

- Pairs_Trading.pdf
  → Report explaining the core concepts, methodology, and findings.

Dependencies
------------
Ensure the following Python libraries are installed to run the notebook:

- numpy
- pandas
- statsmodels
- matplotlib
- seaborn

Usage
-----
Open the Jupyter notebook Pairs_Trading_Cointegration.ipynb to explore the code and run the cells step-by-step. The notebook covers the following steps:
   - Data Collection: Import and preprocess financial time series data.
   - Cointegration Testing: Use the Engle-Granger test to identify cointegrated asset pairs.
   - Signal Generation: Generate entry/exit signals based on the spread between cointegrated pairs.
   - Backtesting: Evaluate strategy performance on historical data.

Results
-------
- The strategy's performance, including trading signals and returns, is visualized and analyzed within the notebook.
- The Pairs_Trading.pdf provides a structured overview of the approach, from theory to execution, along with key insights and findings.

Feel free to explore, modify, and extend the strategy. Contributions are welcome!
