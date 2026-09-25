## Climate Trends in San Diego, California

![San Diego's Mean Maximum Annual Temperature](/img/sandiego_max_annual_temp.jpeg "San Diego's Mean Maximum Annual Temperature Trend")

*Chart depicting the mean daily maximum temperatures per year from 1939-2025 collected by NOAA's station at the San Diego International Airport, California (USW00023188).*

Although climate scientist agree that San Diego as a whole is becoming consistently warmer, with models predicting an increase of 0.8°C to 2.5°C by 2050, the data above suggest the region has actually been cooling over time at a rate of 0.00275005 °C per year from 1939-2025. However, the results of this OLS linear regression model yield an $R^2$ value of 0.007 and a P-value of 0.439, indicating that the results are not statistically significant and there is almost no linear correlation between temperature and time at this station. These results actually make sense when considering the climate of San Diego and this particular station, which is heavily influenced by the maritime effect due to being quite literally on the coast of the Pacific Ocean. This maritime effect essentially moderates the climate of San Diego due to the absorption of solar radiation by the ocean and daily marine layer of clouds, preventing frequent extreme temperatures and making it difficult to determine how temperature trends are changing based on time alone. 

Despite the lack of conclusion on if annual temperature is increasing or decreasing, it is clear that the variance in annual mean maximum temperatures is becoming more extreme. This means that our cold years are becoming even colder, and our warm years are becoming even warmer, a trend particularly clear after the 90's as the data points become much more spread out across the graph. This also aligns with California's Fourth Climate Change Assessment by the University of California San Diego, which notes the increasing likelihood of extreme weather such as heat waves, drought, and precipitation events, all of which would contribute to more extreme values of maximum mean annual temperatures. The lack of a clear linear trend is also likely influenced by the increase of extreme temperature years as the extreme values of warm and cold years create more scattered points, increasing the amount of variance in the model.

[Detailed code and breakdown here](sd-climate-portfolio-post.html)

<embed type="text/html" src="sd_ann_max_temp_hvplot.html" width="800" height="800">

*Interactive graph of mean daily maximum temperatures per year from 1939-2025 collected by NOAA's station at the San Diego International Airport, California (USW00023188).*


#### References

* Messner, S., Miranda, S. C., Young, E., & Hedge, N. (2011). Climate change-related impacts in the San Diego region by 2050. Climatic Change, 109(Suppl 1), 505–531. https://doi.org/10.1007/s10584-011-0316-1
* Kalansky, J., Cayan, D., Barba, K., Walsh, L., Brouwer, K., & Boudreau, D. (2018). San Diego summary report: California's fourth climate change assessment (Publication No. SUM-CCCA4-2018-009). University of California, San Diego. https://escholarship.org/content/qt0ff253kt/qt0ff253kt.pdf
