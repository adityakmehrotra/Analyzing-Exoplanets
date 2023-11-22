# Analyzing-Exoplanets
Using ggplot2 in R to Analyze NASA's Exoplanet dataset.

I will observe the answers to the following questions:
- How is the Exoplanet's Mass related to its Radius?
- Which Discovery Method is most common when discovering new Exoplanets?
- How many Exoplanets were Discovered Using each Method?
- What is the Distribution of the Masses of Exoplanets in the dataset?

## Exoplanet Data
I will be working with data on exoplanets; exoplanets are planets orbiting stars outside our Solar System.  The data were pulled from the [NASA Exoplanet Archive](https://exoplanetarchive.ipac.caltech.edu/index.html) on September 12, 2022.

The variables we will be working with are defined below.  If you want more details, please see the exoplanet archive [data column definitions](https://exoplanetarchive.ipac.caltech.edu/docs/API_PS_columns.html) (using the column names in the raw data).

- `planet` = Planet Name
- `method` =  Method by which the planet was first identified
- `year` = Discovery Year (the year it was discovered)
- `number` = Number of Planets
- `radius` = Planet Radius (units: Earth Radius)
- `mass` = Approximate or Minimum Planet Mass (units: Earth Mass)
