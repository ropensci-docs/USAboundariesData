# Historical state and county boundaries for the United States of America

These datasets contain polygons for historical boundaries in the United
States. These boundaries are taken from the Atlas of Historical County
Boundaries. State boundaries cover the period from 1783 to 2000, and
county boundaries cover the period from 1629 to 2000. The attribute data
includes of the changes to the boundaries and the dates with which they
valid. For a full description of all of the columns in the data frame,
see the [documentation in the zip
files](http://publications.newberry.org/ahcb/downloads/united_states.md)
provided by AHCB. The datasets are objects of class `sf` from the [sf
package](https://cran.r-project.org/package=sf). They are intended to be
used with the functions in the `USAboundaries` package, but the data
objects can also be used on their own. The data attributes associated
with these boundaries are unchanged from what is available in the AHCB
shapefiles files, with the exception that `state_name`,
`state_abbreviation`, and `state_code` columns have been added where
necessary for convience in filtering the boundaries.

## Source

John H. Long, et al., *Atlas of Historical County Boundaries*, Dr.
William M. Scholl Center for American History and Culture, The Newberry
Library, Chicago (2010), <http://publications.newberry.org/ahcbp/>.

See also the [AHCB's about
page](http://publications.newberry.org/ahcb/project.md).

## Details

The high resolution boundaries have been generalized to a .01 degree
tolerance (1:2,500,000; 1 inch = 39 miles). The low resolution
boundaries have been generalized to a .05 degree tolerance
(1:12,500,000; 1 inch = 197 miles). See the AHCB website for
higher-resolution shapefiles.

See the [USAboundaries package](https://docs.ropensci.org/USAboundaries)
for low-resolution state boundaries and for the functions to access this
data.
