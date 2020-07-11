

![IronHack Logo](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_d5c5793015fec3be28a63c4fa3dd4d55.png)


# Berlin Crime 2012-2019


**Data Analytics, June 2020, Berlin**

**Milena Vasić and Şelale Urun**


## Content
* [Project Description](#project-description)
* [Dataset](#dataset)
* [File Structure](#dataset)


## Project Description

Our project focuses on the exploration of crime in Berlin. Our main questions were:
1) What crime types are the most common in Berlin?
2) Can crime be correlated to the areas of districts, population size or number of tourists?
3) What are the differences between districts?
4) What are the 'dangerous' neighbourhoods in Berlin?
5) Does and in what ways crime rate change through time?

 ## Dataset
 
The data was obtained from Berlin open data: https://daten.berlin.de/, and includes information on the demography and official crime records. 
The official crime information was obtained from the following website: https://www.kriminalitaetsatlas.berlin.de/K-Atlas/atlas.html, and the population and tourist information was downloaded from Amt für Statistik Berlin-Brandenburg: https://www.statistik-berlin-brandenburg.de/

## File Structure

The repository contains the following files:

BerlinCrime.csv and BerlinCrime_rearranged.xlsx include the actual number of crime according to the type, year, district, neighbourhood and neighbourhood_id. They contain the same information, but the rows and columns are arranged differently.

BerlinCrime_frequency.xlsx and BerlinCrime_frequency_rearranged.xlsx contains the same information as the above two files, but instead of actual number of crime, they have frequency of crime rate. That is, number of crimes per 100 000 people. 

BerlinPopulationFinal.xlsx represents the demography dataset. It includes information about citizenship, age, sex and Berlin district for each year. 

TouristsNumbers.xlsx contains information about number of tourists and number of overnights in each district per year. 

Our work is stored in two Jupyter notebooks: 
[Crime and its Spatial Distribution](https://github.com/MilVas/Project6/blob/master/CrimeAndItsSpatialDitribution.ipynb) and 
[Temporal Distribution of Crime](https://github.com/MilVas/Project6/blob/master/CrimeAndItsSpatialDitribution.ipynb)
We also added our presentation file in the repository. 

