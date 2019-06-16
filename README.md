# Wine-Data-Ratings

This is a #TidyTuesday challenge setup in May and for the love of wine and experimental spirit I just had to analyse this!

The data is from a wine-enthusiast ratings dataset from Kaggle. A clear relationship from an article based on a different dataset suggested that cost is factored into their rating system. 

# Objective

1. Determine if cost affects the rating system.
2. How does the scale compare with the findings from the article


# Data Dictionary
The data can be found here : https://raw.githubusercontent.com/rfordatascience/tidytuesday/master/data/2019/2019-05-28/winemag-data-130k-v2.csv

| variable	| class |	description |
| :---: | :---: | :---:| 
|country	|character	|Country of origin|
|description|	character	|Flavors and taste profile as written by reviewer|
|designation	|character	|The vineyard within the winery where the grapes that made the wine are from|
|points	|double	|The number of points WineEnthusiast rated the wine on a scale of 1-100 (though they say they only post reviews for wines that score >=80)|
|price|	double	|The cost for a bottle of the wine|
|province	|character	|The province or state that the wine is from|
|region_1|	character	|The wine growing area in a province or state (ie Napa)|
|taster_name	|character	|The taster/reviewer|
|title	|character	|The title of the wine review, which often contains the vintage (year)|
|variety	|character	|Grape type|
|winery	|character	|The winery that made the wine|
