### Effects of COVID-19 on US Economy  ###

# Introduction
 
 This report analyzes the effects of COVID-19 on the US economy, focusing on unemployment and
 participation rates across different states. The data is sourced from the Federal Reserve Economic
 Data (FRED) API and analyzed using Python.
 
 # Data Description
 
 The data used in this analysis includes unemployment rates and labor force participation rates for
 various states in the US. The data spans from January 2020 to December 2022 and is retrieved
 from the FRED API.
 The following sections provide details on how the data was retrieved and analyzed.
 
 # Data Retrieval
 
 The data was retrieved using the FRED API with the following steps:
 1. Create a FRED object using the API key.
 2. Search for and retrieve the relevant data series for unemployment and participation rates for each
 state.

# Effects of COVID-19 on US Economy

 ```python
 from fredapi import Fred
 fred_key = 'YOUR_FRED_API_KEY'
 fred = Fred(api_key=fred_key)
 # Example of retrieving data for New York
 unemployment_rate = fred.get_series('NYUR')
 participation_rate = fred.get_series('NYPR')
 ```
# Data Analysis and Visualization

 The analysis involves visualizing the unemployment and participation rates for each state. The plots
 are created using Matplotlib and Plotly, showing trends over the specified period.
 Conclusion
 The analysis reveals the impact of COVID-19 on unemployment and participation rates across
 different states. The findings highlight significant fluctuations in these rates, underscoring the
 economic challenges posed by the pandemic.
