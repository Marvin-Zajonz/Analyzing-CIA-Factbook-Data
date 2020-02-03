# Analyzing CIA Factbook Data

The CIA World Factbook is a resource produces by the US Central Intelligence Agency providing information about over 250 countries of the world. The CIA World Factbook's websites contains information about maps, flags, country profiles, and demographic data. The data set we will be working with in this project can be found [here](https://github.com/factbook/factbook.sql/releases). The data set includes the following columns:
1. **id**: id for the country
2. **code**: abbreviated code (two characters) of the country (unique)
3. **name**: name of the country
4. **area**: area (geograhical size) of the country in km2; cumulative of **area_land** and **area_water**
5. **area_land**: land area (geograhical size) of the country in km2
6. **water_area**: water area (geograhical size) of the country in km2
7. **population**: the country's population
8. **population_growth**: the percentage of population growth in one year
9. **birth_rate**: the country's total number of births per 1,000 population in one year
10. **death_rate**: the total number of deaths per 1,000 population of the country in one year
11. **migration_rate**: ratio between the number of immigrants and the number of emigrants
12. **created_at**: date of the rows creations
13. **updated_at**: date of the rows last update
<br><br>
The data set's type is SQLite and contains each country's information as of 2015.

### Goals of this project

The goal of this project is to find interesting demographic facts about the world, for example the country with the lowest population density or the country with the highest ration of water area to land area. In addition, we want to visualize the data to get a better understanding of the disribution of different variables.
