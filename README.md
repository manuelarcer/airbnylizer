# airbnylizer

Airbnb scraper by APIFY
https://apify.com/dtrungtin/airbnb-scraper

## Dataset structure

Here we are dealing with database with few columns (we specified excel-friendly format). I suppose you can get more information and complex dataset by changing that option

This dataset was extracted on **08-June-2023** and the scrape period was **6 months**

|Column|Type|Description|
|------|----|-----------|
|url|str|URL of the listing|
|name|str|Name of the listing|
|stars|float|Star grading of the listing|
|numberOfGuests|int|Max number of occupants|
|address|str|City, State, Country|
|roomType|str|Type of the listing (e.g., Full apartment, house)|
|location|dict|`{lat, lng}`|
|reviews|list||
|pricing|dict|Dictionary containing currency, rate, etc|
|photos|list|URL's with photos of the listing|
|primaryHost|dict|Details of the host|
|additionalHosts|list|More Details about the host|
|isHostedBySuperhost|bool|Is the host SuperHost?|
|isAvailable|bool|Is the listing Available?|
|calendar|list|List with pairs of values `{Available, Date}`|
|occupancyPercentage|float|Percentage of occupancy in the specified period|