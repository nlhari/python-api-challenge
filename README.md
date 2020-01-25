# python-api-challenge

----
## Key Trends Observed

### Trend 1:
Temparature gets warmer as we get closer to equator (lat=0).

Also, noticed that eventhough random.uniform function was used to select cities, the report above shows the data is more skewed towards northern hemisphere - fact that there are lot of cities between lat 60 to 80 whereas no city selected below lat -60. This is because there are more habitable land in the northern hemisphere in those region than in southern hemisphere. Southernmost tip of Chile is about -55 and barely any cities across that latitude anywhere.

### Trend 2:
Notice temparature drops lot colder as we go up the northern hemisphere (lat > 20), whereas for the same lat (< 20) on southern hemisphere it is still warmer. This makes sense as the weather was checked on Jan 24 when it is Winter in Northern hemisphere and Summer in Southern hemisphere.

### Trend 3:
From the two regression plots above, notice that Northern Hemisphere has a negative correlation i.e. temp dropping as the latitude increases. As mentioned before, it is currently winter in the north. The Southern Hemisphere plot is a positive correlation i.e. temp gets warmer as we get closer to equator since it is summer in the south.

### Trend 4:
Humidity is higher as we get closer to equator.

### Trend 5:
No discernable relationship between Latitude and Cloudiness.