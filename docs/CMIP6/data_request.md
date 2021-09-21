---
title : CMIP6 Data Request
rank: 2.1
---

# CMIP6 Data Request

The CMIP6 data request defines all the quantities from CMIP6 simulations that should be archived. 
This includes both quantities of general interest needed from most of the CMIP6-endorsed model intercomparison projects (MIPs) and quantities that are more specialized and only of interest to a single endorsed MIP. 
The complexity of the data request has increased from the early days of model intercomparisons, as has the data volume. 
In contrast with CMIP5, CMIP6 requires distinct sets of highly tailored variables to be saved from each of the more than 300 experiments. 
This places new demands on the data request information base and leads to a new requirement for development of software that facilitates automated interrogation of the request and retrieval of its technical specifications. 

* [GMD paper](https://gmd.copernicus.org/articles/13/201/2020/)
* [Data Request web interface front page](http://clipc-services.ceda.ac.uk/dreq/index.html)
  * [Search for variables](http://clipc-services.ceda.ac.uk/dreq/mipVars.html) : Search for a variable and you will be presented with links to a `MIP Variable` page, e.g. for `tas`, which will then provide links on to specific instances of this variable in various MIP tables.
  * [Search for experiments](http://clipc-services.ceda.ac.uk/dreq/experiments.html)
* [Data Request source repository](http://proj.badc.rl.ac.uk/exarch/browser/CMIP6dreq)
* [Input information for CMIP6](http://proj.badc.rl.ac.uk/exarch/browser/CMIP6dreqbuild/trunk/inputs)
* Pressure level set information can be found in table 4 of the [GMD Paper](https://gmd.copernicus.org/articles/13/201/2020/#section4) or within the `CMIP6_coordinate.json` file within the [CMIP6 MIP tables](https://github.com/PCMDI/cmip6-cmor-tables/blob/master/Tables/CMIP6_coordinate.json)

## MIP Specific documents

### OMIP

* [CMIP6_OMIP_physics_standard_output](https://docs.google.com/spreadsheets/d/1M7KeHm1ZaSKClgf5O0L1-LZgWJJqaVlVTQ44jnZiT4A)
* [CMIP6_OMIP_chemistry_standard_output](https://docs.google.com/spreadsheets/d/1SfxHKASSwLbPM6xBDjZ6Y8oIxx9APLOlCG9G0lzIu7o)

