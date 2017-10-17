# Add react landing page that displays the lat/lon data from the backend

### Description
We should start to build out an interface for our Go backend that can users can interact with.  The frontend should be React.

### Specifications

This project has no frontend, so the goal here should be a simple hello world that allows the two to talk, before we build out more complicated features.

- Use react version 16 (v16.0)

- Make a request to the index route (which returns station information for a NOAA sensor)

- Display the station ID and name in the center of the page.

These values can be found in the metadata object of the response:

{"metadata":{"id":"8454000","name":"Providence","lat":"41.8067","lon":"-71.4006"}, "data": [{"t":"2013-01-01 10:00", "v":"0.072", "s":"0.003", "f":"0,0,0,0", "q":"v"},{"t":"2013-01-01 10:06", "v":"0.095", "s":"0.003", "f":"0,0,0,0", "q":"v"},{"t":"2013-01-01 10:12", "v":"0.115", "s":"0.003", "f":"0,0,0,0", "q":"v"},{"t":"2013-01-01 10:18", "v":"0.138", "s":"0.004", "f":"0,0,0,0", "q":"v"},{"t":"2013-01-01 10:24", "v":"0.167", "s":"0.004", "f":"0,0,0,0", "q":"v"}]}
