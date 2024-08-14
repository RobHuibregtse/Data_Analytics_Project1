# Data_Analytics_Project1

Project Title: COVID-19 and Real Estate: A Zillow Data Analysis

Members: 
Laura Magallanes 
Rob Huibregtse 
Jane Hedges 
James Pelletier 

Project Description: Anecdotally, the COVID-19 pandemic and the resulting increase in work-from-home employment is said to have created a shift in the housing market by taking some air out of the market in large cities and increasing housing demand in smaller cities across the country. By analyzing data provided by Zillow regarding average home prices, for-sale listings, new construction, and rent from pre-pandemic and post-pandemic years, we aim to visualize and draw some conclusions about the magnitude of this change in the housing market. 

Scope & Data Collection: The project analysis will be sourced from Zillow’s real estate databases (https://www.zillow.com/research/data/) and Macrotrends (https://www.macrotrends.net/2015/fed-funds-rate-historical-chart) conducted on a nationwide scale during the time period of 2018-2023, highlighting pre-pandemic, pandemic, and post-pandemic periods. The key metrics we aim to focus on are: Inventory Levels, Market Heat Index, Rent Index, and Home Value Index. 

Hypotheses: 
- Hypothesis 1: Larger Cities experienced an increase in inventory compared to smaller cities due to individuals moving from larger cities to more remote locations during the pandemic period (2020-2021). 
- Ho: Larger cities do not experience a significant increase in inventory compared to smaller cities during the pandemic period (2020-2021).
- Ha: Larger cities experienced a significant increase in inventory compared to smaller cities during the pandemic period (2020-2021).
- Hypothesis 2: Larger cities experienced a decrease in rent value index compared to smaller cities during the pandemic period (2020-2021)
- Ho: Larger cities did not experience a significant decrease in rent value index
- Ha: Larger cities did experience a significant decrease in rent value index
- Hypothesis 3:  Larger Cities experienced a decrease in home value index compared to smaller cities due to individuals moving from larger cities to more remote locations during the pandemic period (2020-2021). 
- Ho: Larger cities do not experience a significant decrease in home value index.
- Ha: Larger cities do experience a significant decrease in home value. 
- Hypothesis 4: Larger cities experienced a decrease in market heat index compared to smaller cities during the pandemic period (2020-2021)
- Ho: Larger cities did not experience a significant decrease in market heat index
- Ha: Larger cities did experience a significant decrease in market heat index

Research Questions:
- Question 1: How did market heat index and interest rates correlate from 2018 - 2023?
- Question 2: How did housing inventory change from 2018-2023?
- Question 3: How did rent index change in large and small cities between 2018 and 2023?
- Question 4: When compared to the rent index in smaller cities between 2020 and 2021, is the decline in the rent index in large cities statistically significant? 
- Question 5: Is there a statistically significant difference in the measures of central tendency between large and small cities in 2021 compared to 2019?
- Question 6: How do inventory index levels compare across different city size segments?
- Question 7: Has there been a notable dip in the Home Value Index for in large cities between 2018 - 2023?
- Question 8: Have home prices increased at a faster rate in smaller cities compared to large cities?

Repository Structure:
Accessing our Data Files used in our Analysis: 
- Hypotheses 1 Inventory Levels (Main Branch): Data_Analytics_Project1/Code/Zillow_Data/Metro_invt_fs_uc_sfrcondo_sm_month.csv
- Hypotheses 2 Rent Index (Main Branch): Data_Analytics_Project1/Code/Zillow_Data/Metro_zori_uc_sfrcondomfr_sm_month.csv
- Hypotheses 3 Home Value Index (Main Branch): Data_Analytics_Project1/Code/Zillow_Data/Metro_zhvi_uc_sfrcondo_tier_0.0_0.33_sm_sa_month.csv
- Hypotheses 4 Market Heat Index (Main Branch): Data_Analytics_Project1/Code/Zillow_Data/Metro_market_temp_index_uc_sfrcondo_month.csv

Accessing our Code Analysis: 
- Hypotheses 1 Inventory Levels (Main Branch): Data_Analytics_Project1/Code/Hypothesis1CodeLauraFinal.ipynb
- Hypotheses 2 Rent Index (Main Branch): Data_Analytics_Project1/Code/Hypothesis2Code.ipynb
- Hypotheses 3 Home Value Index (Main Branch): Data_Analytics_Project1/Code/Hypothesis3CodeJamesP.ipynb
- Hypotheses 4 Market Heat Index (Main Branch): Data_Analytics_Project1/Code/Hypothesis4AnalysisMarketHeatIndex

Accessing Our Written Analysis & Presentation Slides:
- Detailed Written Analysis(Main Branch): Data_Analytics_Project1/Data Analytics Project 1 Written Analysis.pdf
- Presentation Slides (Main Branch): Data_Analytics_Project1/Data Analytics Project 1.pptx

How to Run the Project:
- Step 1: Clone the repository to your local machine.
- Step 2: Ensure Python and Jupyter Notebook are installed on your local machine. 
- Step 3: Ensure you have all the dependencies installed: pandas, pathlib, spicy.stats, matplotlib.pyplot, numpy, seaborn.

Key Findings
We were not able to reject the null hypothesis for any of our metrics signifying we could not find a significant change in these four metrics between large metro areas and smaller metro areas during the pandemic. We did observe significant changes in the housing market:
- Nationwide housing inventory dropped significantly.
- Home values and rent (which are strongly correlated) continued to go up.
- The Federal Reserve’s use of interest rates to respond to the pandemic appeared effective in the housing market; the once positive correlation between interest rates and demand was reversed, and the two are now negatively correlated again (as basic economics would predict).
  
Conclusion: 
- Large cities had considerable declines in the rent index during the pandemic, but a p-value of more than 0.05 indicates that the data is not statistically significant. 
- Large cities and smaller cities both experienced a significant decrease in inventory levels during the pandemic years (2019-2020).
- Home prices have risen across the board showing no favoritism for smaller or larger cities.
- Strongest Correlation: Home Value Index and Rent Index
- Weakest Correlation: Housing Inventory and Federal Funds Rate

References:
- Zillow Housing Data: https://www.zillow.com/research/data/
- Federal Funds Rate Data: https://www.macrotrends.net/2015/fed-funds-rate-historical-chart



