# Prerequisite

To complete this project, you will need to master data manipulation in Python or R, apply these languages to descriptive statistics as well as automatic classification.

# Scenario
Your food company wants to expand internationally. It specializes in chicken 

The international, yes, but for the moment, the field of possibilities is very wide: no particular country or continent is for the moment chosen. All countries are conceivable!

Your objective will be to help target certain countries more specifically, with the aim of then deepening the market study. In particular, the ideal would be to produce "groups" of countries, more or less large, whose characteristics are known.

In the first instance, the strategy is to export rather than to produce locally, i.e. in the new target country or countries.

# The data
Do you remember FAO in one of your previous projects? Come on, let's go back! You already know the interface of the site, it's up to you to [find the data](http://www.fao.org/faostat/fr/#data) that will be useful for the project.

# Skills assessed
- Interpreting a PCA
- Testing the suitability of a law by a statistical test
- Building and reading a dendogram

# Your mission
In order to identify countries suitable for inclusion in the chicken market, you were asked to target countries. You will also need to study the diets of each country, particularly in terms of animal proteins and calories.

Construct your sample containing all available countries, each characterized by these variables:

- population difference between a previous year (of your choice) and the current year, expressed as a percentage;
- Proportion of animal protein in the total amount of protein available in the country's food supply;
- per capita food protein availability;
- food availability in calories per capita.

Construct a dendrogram containing all the countries studied, then cut it to obtain 5 groups.

Characterize each of these groups according to the variables mentioned above, and optionally according to other variables that you consider relevant (e.g. GDP per capita). You can do this by calculating the position of the centroids in each of the groups and then commenting and critiquing them in relation to your objectives.

Give a short list of countries to target, presenting their characteristics. A more precise breakdown than 5 groups can be made if necessary to target a reasonable number of countries. 

View your scores in the first factorial plan obtained by ACP.

In your partition, you have obtained distinct groups. So check that they are really different. To do this, perform the following statistical tests:

- a goodness of fit test: among the 4 variables, or among other variables you find relevant, find a variable with a normal distribution;
- a test of comparison of two populations (in the Gaussian case): choose 2 clusters among those you have determined. On these 2 clusters, test the Gaussian variable thanks to a comparison test.

