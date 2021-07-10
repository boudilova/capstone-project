# capstone-project
week of coursera capstone project part 1

Introduction/Business Problem

My choice of problem is to find out best places to open a restaurant in Toronto.

Good locations for restaurant is a key to success. 
What is the good location for restaurant? 
Some place with no restaurant or less restaurants then in other places but people go by very often.

Data

Using data from Foursquare and data about postal codes of Toronto, i going to find out list of best places to open restaurant.
To find locations I'm going to use set of postal codes of Toronto to split city for regions.

Then using Foursquare data, which contains information about different venues in Toronto, I get data about restaurant's locations .
Then analyze venues categories assign every venue category to venue groups as «restaurant», «food», "entertainment»  and so on.

List of Toronto's postal codes is taken from wikipedia, converted into table view (there were different types of table view, and they changed it every day so I downloaded it) 

To find regions with less restaurants we are going to Intersect foursquare data with postal codes of Toronto. This operation will give us information about how many venues of every group are located in every postal code region.
With this information i'm going to find regions where less restaurants among other regions.

Methodology

The  main question of this problem is "what places are best" so places may be good and may be not good for restaurant. So i need to split data into several groups using some kind of characteristics. 

