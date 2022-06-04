# bikesharing
## Overview
The objective of this project was to analyze and visualize data from a bike rental company to help inform decisions to improve the business. The data was submitted as a csv file. Pandas was used to change the 'Trip Duration' column of the data to a datetime data type. The adjusted data file was then imported into Tableau to complete the analysis and visualization. 
### Dashboard Link
[Results Dashboard](https://public.tableau.com/app/profile/david.james.kristek/viz/Bikesharing_Challenge_16537612543450/CheckoutTimesbyGender?publish=yes)
## Results
Seven different visualizations were created using Tableau. The visualizations and a description of the results can be found below. 
<details>
<Summary> Top Starting Locations </Summary>
  
![Top Starting Locations](https://github.com/dkristek/bikesharing/blob/main/images/top_starting_locations.png)
<br>
  This visualization shows the areas in Manhattan with the highest amount of bike rentals. The larger dots with darker shades of blue represents a higher number of bike trips. One reason for certain areas having higher amounts of rentals could be due to those areas having larger tourist populations.
</details>

<details>
<Summary> Top Return Locations </Summary>
  
![Top Return Locations](https://github.com/dkristek/bikesharing/blob/main/images/top_return_loc.png)
<br>
  This visualization shows the areas in Manhattan with the highest amount of bike rental returns. The larger dots with darker shades of red represents a higher number of bike trips. One reason for certain areas having higher amounts of returns could be due to those areas having larger tourist populations. These return hotspots are similar to the top starting locations. This could be due to customers staying within Manhattan rather than travelling to other parts of New York City.
</details>

<details>
<Summary> Checkout Times </Summary>
  
![Checkout Times](https://github.com/dkristek/bikesharing/blob/main/images/checkout_times.png)
<br>
  This visualization illustrates the most frequent bike trip durations by minute and hour. The majority of the rentals last under one hour. The peak is around 5 minutes with over 140,000 bikes being rented. A possible explanation for this could be that customers are using the bikes for short distance travel rather than walking or using public transportation. 
</details>

<details>
<Summary> Checkout Times By Gender </Summary>
  
![Checkout Times by Gender](https://github.com/dkristek/bikesharing/blob/main/images/checkout_times_gender.png)
<br>
  This visualization illustrates the most frequent bike trip durations by minute and hour with three lines representing genders (Male, Female, Unknown/Non-Binary). Each of the lines has a similar shape to the original Checkout Times graph. However, this graph shows that men make up the largest portion of the rental customer base.
</details>

<details>
<Summary> Trips By Weekday </Summary>
  
![Trips by Weekday by Hour](https://github.com/dkristek/bikesharing/blob/main/images/trips_weekday_hour.png)
<br>
  This visualization acts as a heatmap for the amount of rentals throughout each hour of the week. The twelve hour period between 7 A.M and 7 P.M is generally the most active rental period for each day of the week. On weekdays, 7 - 9 A.M and 5 - 7 P.M are the most heavily active bike rental times. This could suggest that customers are using the bikes to commute to and from work each day. While on weekends, the bike rentals are more evenly spread throughout the twelve hour block of heavy activity. This suggests that customers are using the bikes to travel through the city throughout their days.
</details>

<details>
<Summary> Trips By Gender </Summary>
  
![Trips by Gender](https://github.com/dkristek/bikesharing/blob/main/images/trips_weekday_hour.png)
<br>
  This visualization acts as a heatmap for the amount of rentals throughout each hour of the week separated by gender. The general trends seen in the previous Trips By Weekday graph can also be seen here in each gender category. However, the Male graph tends to be darker as they make up a larger portion of rental customers.
</details>

<details>
<Summary> Trips By Gender By Weekday </Summary>
  
![Trips by Gender by Weekday](https://github.com/dkristek/bikesharing/blob/main/images/trips_gender_weekday.png)
<br>
  This visualization acts as a heatmap for the amount of rentals throughout each day of the week separated by gender. The general trend is that subscribers make up the larger portion of the rentals. However, this is not true for non-binary category possibly due to a lack of data.
</details>

## Summary
