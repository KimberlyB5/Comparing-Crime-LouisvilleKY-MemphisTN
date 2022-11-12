# **Comparing 2022 Crime Louisville, Kentucky and Memphis, Tennessee**

I chose Louisville and Memphis because Louisville rates as number 29 on the top 50 largest cities as of the 2020 Census, Memphis is 28 with 59 more people than Louisville.  Memphis is the closest city size to Louisville. I used [THIS](https://www.infoplease.com/us/cities/top-50-cities-us-population-and-rank) website for my census data.

Memphis tax rate is approximately 30% lower than Louisville.  Tax rate data came from [HERE](https://smartasset.com/mortgage/cost-of-living-calculator#oXS5xYWqX6). Tennessee like Kentucky is primarily a red state with the both Louisville and Memphis having Democrat Mayors.  

Memphis Crime data came totaled in 2 categories per month, Louisville Crime data was detailed and had to be sorted into the 2 categories.  I visited the FBI website at [FBI PROPERTY CRIME](https://ucr.fbi.gov/crime-in-the-u.s/2018/crime-in-the-u.s.-2018/topic-pages/property-crime) and quote the guidance used for sorting data.


    "In the FBI’s Uniform Crime Reporting (UCR) Program, property crime includes the offenses of burglary, larceny-theft, motor vehicle theft, and arson. The object of the theft-type offenses is the taking of money or property, but there is no force or threat of force against the victims. The property crime category includes arson because the offense involves the destruction of property; however, arson victims may be subjected to force."

 I visited the FBI website at [FBI VIOLENT CRIME](https://ucr.fbi.gov/crime-in-the-u.s/2010/crime-in-the-u.s.-2010/violent-crime#:~:text=Definition,%2C%20robbery%2C%20and%20aggravated%20assault.) and quote the guidance used for sorting data.


    "In the FBI’s Uniform Crime Reporting (UCR) Program, violent crime is composed of four offenses: murder and nonnegligent manslaughter, forcible rape, robbery, and aggravated assault. Violent crimes are defined in the UCR Program as those offenses which involve force or threat of force."

Using this as a guide I sorted Louisville's detailed data into 3 Categories Major Property Crime, Major Violent Crime and Other.  The other did not fit into either category i.e. drug/alcohol charges, disturbing the peace, etc.

My data consists of the following data fields:

|Field Name | Description                               |
|-----------|-------------------------------------------|
|  MONTH    | Monthly totals                            |
| CATEGORY  | Property, Violent, or other crime         |
|  COUNT    | Total Monthly counts of each crime type   |
| LOCATION  | Where the totals go Louisville or Memphis |


**TO RUN THIS PROJECT:**

I used VSCode with a Jupyter extension and imported
        ```from pathlib import Path```, 
        ```import pandas as pd```, 
        ```import os```

After cleaning and sorting the data I exported them to seperate CSV files to move to Tableau Public to create additional graphs and merge the data.
Please visit for the Tableau work [HERE](https://public.tableau.com/views/LouisvilleMemphis2022CrimeData/Memphis?:language=en-US&:display_count=n&:origin=viz_share_link)

Interesting observations from exploring this data:

1. Memphis has more Major Property Crime than Louisville.
2. Louisville has more Major Violent Crime than Memphis.
3. Crime trends tend to be higher in warmer months.

Ideas to expand this project:
1. Expand the data to compare 2018 - 2022
2. The comparison of the 2 years prior to the pandemic shutdown (2018, 2019) to the 2 years after the pandemic shutdown (2021, 2022).
3. Exploring what happened during 2020 would be interesting compared to the 2 years before and after.