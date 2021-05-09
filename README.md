# Segmenting and Clustering Neighborhoods in Istanbul
## Introduction
Istanbul is the largest city in Turkey and the country's economic, cultural and historic center. As a resident of this city, I decided to create my project about Istanbul. The city straddles the Bosphorus strait, and lies in both Europe and Asia, with a population of over 15 million residents, comprising 19% of the population of Turkey. Istanbul is also the most populous city in Europe and the world's fifteenth-largest city.
As we mentioned in the first paragraph, millions of people live in Istanbul and moreover, many people are planning to live in Istanbul. Thus, the goal I want to reach with this project is to give a simple recommendation to people: Which neighborhood of Istanbul is suits you best? The target audience is both people planning to move to Istanbul and people who are not happy where they live in Istanbul.

## Data sources
To solve this problem, we need the following variables:
- Neighborhood,
- Boroughs,
- Population,
- Area(in $km^{2}$),
- Density: Population density per $km^{2}$,
- Latitude,
- Longitude.

  Firstly, for the Istanbul neighborhood data, I will scrape the page "https://www.atlasbig.com/tr/istanbul-mahalleleri-nufus-yogunlugu" that includes the neighborhood names, population, area and population density. Then, I will wrangle the data and clean it. I will use the geopy library to obtain the coordinate information of the neighborhoods. Finally, I will use Foursquare API to obtain the most common venues in given neighborhood of Istanbul.
