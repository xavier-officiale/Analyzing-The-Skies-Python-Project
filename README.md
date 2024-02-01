# Analyzing The Skies - Study of Departures & Delays in 2022

This GitHub repository houses a data analysis project focused on unraveling the on-time performance of domestic flights in the United States for the year 2022. The data, sourced from [TranStats - Bureau of Transportation Statistics (BTS)](https://www.transtats.bts.gov/Tables.asp?QO_VQ=EFD&QO_anzr=Nv4yv0r%FDb0-gvzr%FDcr4s14zn0pr%FDQn6n&QO_fu146_anzr=b0-gvzr), offers a comprehensive glimpse into the behavior of commercial flight carriers, the capacity of major airports, and the critical aspect of timeliness in air travel.

## Objective

The primary goal of this project is to delve into the intricate details of air travel operations and explore key factors influencing on-time performance. By leveraging exploratory data analysis techniques and visualization tools, the project aims to uncover patterns, correlations, and insights that can enhance our understanding of the dynamics within the aviation industry.

## Data

### Source:
The data originates from TranStats, a division of the United States Department of Transportation (DOT). This official government source is considered reliable, as it collects on-time data for flights reported by US carriers. The dataset is particularly intriguing for its potential to reveal trends in the behavior of carriers, the capacity of major airports, and the ability of airlines to meet travelers' expectations regarding timeliness.

Geospatial analysis was conducted in Python using this [us-states.json](https://coach-courses-us.s3.amazonaws.com/public/courses/data-immersion/A6/6.3/us-states.json) file.

### Collection Method:
Administrative data related to airline flight operations is collected automatically through an Airline Operations and Delay System (AODB). The delay information, including reasons for delays, is manually recorded by airline staff, air traffic controllers, or airport personnel. The AODB captures and publishes this data monthly, providing a near-real-time snapshot of the previous month's flight operations.

### Content: 
The dataset encompasses scheduled and actual departure and arrival times reported by certified U.S. air carriers that represent at least one percent of domestic scheduled passenger revenues. While the entire dataset covers flights for all domestic airports, this analysis specifically focuses on the year 2022, narrowing down to flights departing from the top 5 busiest airports in the country, as identified by [Afar](https://www.afar.com/magazine/busiest-airports-in-the-us).

To facilitate year-long analysis, monthly data was downloaded, and a reduced dataset was created in Python, isolating flights departing from the top 5 busiest airports for each month. The final step involved concatenating the twelve datasets into one comprehensive dataset for thorough analysis.

Because of Github's 25MB limit for upload, the final dataset in this repository is only a 50% version of the one used in the analysis.

## Tools
Python libraries used in this project include:
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Folium
- Scikit-learn

Scripts were created in Jupyter.

The final presentation was created in Tableau and can be viewed [here](https://public.tableau.com/app/profile/xavier.herrera1185/viz/Task6_7-AnalyzingTheSkies/ANALYZINGTHESKIES).
