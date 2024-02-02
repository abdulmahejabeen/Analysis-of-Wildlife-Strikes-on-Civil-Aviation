# Analysis-of-Wildlife-Strikes-on-Civil-Aviation
Wildlife strikes are the consequence of various factors. These factors include migration of species, weather, time-of-day, phase of flight and the region of the flight’s route. However, some of the questions remain to be addressed with solid observational data.
## Description
This project focuses on the aforementioned factors and try to ascertain levels of contribution for each factor. This project aim is to provide indepth analysis of dataset includes visualization through various types of graphs which have been used to demonstrate a concise overview of the bird strike problem in commercial aviation and also the factors contributing to the occurrence and the potential consequences in terms of effect on the flight and damage. 
## Datasets
There are two datasets used in this analysis. Wildlife strikes data is downloaded from FAA Wildlife Strike Database. It Contains data from 1990 to 2021, consisting of 260,000 records, and 100 fields covering all states in US. 

The other dataset used is Aviation accidents dataset, has been collected from NTSB aviation accident database contains information from 1990 and later about civil aviation accidents and incidents within the United States, its territories and possessions, and in international waters. It consists of about 88000 records covering 49 different states of the US from the years 1990 to 2021. 

The two datasets Aviation and Wildlife Strikes data using Outer join on column-registration number of the accident. Along with the two datasets, also joined the US state code mapping table using the left join on state column which helps in mapping state codes with the state names.
