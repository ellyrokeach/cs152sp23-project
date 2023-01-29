# Predicting Uninhabitable U.S. Counties due to Extreme Heat

## Project Description
Extreme heat can cause illness and death, especially among vulnerable populations who do not have enough access to self-protection strategies. Communities of elderly adults, young people, low-income people, people of color, and houseless people are particularly vulnerable. In a 2021 study on dimensions of thermal inequity, UC Davis researchers found that California’s poorest neighborhoods were 6 to 7 degrees hotter than the wealthiest neighborhoods “on both extreme heat days and average summer days” (Dialesandro, Brazil, Wheeler, & Abunnasr, 2021, p. 5). In some parts of the world, extreme heat has already rendered some towns uninhabitable, causing communities to abandon them entirely and migrate. According to a recent study published in Nature Climate Change about the increasing global risk of deadly heat, “around 30% of the world’s population is exposed to a deadly combination of heat and humidity for at least 20 days each year” (MIT Technology Review).

For these reasons, in my project, I plan to determine when counties across the United States will reach unsurvivable temperatures on average and become uninhabitable. This will be helpful for planning strategies for protection and adaptation, especially for communities that are particularly vulnerable. It will also help inform crucial changes in infrastructure and policy, as well as the development of global climate solutions in general.

I will use data of average temperatures of United States counties over the course of several decades provided by the [National Centers for Environmental Information](https://www.ncei.noaa.gov/access/monitoring/climate-at-a-glance/county/mapping). I plan to use this time series data to train a model to make predictions for increased average temperatures in U.S. counties using an LSTM network, a type of RNN capable of learning long-term dependencies.

After using this network, I will then compare the predicted average temperatures to the maximum temperatures that humans can tolerate and determine which U.S. counties will become uninhabitable soonest. I could also then visually indicate these uninhabitable counties by plotting them on a map. To increase the complexity and perhaps accuracy of the project, I could also introduce other datasets, including humidity levels, which also play a role in determining how high a temperature humans can survive. I could also look at datasets that include frequency and duration of heat waves in counties across the country. Looking at the likelihood of extreme heat waves would be helpful, since one heat wave could also make a location unsurvivable, and its occurrence might not be reflected in the average yearly temperature.

## Project Goals
1. Aggregate data for average temperatures in U.S. counties from the National Centers for Environmental Information.
2. Understand and design an LSTM network, and train it on the time series data.
3. Make revisions as necessary, and possibly add complexity by introducing other datasets.
4. Create visuals to display the results, and plot the uninhabitable counties on a map.
5. Write an academic paper documenting the process, model, and results.

## Bibliography
Bencherif, K. (2021, November 15). How Climate Change Turned This Moroccan Village Into a Ghost Town. In These Times. Retrieved January 29, 2023, from https://inthesetimes.com/article/morocco-oasis-es-sfalat-tafilalet-abandoned-village-climate-change-ghost-town 

Buis, A. (2022, March 9). Too Hot to Handle: How Climate Change May Make Some Places Too Hot to Live. NASA. Retrieved January 29, 2023, from https://climate.nasa.gov/ask-nasa-climate/3151/too-hot-to-handle-how-climate-change-may-make-some-places-too-hot-to-live/ 

Crownhart, C. (2021, July 9). How Hot is Too Hot for the Human Body? MIT Technology Review. Retrieved January 29, 2023, from https://www.technologyreview.com/2021/07/10/1028172/climate-change-human-body-extreme-heat-survival/

Dialesandro, J., Brazil, N., Wheeler, S., & Abunnasr, Y. (2021). Dimensions of Thermal Inequity: Neighborhood Social Demographics and Urban Heat in the Southwestern U.S. International Journal of Environmental Research and Public Health, 18(3), 941. doi:10.3390/ijerph18030941

Environmental Protection Agency. (2022, August 1). Climate Change Indicators: Heat Waves. EPA. Retrieved January 29, 2023, from https://www.epa.gov/climate-indicators/climate-change-indicators-heat-waves 

Mora, C., Dousset, B., Caldwell, I. et al. Global Risk of Deadly Heat. Nature Climate Change 7, 501–506 (2017). https://doi.org/10.1038/nclimate3322

NOAA National Centers for Environmental Information. (2023, January). Climate at a Glance: County Mapping. Retrieved on January 29, 2023 from https://www.ncei.noaa.gov/access/monitoring/climate-at-a-glance/county/mapping

Smith, J. M. (2021, November 19). Urban Extreme Heat Dataset Offers Population Exposure Estimates for More Than 13,000 Urban Settlements Worldwide. NASA. Retrieved January 29, 2023, from https://www.earthdata.nasa.gov/learn/articles/urban-extreme-heat-dataset 

Waldron, L., & Lustgarten, A. (2020, November 10). Climate Change Will Make Parts of the U.S. Uninhabitable. Americans Are Still Moving There. ProPublica. Retrieved January 29, 2023, from https://www.propublica.org/article/climate-change-will-make-parts-of-the-u-s-uninhabitable-americans-are-still-moving-there 
