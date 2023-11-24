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
- As we can see in the plot, the majority of exoplanets were discovered through the Transit Method.
  - We can see a large cluster of exoplanets with a mass 100-1000 times the Earth’s mass and radius 10-20 times the Earth’s radius primarily discovered by the Transit Method.
- The Imaging Method is primarily used to find exoplanets with a radius less than 20 times the Earth's radius and a mass larger than 2000 times the Earth's Mass.
- The Orbital Brightness Modulation Method is primarily used to find exoplanets with a similiar radius and mass to Earth's.
- The Radial Velocity Method is used to find exoplanets with a wide variety of mass and radius. A majority of the exoplanets discovered with this method had a mass less than 10 times the Earth's mass, and a radius less than 3 times the Earth's radius.
- The Transit Timing Variations Method is used to find exoplanets with a large variety of mass and radius compared to the Earth's mass and radius.


## Question: How many Exoplanets were Discorvered Using each Method?
<img width="678" alt="Screen Shot 2023-11-23 at 10 51 10 PM" src="https://github.com/adityakmehrotra/Analyzing-Exoplanets/assets/24847438/100e0d03-3187-4372-89c5-f2d246018136">

### Observations
- As we can see in the barplot, the clear majority of discoveries was made with the Transit Method.
- The next Method used the most to discover exoplanets was the Imaging Method followed closely by the Radial Velocity Method.
- The Transit Timing Variaions Method was used to discover very few exoplanets.
- The Orbital Brightness Modulation Method was used to discover even fewer exoplanets, and the least among all of the five methods.


## Question: What is the distribution of the masses of exoplanets in the dataset
<img width="690" alt="Screen Shot 2023-11-23 at 10 50 48 PM" src="https://github.com/adityakmehrotra/Analyzing-Exoplanets/assets/24847438/86a1f79a-ba00-46bc-b104-1ab975825a5a">
