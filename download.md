---
layout: page
title: Downloads
subtitle: 
---
We release the raw numbers behind our analysis. For each data release we will post two files:

### Excel/CSV containing measurements by US state

This file contains the current social mobility index for each US state and territory. The columns are:

- `location` The US state or territory and the US as a whole. We include some cities and will add new ones over time.

- `Mobility from 2019.01.01 to 2020.03.15`	The social mobility index for the entire time period of the dataset, from January 1, 2019 up to the date before social distancing.

- `Mobility from 2020.03.16 to 2020.03.29` The social mobility index since March 16, 2020. Note that social distancing started at different times for different states, but we don't include that analysis in this data.

- `reduction` The percent reduction of social mobility. This is computed as `Mobility from 2020.03.16 to 2020.03.29` / `Mobility from 2019.01.01 to 2020.03.15`. 

- `num_users` The number of unique Twitter users that were used to compute this row.

- `num_records` The number of unique tweets used to compute this row.

### Longitudinal data with weekly measurements by US state
This file contains the social mobility index for every location for each week starting in January 1, 2019.


## Data Files
#### March 30, 2020

- [social_mobility_index.state_data.20200330.csv](data/social_mobility_index.state_data.20200330.csv)

- [social_mobility_index.longitudinal.20200330.csv](data/social_mobility_index.longitudinal.20200330.csv)
