# Aotidae

The Aotidae project seeks to ingest space data that is stored on AWS and analyse it for value. The data can be found [here](https://registry.opendata.aws/?search=tags:gis,earth%20observation,events,mapping,meteorological,environmental,transportation).

The initial analysis is using the Sentinel-2 satelite images to identify the prevalence of cloud cover. This analysis seeks to input a location and a time period and output the usability of the images.

The Sentinel-2 guide can be found [here](https://sentinelhub-py.readthedocs.io/en/latest/examples/process_request.html#Example-1:-True-color-(PNG)-on-a-specific-date).

Feel free to run the notebook (note that you will need to create the SentinelHub config file) to see getting the images, and to start to look at how the analysis process can be run.
