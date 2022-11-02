# Our_first_project
Group 9: Team Not Happy worked together to analysis the correlation between compiled life evaluations of a 6 factor index to rankings of happiness in each country in Git.

When inquiring about how happy someone is, one often reflects on developing mental or emotional states that are evaluated based upon eudaimonia, prosperity, subjective well-being, and life satisfaction. Every year the United Nations General Assembly directs the Gallup Poll organization to randomly ask at least 1000 people in each of 160 countries to respond to a simple question:  On a scale of 0 to 10, with 0 being the worst possible life and 10 being the best, how do you rate your life at this moment? From this dataset, the UN publishes the World Happiness Report.  The report tries to factor in many quality of life variables to illustrate possible correlations.

Does this mean there is a formula for obtaining happiness?

Within this repository you will find data source files for:
World Happiness Reports for 2015-2019
Our version of the World Happiness Report 2019 with all the compiled factors underconsideration
WHO Alcohol Consumption for 2019
Fertility Rate Per Capita for 2019

Within the World Happiness Report 2019 you will find: 

That outside of the happiness score, each variable was set as a proportion of its maximum value to gauge the relative magnitude of their coefficient. Through this we were able to create an experimental equation for happiness
Expected Happiness Score = (2.485 * Income) - (1.303 * Suicide) - (0.795 * Displaced Persons) 
- (2.170 * Fertility) + (0.470 * taxes) + (0.807 * Cell) + 5.484

Within the Unwrapping Happiness powerpoint you will find: 

Analysis of Happiness vs Income:
Countries with at least 50% of the maximum adjusted income had higher overall happiness, possibly as the result of an individual being able to fulfill basic human and societal needs. Rates below this presented downward trends in scores. However, happiness still slightly declines as income rises above 80%. This may be due to the fact that economic cushion aids in comfort, and it is not always the definitive answer for happiness. 

Analysis of Happiness vs Cell Subscriptions:
Here we see the positive correlation between cell phone subscriptions and happiness. In countries with > 80% of the max cell subscriptions coefficient, it would be interesting to compare happiness rankings in rural vs. urban areas and average time spent on devices within the same countries.

Analysis of Happiness vs Taxes:
People who live in areas with progressive tax rates report higher levels of happiness, which may be due to fairer redistribution of wealth and resources throughout communities reducing barriers to basic needs.

Analysis of Happiness vs Fertility:
As some parents may choose to better allocate resources to fewer dependents. Fertility rates of 20 - 40% lowered the negative impact on the happiness score. Certain nations with birth rates > 50%, may be due to need for agricultural labor, or a result of less access to family planning and contraception. 

Analysis of Happiness vs Internally Displaced Persons:
Communities that suffer from increased rates of internal displacement show negatively impacted scores. A point for future analysis may be to see how long after displacement events like this does it continue to affect overall happiness rankings.

Analysis of Happiness vs Suicide Rates:
Lower suicide rates is inversely correlated to higher rankings of happiness. However, Lesotho is an extreme outlier in this analysis, their coefficient’s impact could be driven by socioeconomic challenges like one of the highest rates of HIV/AIDS infections, half of the population living below the poverty line, and battling spikes in murder and rape.
