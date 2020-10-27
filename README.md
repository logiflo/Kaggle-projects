Kaggle Projects
=======

This repository contains jupyter notebooks for Kaggle tasks and competitions.


# Projects

- [CO2 Emissions](#CO2)
- [Google Play Store](#play-store)
-

<a name="CO2"></a>
# CO2 Emissions

This project analyses the C02 Emissions by country from 1750 to 2017.

**Data Set**

The data sources are not provided, but it is available in [Kaggle](https://www.kaggle.com/yoannboyere/co2-ghg-emissionsdata).

It contains 4 variables: Country, Code, Year and Annual CO2 Emission in tonnes. Each row each row gives us an emission value for a given country at a given year.

**Summary**

After cleaning the data by removing the *Code* column, I have developed a function that graphically displays the CO2 emissions according to the selected country.

The country with the highest total emissions of CO2 from 1750 to 2017 is the United States. Although in 2017 the country with the highest annual emissions is China followed by the United States.

- You can view the notebook online in [Kaggle profile](https://www.kaggle.com/logiflo/co2-emissions).


<a name="play-store"></a>
# Google Play Store

This project is focused on data cleaning of the Google play store dataset extracted in 2018.

**Data Set**

The data sources are not provided, but it is available in [Kaggle](https://www.kaggle.com/lava18/google-play-store-apps)

This data set contains 10841 apps with 13 variables on each app. These variables are: App, Category, Rating, Reviews, Size, Installs, Type, Price, Content Rating, Genres, Last Updated, Current Ver, Android Ver.

**Summary**

This project consists of cleaning the database column by column, in order to have the data ready for later analysis.

Some examples are:
- Convert columns into numeric, removing '+', '$', 'M' or 'k'.
- Fill in the missing values if possible.
- Divide Genres into Main Genres and Sub Genres.
- Convert date in datetime type.

After cleaning data, 4 next columns have been created: Main Genres, Sub Genres, Last Updated in Days, MIN Android Ver.

- You can view the notebook online in [Kaggle profile](https://www.kaggle.com/logiflo/play-store-data-data-cleaning-and-wrangling).






