## ESM 244 Lab 1 Materials 

Prepared by: Allison Horst

### Data used: 

- SF trees data are from [SF Open Data Portal](https://data.sfgov.org/City-Infrastructure/Street-Tree-List/tkzw-k3nq). See more information from Thomas Mock and TidyTuesday [here](https://github.com/rfordatascience/tidytuesday/tree/master/data/2020/2020-01-28). 

- SF roads shapefile is from [data.gov](https://catalog.data.gov/dataset/tiger-line-shapefile-2017-county-san-francisco-county-ca-all-roads-county-based-shapefile).

### Objectives:

- Review some data wrangling basics with `dplyr`
- Introduce some new `dplyr` and `tidyr` functions
- Convert lat/lon to spatial coordinates with `sf::st_as_sf`
- Make static and interactive maps with `ggplot` and `tmap`
