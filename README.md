# LACrimes

All visualizations are available on Tableau Public at: https://public.tableau.com/views/LACrimesfrom2010-2024/CrimeOverview?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link

The dashboard "LA Crimes from 2010-2024" aims to provide you with:
* A general overview of crime occurrences, arrest statuses, and trends over time in the city of Los Angeles, California
* An account on the different times of day (e.g. morning, afternoon, night, etc.) in which crime occurs
* A breakdown of criminal offences based on their geographical locations, crime scene premises, weapons used, and demographic information of the victims affected

Instructions to those who want to reproduce the end-to-end process of making the visualization:
1. Download the original csv file for the source data from: https://catalog.data.gov/dataset/crime-data-from-2020-to-present.
2. Run the "la_crimes.ipynb" notebook in its entirety to produce a clean csv of the original data and a csv mapping the "Vict Descent" codes to their respective ethnicities. The two csv files will be named "cleaned_crime_data.csv" and "ethnicity.csv" respectively.
3. Open up the "LACrimes.twb" workbook and connect it to the two newly-created csv files in step 2.
4. Enjoy!

To understand the meaning of each column of data in the original dataset, visit: https://data.lacity.org/Public-Safety/Crime-Data-from-2020-to-Present/2nrs-mtv8/about_data
