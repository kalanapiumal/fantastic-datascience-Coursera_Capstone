# fantastic-datascience
This is fantastic Data Science repository to learn and apply for real world problems.
Introduction:
A.1:Business Problem:
	Finding best new location for coffee shop in Mumbai city.
A.2:Description & Discussion of the Background:
The city of Mumbai consists of a large number of coffee shop, restaurants, but still there is always scope for new ones. The total area of Mumbai is 603.4 km2 (233 sq mi).Of this, the island city spans 67.79 km2 (26 sq mi).and Mumbai was the second most populous city in India after Delhi and the seventh most populous city in the world with a population of 19.98 million. As per Indian government population census of 2011. The most recent census was conducted in India during 2018, which put Mumbai's Urban Agglomeration at 20,748,395, while the city itself was recorded at 12,478,447.
The rapid population growth is attributed to migration from other regions in the country, with migrants seeking business and employment opportunities. On an average 25000 person come to Mumbai daily for work.
The Goal of this problem is to find a location that suits the below criteria:
 1) A location that has many restaurants in the vicinity like (Indian, South Indian).
 2) A location that has no or few café coffee, as this will ensure that there very little competition with other competitors.
A.3. Data Description:
The data that will be used in these projects is a csv file having data related to all neighborhoods in the city of Mumbai. File data collected from https://en.wikipedia.org/wiki/List_of_neighbourhoods_in_Mumbai using this URL.
 

Data that will be used to solve problem of finding best location using neighborhoods and location.
We explore the neighborhoods using Foursquare API to find the avenues within 500 meters of each neighborhood. 
The Foursquare API that will be used to explore the neighborhoods is https://api.foursquare.com/v2/venues/explore.  This API returns json response which will be transformed into a Data Frame, taking only the required details into consideration. 
A.4: Target Audience
 To recommend the correct location, XYZ Company Ltd has appointed me to lead of the Data Science team. The objective is to locate and recommend to the management which neighborhood of Mumbai city will be best choice to start a Coffee Shop. The Management also expects to understand the rationale of the recommendations made. This would interest anyone who wants to start a new café in Mumbai city. 
A.5:  Success Criteria:
The success criteria of the project will be a good recommendation of borough/Neighborhood choice to XYZ Company Ltd based on Lack of such café in that location and nearest sources of customer.

Reference: wikipidia page:https://en.wikipedia.org/wiki/List_of_neighbourhoods_in_Mumbai 
