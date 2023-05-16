# Australia Greenhouse Gasses Analysis
This repository contains analysis of Greenhouse Gasses emission of Australia.

## Background
Australia has revised target of reducing emissions by 43 per cent below 2005 levels by 2030. Australia's quarterly emissions have fallen by 21% since 2005. Australia has reduced its emissions at a faster rate than many similar developed countries.<br /><br />
Link: <a href="https://www.aofm.gov.au/sites/default/files/2022-11-28/Aust%20Govt%20CC%20Actions%20Update%20November%202022_1.pdf#:~:text=Australia%20has%20a%20revised%20target,below%202005%20levels%20by%202030.&text=Australia's%20quarterly%20emissions%20have%20fallen,than%20many%20similar%20developed%20countries">Prime Minister of Australia</a>

## Dataset
For this project, I use dataset of Greenhouse Gas Emissions from Organisation for Economic Co-operation and Development (OECD). Link to <a href="https://stats.oecd.org/Index.aspx?DataSetCode=air_ghg">dataset</a>.

## Tools
1. **Microsoft Excel** to load and transfor data.
2. **Microsoft Power BI** to create visualization.
3. **R** to create model dan predict value.

## Analysis
After analyzing data Australia GHG data, below are charts showing total emissions, LULUCF (Land Use, Land-Use Change and Forestry), and pollutants, from 1990 to 2020
<br /><br />
<img src="https://github.com/salmiah-ls/Australia-Greenhouse-Gasses-Analysis/blob/main/images/Australia_emissions.png" width="800"></img><br /><br />
<img src="https://github.com/salmiah-ls/Australia-Greenhouse-Gasses-Analysis/blob/main/images/Australia_lulucf.png" width="800"></img><br /><br />
<img src="https://github.com/salmiah-ls/Australia-Greenhouse-Gasses-Analysis/blob/main/images/Australia_pollutants.png" width="800"></img><br /><br />

## Prediction
Based on analysis above, I will build linear regression model to predict the maximum amount of CO2 the country has to keep each year in order to achive the target emission in 2030.<br />
- First, calculating the target CO2 emission for year 2030. It is 43% below emission in 2005. Hence, the emission value is 57% of 2005 emission (608646.542 thousands tonnes).<br />
> 2030 CO2 emission = 57% * 608646.542 = 346928.5289 thousands tonnes
