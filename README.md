powergeneration
===============

Power Generation Facilities

This is data taken from the Energy Information Administration, 2012 EIA-860  "Generators" file.

- http://www.eia.gov/electricity/data/eia860/

The EIA data has been conflated with USEPA Facility Registry Service (FRS) data providing lat/long values and linkages to regulated EPA programs.

- http://www.epa.gov/enviro/html/fii/index.html

The FAC_URL attributes provide linkages to EPA FRS Facility Detail Reports, e.g. http://oaspub.epa.gov/enviro/fac_gateway.main?p_regid=110045951216

These have been filtered by: 
- EIA-860 STATUS = 'OP' (Operating)

And then broken out into separate files
- [solar.geojson](https://github.com/DruidSmith/powergeneration/blob/master/solar.geojson) EIA-860 ENERGY_SOURCE_1 = 'SUN' (Solar (Photovoltaic, Thermal)
- [hydro.geojson](https://github.com/DruidSmith/powergeneration/blob/master/hydro.geojson) EIA-860 ENERGY_SOURCE_1 = 'WAT' (Water, Conventional or Pumped Storage)
