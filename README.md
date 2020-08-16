# Coursera Capstone Project - Distribution of hospitals in Toronto
This repository is a project of IBM Data Science Professional Certificate by Coursera 

# Aim of this project
To find out the nummber of hospitals in different neighbourhoods of Toronto, so that people will buy houses near it.
The analysis will also help the government to decide which new place hospitals need to be built.

# Data Description 
The data that will be used for this project will be acquired from the following sources:
The Foursquare information data contains detailed breakdowns of hospitals for different neighbourhoods and was the primary data source for this analysis. Specifically, A list of Toronto neighbourhoods retrieved from Wikipedia was also used. 

# Methodology
Scrape the html data from Wikipedia using Beautiful Soup library. A list of Hospitals in Toronto, one was pulled using the Foursquare location data and the other from Wikipedia.
Explore the venues of each neighborhood using Foursquare API.That list was then cross-referenced with the Wikipedia neighbourhood data to determine what neighbourhood each location was part of by matching the first three digits of the Postal Codes.That list was then compared to the total list of neighbourhoods to determine finally what neighbourhoods are hospitals. Finally, the list of neighbourhoods with institutions was mapped to visually demonstrate whether Toronto higher education institutions are, in fact, equally distributed.

Find the detailed methodology inside the Capstone Project Python Notebook.

# Conclusion
Analysis shows that while there are more number of hospital inside of the downtown core, there is a cluster in the centre of the city. The majority of Toronto’s neighbourhoods lack Hospitals options. And while the map makes it clear the Toronto’s surrounding area is well represented west of the 401, the areas between the city and the suburbs is almost entirely without options



