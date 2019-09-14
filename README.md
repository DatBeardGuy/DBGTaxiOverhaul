#DBGTaxiOverhaul
version 1.0 DBG FiveM Taxi Overhaul YMAP

Download DBGTaxiOverhaul

Extract files to DBGTaxiOverhaul

Add to /resources

Add to start cfg

https://www.youtube.com/watch?v=AdajWd091oE

For Door/Gate lock:

Add the following to your doorlock script or download esx_doorlock and add these to the config file:



	-- Taxi Gate

	{
		objName = 'prop_sm1_11_garaged',
		objCoords  = {x = 907.5238, y = -179.7388, z = 73.9924},
		textCoords = {x = 907.5238, y = -179.7388, z = 73.9924},
		authorizedJobs = { 'taxi' },
		locked = false,
		distance = 2,
		size = 1
	},

	-- Taxi Door

	{
		objName = 'apa_heist_apart2_door',
		objCoords  = {x = 897.3915, y = -187.7381, z = 74.0545},
		textCoords = {x = 897.3915, y = -187.7381, z = 74.0545},
		authorizedJobs = { 'taxi' },
		locked = true,
		distance = 2,
		size = 1
	},
