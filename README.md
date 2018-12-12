# OpioidDeathRate
The prescription opioids use is popular be using in some specific area, such as cancer therapy, and pain relief. From 1999 to 2016, more than 630000 people have died from a drug overdose. As of 2016, 2.1 million Americans have an opioid use disorder, and more than 63600 people died from drug overdoses, which makes it the leading cause of injury-related death in the United States (CDC, 2018). I want to use the statistics to dig into the related data and come up with the idea to help end this crisis. Since the different states have different limitation and policy for the opioid use, I try to connect the opioid cause death rate data with all the county in the United States. From that, I can use multiple algorithms to dealing the data, including data visualization to show the distribution for the affection.
# Methodology (Algorithm or analysis)
After gathering raw data, I first process the data that emerge different columns into one general data set, including the number of different races of people, different genders, income levels etc. in different counties. After sorting the data by different counties, I try to find out how different factors are related to the death number within Opioid death rate in different counties in each year. I will conduct a one-way ANOVA analysis in order to find out how different the races relating with the death numbers due to Opioid Crisis. As reports, from 2013 to 2016 is the most increasing year for the Opioid crisis, I'm interesting to find out the relations between each of them and the yearly change for the opioid crisis. The result be presented by showing a map of America, categorized by different county. Furthermore, I will use different colors to represent how close different factors are related to the death rate with linear regression plots. After showing the connecting of different factors to the death rates, I sum up the report by concluding the most influential factor to Opioid Crisis and which year was most effected by opioid using. By obtaining such conclusion, people will be more aware of such factor, hence will help prevent Opioid Crisis or reduce it in general.

### Here are some of the variables retrieved:

**OpioidDeathRate** : Death rate cause by the opioid. OpioidDeathRate = Opioid Deaths Population / Total Population
**UnemploymentRate** : The unemployment Rate in each counties in United States.
**CancerDeathRate** : The death rate related with cancer.
**prescribingRateAVE** : The Average amount of opioids prescribed in the US from 2013 to 2016
**ProvertyPre** : All Ages of people in Poverty Percent base on median family income by family size from 2013 to 2016
**geometry** : The geometry information conduct for each counties in U.S.

# Summary
## Conclusion
As a result, we can see the opioid cause death rate with cancer death rate is mostly correlated, and 2014 have the most massive increasing rate in the opioid cause of death.

Prescription opioids can be used to treat moderate-to-severe pain and are often prescribed following surgery or injury, or for health conditions such as cancer. In recent years, there has been a dramatic increase in the acceptance and use of prescription opioids for the treatment of chronic, non-cancer pain, such as back pain or osteoarthritis, despite serious risks and the lack of evidence about their long-term effectiveness. As one of the most effective elements for the opioid cause of death, the government should control the prescription opioids with strict law to decreasing the opioid using from the beginning.

But sometimes the prescription opioid could be helpful, especially on the cancer treatment, that's the reason why the cancer death rate is mostly related to opioid cause death rate. As the way to figure this, I suggest people using some alternative medicines which might not as good as opioid medicines, but without addiction.

Surprisingly, I find the relation between poverty rate and opioid was changed during the years, the higher poverty rate cause the high opioid death rate in 2013, but from 2014, the higher poverty rate cause the decreasing of the opioid death rate. I did some search on the website, which the result show the pricing of opioid medicines was increasing serval times during 2013 to 2015, and that might the reason cause the poor people cannot afford the medication for cancer or opioid using which produce the high increase in both death rate. To solve this, I think the government needs to provide some law to limit opioid medicine pricing change. I know some medicine company produces opioid because the huge benefit behind it, with the regulation or restriction, the balance between profit and manufacturing would be a break so that the opioid could be replaced by something else which more useful for treatment.

## Future Directions
The weaknesses of my model can be overcome. The important weakness of low sample size after merge can be remedied by waiting until more data becomes available as time passes.

The method in real life problem always have a lot of missing value, this mtheod was not doing good work on that which replace the missing value by some basic method such as mean and median. In a good way to solve this, I can apply linear regression between my variables, or using K-NN methed to generate the most fittble numbers for the missing value, which will lower the varience of the data.

Our analysis also fails to include the fact that the month or day likely has a strong effect on opioid cause of death, so implementing some sort of time series analysis would likely give me greater power in detecting differences in our variables of interest.

Other ways to improve the model include the use of cross-validation to see if a polynomial term of some variables could provide more predictive power without overfitting.

Other areas of interest for analysis would be to make comparisons between some big cities such as NYC or Miami city instead of just doing an analysis of the counties.

## Reference
[1] Center of Disease Control and Prevention. (2018, December 5).Multiple Cause of Death, 1999-2017 Request. Retrieved December 5, 2018, from https://wonder.cdc.gov/mcd.html

[2] Center of Disease Control and Prevention. (2018, December 5).Prescription Opioid Data. Retrieved December 5, 2018, from https://www.cdc.gov/drugoverdose/data/prescribing.html

[3] Center of Disease Control and Prevention. (2018, December 5).Cancer Data and Statistics. Retrieved December 5, 2018, from https://www.cdc.gov/cancer/dcpc/data/index.html

[4] U.S. Census Bureau. (2018, December 5).Income and Poverty in the United States (2013-2016) Retrieved December 5, 2018, from https://www.census.gov/data/tables/2017/demo/income-poverty/p60-259.html

[5] U.S. Census Bureau. (2018, December 5).Cartographic Boundary Shapefiles - States. Retrieved December 5, 2018, from https://www.census.gov/geo/maps-data/data/cbf/cbf_state.html

[6] U.S. Census Bureau. (2018, December 5).Cartographic Boundary Shapefiles - Counties. Retrieved December 5, 2018, from https://www.census.gov/geo/maps-data/data/cbf/cbf_counties.html
