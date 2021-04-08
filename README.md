# Swedish Cities

Had to gather this information for a project at work.
List of cities/places is from an internal list.

I ran it against Wikipedia and Geohack to get population and coordinates.

Each city has the following:
* checked - Just a marker for the code to know if it has already been checked
* pop - Population from Wikipedia, values of 1 or -1 are placeholders if nothing else was found.
* lat - Latitude from Geohack
* lon - Longitude from Geohack
* time - Travel time by car in minutes to the biggest cities within the same county. Calculated with Google Maps API
  * If time for a city is False, Google Maps didn't find a route between them
