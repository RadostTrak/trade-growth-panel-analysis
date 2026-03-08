# Trade Liberalisation and Economic Growth (1988-2023)
This is an analysis of trade liberalisation's impact on economic growth in the long run. This project is done for a level 3 course 'Economic History, Origins and Crises of Global Capitalism'. It uses Sachs & Warner’s (1995) landmark paper as a basis, replicating and extending their econometric model to examine the relationship between tariff rates and growth across 107 countries in the period 1988-2023. The results show that lagged tariff rates are not a significant predictor of GDP per capita growth (p = 0.203). View the paper in progress [here](Radost%20Trakiyska%20Trade%20Liberalisation%20and%20Growth.pdf).

Status: in progress. 
Planned work: run robustness checks, finish writing results and discussion of paper.

## Notebooks
1. `01_data_cleaning.ipynb` - Loads and cleans four datasets, constructs import-weighted tariff variable, handles missing data, and merges into a single panel dataset.
2. `02_data_exploration.ipynb` - Exploratory visualisations of tariff rates, trade, and GDP per capita trends.
3. `03_regression_analysis.ipynb` - OLS regression replicating the Sachs & Warner specification with tariff rates replacing the openness dummy.

## Data
Tariffs: World Bank's Integrated Trade Solution, UNCTAD TRAINS. Analysis uses weighted average tariffs, defined as import-value-weighted ad valorem averages by year.  
Trade: World Bank, measures exports and imports of goods and services as percent of GDP.  
Penn World Table version 11.0: provides macroeconomic variables such as real GDP and population.  
Income Groups: World Bank's income classification, defines annual income classifications based on countries' gross national income per capita. 