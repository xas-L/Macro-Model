# G4 Semi-Structural Macro-Financial Model

## Project Overview

This project presents a Python-based semi-structural macro-financial model focused on the G4 economies: the United States (US), United Kingdom (UK), Japan (JP), and the Euro Area (EA). The primary objective is to provide a framework for:

* **Forecasting key macroeconomic and financial variables.**
* **Conducting dynamic scenario analysis** to assess the impact of various economic shocks.
* **Evaluating debt sustainability** under different economic conditions.

This initiative was undertaken as a personal learning endeavor to deepen understanding and practical skills in quantitative finance, macroeconomic modelling, and systematic macro investing strategies.

## Core Features

* **Multi-Country Analysis:** Simultaneous modelling of the US, UK, Japan, and Euro Area.
* **Econometric Foundations:** Primarily utilizes Error Correction Models (ECM) and Vector Error Correction Models (VECM) to capture long-run equilibrium relationships and short-run dynamics.
* **Key Variable Coverage:** Includes variables such as GDP growth, CPI inflation, unemployment rates, short-term and long-term interest rates, equity indices, exchange rates, and fiscal variables (e.g., debt-to-GDP, primary balances).
* **Forecasting Engine:** Generates baseline forecasts for endogenous model variables.
* **Scenario Analysis Module:** Allows for the simulation of predefined or custom economic shocks (e.g., growth shocks, interest rate shocks, fiscal policy changes) to assess their impact on economic trajectories.
* **Debt Sustainability Assessment:** Projects debt-to-GDP ratios under baseline and alternative scenarios, facilitating analysis of fiscal vulnerabilities.
* **Python Implementation:** Developed entirely in Python, leveraging its rich ecosystem of data science and econometrics libraries.
* **Visualization:** (Intended) Generation of visual outputs (e.g., using Plotly) to display historical data, forecasts, and scenario impacts.

## Theoretical Influences & Learning Resources

The development of this model has been significantly informed by established literature and practical guides in quantitative finance and macroeconomics:

* **Quantitative Implementation:** C. Kelliher's "Quantitative Finance With Python" served as a practical guide for Python usage in data handling, time series analysis, and model estimation.
* **Debt Dynamics & Crises:** Ray Dalio's "Principles For Navigating Big Debt Crises" provided invaluable frameworks for understanding debt cycles and designing the debt sustainability analysis module.
* **Scenario Design & Geopolitics:** Marko Papic's "Geopolitical Alpha" offered a constraint-based framework for thinking about realistic policy responses and scenario construction.
* **Narrative Economics:** Robert J. Shiller's "Narrative Economics" provided insights into how prevailing stories and sentiment can influence economic outcomes, adding depth to scenario interpretation.
* **Market Reflexivity:** George Soros's "The Alchemy of Finance" contributed to a deeper understanding of market dynamics, particularly the concept of reflexivity.
* **Hedge Fund Perspectives:** Steven Drobny's "Inside the House of Money" offered context on how macro practitioners approach markets and analysis.

## Technologies Used

* **Primary Language:** Python 3.x
* **Core Data Science:** Pandas, NumPy
* **Econometrics & Statistics:** Statsmodels, SciPy, ARCH
* **Data Sourcing:** yfinance, pandas-datareader, Requests (for potential API access)
* **Visualization (Planned/Partial):** Matplotlib, Seaborn, Plotly

## Current Status & Code Availability

This project is an ongoing personal development initiative.

**Please Note:** The complete Python codebase for this model, including specific calibrations, advanced functionalities, and detailed implementation of all modules, is currently maintained in a **private repository**. This decision has been made considering its potential applicability and value as a demonstration of practical skills in professional environments.

While the core concepts and methodologies are outlined in associated documentation (such as academic papers or presentations), direct access to the full source code is restricted at this time.

## Future Development Ideas

Potential future enhancements could include:
* Expanding the range of variables or countries.
* Incorporating machine learning techniques for specific sub-modules (e.g., nowcasting, sentiment analysis).
* Developing a more interactive web-based dashboard for results visualization.
* Refining model specifications with alternative theoretical priors.
* Implementing more sophisticated backtesting and cross-validation procedures.

## Author

[Saxon Lee](https://www.linkedin.com/in/saxon-lee/?lipi=urn%3Ali%3Apage%3Ad_flagship3_feed%3BGp8GASgWTvqUGTZowwD4lA%3D%3D)

## Acknowledgements

This project has been a significant learning experience, driven by a desire to explore the intersection of economic theory, quantitative methods, and practical market analysis.
