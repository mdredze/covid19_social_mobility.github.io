---
layout: page
title: Download
subtitle: 
---
We release the raw numbers behind our analysis. For each data release we will post two files:

### Excel/CSV containing measurements by US state

This file contains the current social mobility index for each US state and territory. The columns are:

- `location` The US state or territory and the US as a whole. We include some cities and will add new ones over time.

- `mobility_before_distancing`	The social mobility index for the entire time period of the dataset, from January 1, 2019 up to the date before social distancing, March 15, 2020.

- `mobility_after_distancing` The social mobility index since March 16, 2020. Note that social distancing started at different times for different states, but we don't include that analysis in this data.

- `general_reduction` The percent reduction of social mobility. This is computed as 1 - `mobility_after_distancing` / `mobility_before_distancing`.

- `median_reduction` Median value for user level mobility reduction.

- `median_seasonal_reduction`  Median value for seasonal user level mobility reduction by comparing mobility after social distancing and mobility during same period in 2019.

- `num_users` The number of unique Twitter users that were used to compute this row.

- `num_records` The number of unique tweets used to compute this row.

### Longitudinal data with weekly measurements by US state
This file contains the social mobility index for every location for each week starting in January 1, 2019.


## Data Files

- [social_mobility_index.state_data.20200330.csv](data/social_mobility_index.state_data.20200330.csv)

- [social_mobility_index.longitudinal.state.20200330.csv](data/social_mobility_index.longitudinal.state.20200330.csv)

We also present the mobility data for the [100 most populous United States cities](https://en.wikipedia.org/wiki/List_of_United_States_cities_by_population).
 
- [social_mobility_index.city_data.20200330.csv](data/social_mobility_index.city_data.20200330.csv)

- [social_mobility_index.longitudinal.city.20200330.csv](data/social_mobility_index.longitudinal.city.20200330.csv)

Historical data: [here](https://github.com/mdredze/covid19_social_mobility.github.io/tree/master/data)