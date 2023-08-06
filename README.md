# Data-Cleaning-COVID19

Snowflake COVID19-epidemiological data.

The following tasks were performed:
- Removed U.S. territories
- Removed government agencies
- Removed data for the month of June.  June data in two years had abnormal values 
- Although the figures were cumulative used max() to obtain data values because Hawaii and West Virginia were missing data values
- Created separate columns for two data values in field Cases

SQL
- [Data Cleaning  & Aggregation SQL](https://github.com/Sarah269/Data-Cleaning-COVID19/blob/main/Snowflake%20COVID19%20060423.txt)

Dashboard
- [US COVID-19 Dashboard](https://public.tableau.com/views/Sample_16857372916990/Dashboard1?:language=en-US&:display_count=n&:origin=viz_share_link)

