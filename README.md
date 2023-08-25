# Data Analysis -COVID19

Snowflake COVID19-epidemiological data.

The following tasks were performed:
- Removed U.S. territories
- Removed government agencies
- Removed data for the month of June.  June data in two years had abnormal values 
- Although the figures were cumulative used max() to obtain data values because Hawaii and West Virginia were missing data values
- Created separate columns for two data values in field Cases

Observations:
- Tennesee is the only state to place in the top 5 for number of cases and deaths as a percentage of population.
- Deaths as a percentage of population clustered between 0.20% and 0.40%.
- Florida and Arizona have a lot of hospitals and ICU beds yet deaths as a percentage of the population is high.
- Rhode Island is the only state in the top 5 cases with a vaccination rate of 83%.  The rest of the states in the top 5 cases and deaths are below 60%.
- Rhode Island seems to have fewer hospitals and ICU beds than other states with a similiar population.
- A hospital does not equal ICU beds.  There are hospitals that don't have ICU beds.  Additionally, there are counties in states that don't have hospitals.

SQL
- [Data Cleaning  & Aggregation SQL](https://github.com/Sarah269/Data-Cleaning-COVID19/blob/main/Snowflake%20COVID19%20060423.txt)

Dashboard
- [US COVID-19 Dashboard](https://public.tableau.com/views/Sample_16857372916990/Dashboard1?:language=en-US&:display_count=n&:origin=viz_share_link)

