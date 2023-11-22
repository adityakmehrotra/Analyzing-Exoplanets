# Analyzing-Exoplanets
Using ggplot2 in R to Analyze NASA's Exoplanet dataset.

## Questions
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


## Question: How is the Exoplanets Mass related to its Radius?
<img width="679" alt="Screen Shot 2023-11-22 at 1 44 55 PM" src="https://github.com/adityakmehrotra/Analyzing-Exoplanets/assets/24847438/0ae79486-c512-4bb6-9efd-931ccabef264">

### Observations
- The radius of exoplanets seem to be directly correlated to the mass
- Informally, we can interpret the blue curve in the plot as a correlation between the mass and radius of an exoplanet
- We can see a large cluster of exoplanets with a mass 100-1000 times the Earth's mass and  radius 10-20 times the Earth's radius.
- There are some outliers, mostly with a significantly larger mass than radius.


## Question: How is the Exoplanets Mass related to its Radius, and which Discovery Methods were most common in discovering these Exoplanets?
<img width="681" alt="Screen Shot 2023-11-22 at 1 47 39 PM" src="https://github.com/adityakmehrotra/Analyzing-Exoplanets/assets/24847438/7058178b-78b6-4c5e-8334-323f2038bb0b">

### Observations
