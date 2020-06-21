## COVID-19 and US State Clustering by Aggregate Smartphone Movement

I used k means and hierarchical clustering algorithms to segment US states by aggregate smartphone movements as a proxy for human movement, resulting in clusters exhibiting similar activity through commercial spaces for greater understanding of state level exposure and response to shelter-in-place orders.  These segments are helpful for policy makers and epidemiologist, as they identify patterns in exposure, movement, and effective implementation of policies beyond the current COVID-19 crisis.

## About the Dataset
-  In the wake of the global COVID-19 pandemic, Place IQ, a commercial location intelligence and space mapping service, made data on mass, de-identified Smartphone movement public. 
-  Victor Couture, Jonathan Dingel, Allison Green, Jessie Handbury, Kevin Williams, Hayden Parsley, and Serena Xu have created a dataset of device exposure indices for each US State and the District of Columbia based on the data provided by Place IQ. 
  - Each device exposure index or DEX represents the average number of cellular devices visited in the same commercial spaces as any given device based on cell phone tower pings
  - Their work can be found [here](https://github.com/COVIDExposureIndices/COVIDExposureIndices)
- The resulting dataset includes 4,539 rows, one row for each state for each day from January 20, 2020 through April 9, 2020.
- There are 53 features in the dataset, including DEX figures separated by income quartile, education quartile, and race.



