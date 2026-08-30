# Cartographic boundary files from the U.S. Census Bureau

The U.S. Census Bureau provides [cartographic boundary
files](https://www.census.gov/geo/maps-data/data/tiger-cart-boundary.html)
for current U.S. boundaries. The datasets in this package provide a
selection of boundaries from the 2024 Census files. They are objects of
class `sf` from the [sf
package](https://cran.r-project.org/web/packages/sf/index.html). They
are intended to be used with the functions in the `USAboundaries`
package, but the data objects can also be used on their own. The data
attributes associated with these boundaries are unchanged from what is
available in the Census boundary files, with the exception that
`state_name` and `state_abbreviation` columns have been added where
necessary for convience in filtering the boundaries.

## Details

The following objects are included in this package:

- congress_contemporary_lores:

  Congressional district boundaries for the 119th Congress, 1:20m
  resolution.

- counties_contemporary_hires:

  County boundaries, 1:500k resolution.

- counties_contemporary_lores:

  County boundaries, 1:20m resolution.

- states_contemporary_hires:

  State boundaries, 1:500k resolution.

- zipcodes:

  Centroids of Zip Code Tabulation Areas (2019).

See the [USAboundaries package](https://docs.ropensci.org/USAboundaries)
for low-resolution state boundaries and for the functions to access this
data.

## References

U.S. Census Bureau, [Cartographic Boundary
Shapefiles](https://www.census.gov/geographies/mapping-files/time-series/geo/tiger-line-file.html)
(2024).

See the U.S. Census Bureau's "[Understanding Geographic Identifiers
(GEOIDs)](https://www.census.gov/programs-surveys/geography/guidance/geo-identifiers.html)"
and their "[Geographic
Codes](https://www.census.gov/programs-surveys/geography/technical-documentation/code-lists.html)"
pages for the details of this attribute data.
