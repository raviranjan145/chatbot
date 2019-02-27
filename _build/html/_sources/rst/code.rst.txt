====
code
====



Function
========
for finding the wo id
.. code-block:: python 

   def get_woeid(city_name):
	r = requests.get('https://www.metaweather.com/api/location/search/?query        ='+ str(city_name))
	woeid = r.json()[0]['woeid']

	return(get_weather_stats(woeid))




.. toctree::
   :maxdepth: 2
   :caption: User Documentation:
   
   fun2









