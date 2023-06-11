# Data-Cleaning-COVID19

Snowflake COVID19-epidemiological data.

The following tasks were performed:
- Removed U.S. territories
- Removed government agencies
- Removed data for the month of June.  June data in two years had abnormal values 
- Although the figures were cumulative used max() to obtain data values because Hawaii and West Virginia were missing data values
- Created separate columns for two data values in field Cases
