# PBS 2017 Census Data

This repository contains digitized data from Pakistan Bureau of Statistics's 2017 Census results. We converted them to csv format to help analysts and researchers make use of the data in research projects.

Data Source: https://www.pbs.gov.pk/content/district-wise-results-tables-census-2017

## Organization

Each of the districts in the link above have 40 tables, broken down by tehsil / sub-division. The data folder will be organized by table number and contain various versions of the underlying raw data. All tables completed and uploaded are listed below - this is a work in progress.

01 - Area, Population by sex, sex ratio, population density, urban proportion, household size and annual growth rate

04 - population breakdown by age, sex, rural/urban - tehsil/district level

14 - literate population (10 years and above) by level of educational attainment, sex, age group and rural/urban

19 - disabled Population (10 Years and Above) by Sex, Age Group, Economic Activity and Rural/Urban

29 - houshold room occupancy and household size - district level

33 - construction material used and ownership status  - district level

35 - housing units by ownership, source of drinking water, lighting, cooking fuel used and rural/urban

37 - housing units by tenure, kitchen, bathroom, latrine facilities and rural/urban

40 - number of households by source of information and rural/urban

For the most disaggregated version of data available, download tehsil_disaggregated or district_disaggregated version as per your needs.

## Mapping data

We have also provided shapefiles for you to be able to map out the data and explore spatial patterns. The shapefiles are dated (2010) so use accordingly. We have also provided a key to link district names in PBS data to the shapefile attribute table. The source of these shapefiles is OCHA's admin boundaries database for Pakistan, among other sources. There are some differences between the boundaries between PBS and OCHA which are are more apparent at the tehsil / adm3 level. h/t to @suzairjunaid for pointing this out.

Link to source: https://data.humdata.org/dataset/pakistan-union-council-boundaries-along-with-other-admin-boundaries-dataset

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change. Feedback is welcome.

Please make sure to cite us if using the data in your projects.

## License
[MIT](https://choosealicense.com/licenses/mit/)
