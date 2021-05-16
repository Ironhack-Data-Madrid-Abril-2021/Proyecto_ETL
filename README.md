![alt text](https://static01.nyt.com/images/2020/07/28/us/28xp-UFO/28xp-UFO-facebookJumbo.jpg)



Proyecto de ETL UFOs en USA - Vicente Díaz Pliego



The project consisted in extracting information from different sources (Databases, WebScrapping, APIs...), cleaning the data to later, gather all the records of UFO sightings and make a study to see the relationship that these records had with the area 51, and also with the largest nuclear power plant in the USA, Palo Verde Nuclear Generating Station.

After the data cleaning, I eliminated all the scattered records, to make a study focused on USA and the cities where more sightings occur:
seattle 524
phoenix 454
portland 373
las vegas 367
los angeles 352

These are the cities with the highest number of records.

From this point, I performed a webcrapping of the DD coordinates of Area 51, and the coordinates of the Palo Verde Nuclear Generating Station.

I downloaded a Python library called Harvesine, which calculates the distance between two points through their coordinates, to check if there was any relationship between the sightings and the proximity to these two places.





