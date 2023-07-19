# data-archive

This repository has space for archived output data from analyses using covidestim model runs.
This readme describes for each folder the data files that are present, and includes the appropriate citation that describes the methods to generate the output, and that should be attributed for any derivations or uses of that data.

## covid-immunity

### Data
< covidestim | immunity >-daily-< fips | state >.csv.xz

Load data in R using `file <- vroom::vroom("<path_to_file>.csv.xz")`

### Definition of shorthands
- covidestim: the covidestim generated files used as input to render the immunity files (includes: infections, Rt)
- immunity: the estimated immunity estimates (includes: immunological exposure (total and by type); effective protection (total and by type of exposure).
- daily: entries are by date (one for each date)
- fips / state: geographies included in file

### Citation
Klaassen, F., Chitwood, M., Cohen, T., Pitzer, V.E., Russi, M., Swartwood, N.A., Salomon, J.A., Menzies, N.A. (2023). Population Immunity to Pre-Omicron and Omicron Severe Acute Respiratory Syndrome Coronavirus 2 Variants in US States and Counties Through 1 December 2021, Clinical Infectious Diseases, Volume 76, Issue 3, 1 February 2023, Pages e350–e359, https://doi.org/10.1093/cid/ciac438


## covid-immunity-2022

### Data
< covidestim | immunity >-weekly-< fips | state >.csv.xz

Load data in R using `file <- vroom::vroom("<path_to_file>.csv.xz")`

### Definition of shorthands
- covidestim: the covidestim generated files used as input to render the immunity files (includes: infections)
- immunity: the estimated immunity estimates (includes: immunological exposure (total and by type); effective protection (total and by type of exposure).
- weekly: entries are by date (one for each week, dates refer to the end of a week)
- fips / state: geographies included in file

### Citation
Klaassen, F., Chitwood, M., Cohen, T., Pitzer, V.E., Russi, M., Swartwood, N.A., Salomon, J.A., Menzies, N.A. (2023). Changes in Population Immunity Against Infection and Severe Disease From Severe Acute Respiratory Syndrome Coronavirus 2 (SARS-CoV-2) Omicron Variants in the United States Between December 2021 and November 2022, Clinical Infectious Diseases, 2023;, ciad210, https://doi.org/10.1093/cid/ciad210

