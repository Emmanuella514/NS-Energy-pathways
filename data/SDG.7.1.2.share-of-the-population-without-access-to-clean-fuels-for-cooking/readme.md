# Number of people with and without access to clean cooking fuels - Data package

This data package contains the data that powers the chart ["Number of people with and without access to clean cooking fuels"](https://ourworldindata.org/grapher/number-with-without-clean-cooking-fuels?v=1&csvType=full&useColumnShortNames=false) on the Our World in Data website.

## CSV Structure

The high level structure of the CSV file is that each row is an observation for an entity (usually a country or region) and a timepoint (usually a year).

The first two columns in the CSV file are "Entity" and "Code". "Entity" is the name of the entity (e.g. "United States"). "Code" is the OWID internal entity code that we use if the entity is a country or region. For most countries, this is the same as the [iso alpha-3](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-3) code of the entity (e.g. "USA") - for non-standard countries like historical countries these are custom codes.

The third column is either "Year" or "Day". If the data is annual, this is "Year" and contains only the year as an integer. If the column is "Day", the column contains a date string in the form "YYYY-MM-DD".

The remaining columns are the data columns, each of which is a time series. If the CSV data is downloaded using the "full data" option, then each column corresponds to one time series below. If the CSV data is downloaded using the "only selected data visible in the chart" option then the data columns are transformed depending on the chart type and thus the association with the time series might not be as straightforward.


## Metadata.json structure

The .metadata.json file contains metadata about the data package. The "charts" key contains information to recreate the chart, like the title, subtitle etc.. The "columns" key contains information about each of the columns in the csv, like the unit, timespan covered, citation for the data etc..

## About the data

Our World in Data is almost never the original producer of the data - almost all of the data we use has been compiled by others. If you want to re-use data, it is your responsibility to ensure that you adhere to the sources' license and to credit them correctly. Please note that a single time series may have more than one source - e.g. when we stich together data from different time periods by different producers or when we calculate per capita metrics using population data from a second source.

### How we process data at Our World In Data
All data and visualizations on Our World in Data rely on data sourced from one or several original data providers. Preparing this original data involves several processing steps. Depending on the data, this can include standardizing country names and world region definitions, converting units, calculating derived indicators such as per capita measures, as well as adding or adapting metadata such as the name or the description given to an indicator.
[Read about our data pipeline](https://docs.owid.io/projects/etl/)

## Detailed information about each time series


## Number of people with access to clean fuels for cooking – World Bank
Access to [clean fuels or technologies](#dod:clean-cooking-fuels) such as natural gas, electricity, and clean cookstoves reduces exposure to indoor air pollutants, a leading cause of death in low-income households.
Last updated: February 27, 2026  
Next update: February 2027  
Date range: 2000–2023  
Unit: people  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
World Health Organization (via World Bank) – with major processing by Our World in Data

#### Full citation
World Health Organization (via World Bank) – with major processing by Our World in Data. “Number of people with access to clean fuels for cooking – World Bank” [dataset]. Tracking SDG 7: The Energy Progress Report, via World Bank, “World Development Indicators 125”; United Nations Population Division, national statistical offices, and Eurostat, via World Bank, “World Development Indicators 125” [original data].
Source: World Health Organization (via World Bank) – with major processing by Our World In Data

### How is this data described by its producer - World Health Organization (via World Bank)?
Access to clean fuels and technologies for cooking is the proportion of total population primarily using clean cooking fuels and technologies for cooking. Under WHO guidelines, kerosene is excluded from clean cooking fuels.

Statistical concept and methodology: Data for access to clean fuels and technologies for cooking are based on the World Health Organization's (WHO) Global Household Energy Database. They are collected among different sources: only data from nationally representative household surveys (including national censuses) were used. Survey sources include Demographic and Health Surveys (DHS) and Living Standards Measurement Surveys (LSMS), Multi-Indicator Cluster Surveys (MICS), the World Health Survey (WHS), other nationally developed and implemented surveys, and various government agencies (for example, ministries of energy and utilities).

Trends in the proportion of the population using each fuel type are estimated using a single multivariate hierarchical model, with urban and rural disaggregation. Estimates for overall "polluting" fuels (unprocessed biomass, charcoal, coal, and kerosene) and "clean" fuels (gaseous fuels, electricity, as well as an aggregation of any other clean fuels like alcohol) are produced by aggregating estimates of relevant fuel types. The model was used to derive clean fuel use estimates for 191 countries (ref. Stoner, O., Shaddick, G., Economou, T., Gumy, S., Lewis, J., Lucio, I., Ruggeri, G. and Adair-Rohani, H. (2020), Global household energy model: a multivariate hierarchical approach to estimating trends in the use of polluting and clean fuels for cooking. J. R. Stat. Soc. C, 69: 815-839). Countries classified by the World Bank as high income (57 countries) in the 2022 fiscal year are assumed to have universal access to clean fuels and technologies for cooking.

### Sources

#### Tracking SDG 7: The Energy Progress Report, via World Bank – World Development Indicators
Retrieved on: 2026-02-27  
Retrieved from: https://data.worldbank.org/indicator/EG.CFT.ACCS.ZS  

#### United Nations Population Division, national statistical offices, and Eurostat, via World Bank – World Development Indicators
Retrieved on: 2026-02-27  
Retrieved from: https://data.worldbank.org/indicator/SP.POP.TOTL  

#### Notes on our processing step for this indicator
We calculated the number of people with access to clean fuels and technologies for cooking by multiplying the fraction of the population with access by the total population.


## Number of people without access to clean fuels for cooking – World Bank
Access to [clean fuels or technologies](#dod:clean-cooking-fuels) such as natural gas, electricity, and clean cookstoves reduces exposure to indoor air pollutants, a leading cause of death in low-income households.
Last updated: February 27, 2026  
Next update: February 2027  
Date range: 2000–2023  
Unit: people  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
World Health Organization (via World Bank) – with major processing by Our World in Data

#### Full citation
World Health Organization (via World Bank) – with major processing by Our World in Data. “Number of people without access to clean fuels for cooking – World Bank” [dataset]. Tracking SDG 7: The Energy Progress Report, via World Bank, “World Development Indicators 125”; United Nations Population Division, national statistical offices, and Eurostat, via World Bank, “World Development Indicators 125” [original data].
Source: World Health Organization (via World Bank) – with major processing by Our World In Data

### How is this data described by its producer - World Health Organization (via World Bank)?
Access to clean fuels and technologies for cooking is the proportion of total population primarily using clean cooking fuels and technologies for cooking. Under WHO guidelines, kerosene is excluded from clean cooking fuels.

Statistical concept and methodology: Data for access to clean fuels and technologies for cooking are based on the World Health Organization's (WHO) Global Household Energy Database. They are collected among different sources: only data from nationally representative household surveys (including national censuses) were used. Survey sources include Demographic and Health Surveys (DHS) and Living Standards Measurement Surveys (LSMS), Multi-Indicator Cluster Surveys (MICS), the World Health Survey (WHS), other nationally developed and implemented surveys, and various government agencies (for example, ministries of energy and utilities).

Trends in the proportion of the population using each fuel type are estimated using a single multivariate hierarchical model, with urban and rural disaggregation. Estimates for overall "polluting" fuels (unprocessed biomass, charcoal, coal, and kerosene) and "clean" fuels (gaseous fuels, electricity, as well as an aggregation of any other clean fuels like alcohol) are produced by aggregating estimates of relevant fuel types. The model was used to derive clean fuel use estimates for 191 countries (ref. Stoner, O., Shaddick, G., Economou, T., Gumy, S., Lewis, J., Lucio, I., Ruggeri, G. and Adair-Rohani, H. (2020), Global household energy model: a multivariate hierarchical approach to estimating trends in the use of polluting and clean fuels for cooking. J. R. Stat. Soc. C, 69: 815-839). Countries classified by the World Bank as high income (57 countries) in the 2022 fiscal year are assumed to have universal access to clean fuels and technologies for cooking.

### Sources

#### Tracking SDG 7: The Energy Progress Report, via World Bank – World Development Indicators
Retrieved on: 2026-02-27  
Retrieved from: https://data.worldbank.org/indicator/EG.CFT.ACCS.ZS  

#### United Nations Population Division, national statistical offices, and Eurostat, via World Bank – World Development Indicators
Retrieved on: 2026-02-27  
Retrieved from: https://data.worldbank.org/indicator/SP.POP.TOTL  

#### Notes on our processing step for this indicator
We calculated the number of people without access to clean fuels and technologies for cooking by multiplying the fraction of the population without access by the total population.


    