# Release notes

## Market View 6

### Version 6.4.0

* Remove old google analytics&#x20;
* Update wording in about our data page&#x20;
* Make entire nav boxes clickable
* Redirect to /your-data after connecting veracross&#x20;
* Swap to show DASL value in column when there is a mismatch&#x20;
* Bump @percy/cli from 1.8.0 to 1.26.0&#x20;
* Add admissions data to standalone zip view&#x20;
* Update mapbox&#x20;
* Add forecasts to zip view
* Update affordability statement text&#x20;
* Add a column for 10-year change to the overview tab of trends.
* Add parenthetical percentages to race counts on data cards
* Split feature flag for blackbaud and veracross&#x20;
* Fix for race breakdown percentages when zero&#x20;
* Update text around the beta&#x20;
* Change styling of the race breakdown percentages&#x20;

### Version 6.1.0

* Label counts for admissions list data as 'students' rather than
* Add sparkles emoji to the new tag
* Add overlay to tables that are scrolled horizontally
* Copy edits on sort bar on trends
* Updates to trends/enrollments
* Only use localstorage for map layer status on /map
* Add admissions data section to map cards
* Add choropleths for most recent and second most recent year applications
* Request previous three years, not including current school year for&#x20;
* Display admissions items in the zip on the map, including a tooltip&#x20;
* Add filter to request for admissions list items on map to only get two most recent years
* Update text of link to download upload template / Obscure client secret field on veracross form&#x20;
* Rename multiple to multiracial
* Correct tutorial "hole" on filters on very wide monitors
* Fix bug where zip codes would toggle visibility when mousing over

### Version 6.0.0

* New "Your Data" section with ability to add admissions data
* Enable a new section under trends: "Enrollment" that uses admissions data
* Add in-app chat
* Update help link
* Update terms and conditions&#x20;
* Format saturation and conversion totals as percentages with one decimal
* Fixes for analysis chart
* Add (last 10 years) to opportunities sort selector options
* Fix text color of school tooltips on maps
* Remove population series from diversity chart on my-school/trends&#x20;
* Update link to uploading field guide
* Update Check Now links to Learn More and link to help sections
* Implement the help modal on Your Data
* Add terms notice to connect pages and data upload pages&#x20;

## Market View 5

### Version 5.0.15

* Update terms&#x20;
* Fix full-pay, partial-need, and full need labels on distribution chart when all of a particular section is deselected&#x20;
* Fix some library UI issues&#x20;
* Fix display of author on reports in library&#x20;
* Replace many address fields on school with one, 'address'&#x20;

### Version 5.0.8

**Released May 10, 2022**

* Change choropleth on trends/overview to be forecast percentage
* Remove the dash in the drive time selectors

### Version 5.0.7

**Released May 2, 2022**

* Upgrade to 4.2 of Ember + addons
* Delete the old research tab
* Fix uploading multiple files and dropping files
* Remove zip labels on trends
* Add tooltips on zip lists on trends
* Add year selector to population change chart
* Hide All Ages series by default on School-age population by age
* Add tooltip for private schools on trends
* Extend styles from trends to the rest of the app
* Add percentage of children of total population as choropleth option
* Display 'No addresses found' when no results searching for addresses
* Remove boxes around data labels on column charts on map
* Add query params to trends for drive time, centerpoint and tuition so they persist across tab and when sharing links
* Persist layer selection status in local storage
* Remove ability to edit age preferences
* Change age buckets on trends to default buckets
* Fix horizontal scroll on mobile
* Create the new 'Your Data' route, available at /your-data
* Update fields to correctly display PK-12 instead of K-12

### Version 5.0.6

**Released March 04, 2022**

* Allow duplicate addresses across datasets

### Version 5.0.5

**Released Feb 08, 2022**

* Add option of selecting boys, girls, children in the query paragraph on Map View
* Improve render performance on the Map View when many zips are returned
* Replace the forecast toggle with a checkbox
* Display a warning 5 minutes before a user's session will expire, giving the user the option to log in again or to keep working
* Display a dialog when the user's session is expired, telling the user to log in again
* Use contribution %s for financial gap calculations
* Display a tooltip on income breakdown charts on cards to show the financial gap for each income range
* Round affordability numbers to nearest 1000 to convey their fuzziness
* Add a chart to trends/affordability to show the breakdown of tuition into financial gap and contribution
* Add zones for full pay / partial need / full need to household income distribution by race chart on Trends
* Add additional quotes to the landing page
* Link ZIPs to an page with all data about that ZIP

### Version 5.0.4

Released June 16, 2021

* Display names of ZIPs where they are displayed
* Add additional controls to show and hide series on charts on the Trends tab
* Add ability to save images of maps on Trends
* Add a legend for the travel time display on maps on Trends
* Fix a bug on the Map tab where clicking on a ZIP in the map that started with '0' would not scroll to the ZIP's card
* Show labels on maps when zoomed out further
* Show the tuition on saved reports
* Fix the display of ZIPs on the maps in the Library
* Various Copy Edits

### Version 5.0.3

#### Released Jun 07, 2021

* Improve the mobile UI of the trends area



### Version 5.0.2

#### Released May 19, 2021

* Add more debugging info around missing location info



### Version 5.0.1

#### Released May 18, 2021

* Adjust styles to make control sentence UI work on mobile
* Change how copying works to possibly make it more reliable on Chrome
* Add debugging around fetching zips if the lat and long are missing



### Version 5.0.0

**Released May 17, 2021**

* Add /trends section
* Remove /research
* Move Trends to be the landing page after login

## Market View 4

### Version 4.5.1

**Released May 03, 2021**

* Add /trends but keep it hidden until we're ready to release

### Version 4.5.0

**Released Mar 15, 2021**

* Add additional map color options and data about children of color
* Close the upper-left hamburger menu when clicking anywhere outside of it
* Display a tooltip on the map when clicking a point from an address dataset
* Upgrade Ember
* Upgrade Highcharts

### Version 4.4.0

**Released Jan 07, 2021**

* Appropriately title the filenames of downloads of charts
* Appropriately title data in chart downloads
* Hide duplicate dropdown navigation items (under hamburger) on desktop
* Bugfix: Correctly get fresh data for forecasted reports when chosen search parameters change
* Bugfix: Hide children-of-color data and maps until data can be corrected
* Bugfix: Show the year of data displayed, not current year, under the income breakdown charts



### Version 4.3.0

**Released Dec 14, 2020**

* Change the selection of the visualization variable to a selection of map visualization by name
* Default to showing 'Number of Children by Zip Code' map visualization
* Default the map zoom to encompass all the zip codes in the result, rather than just the travel time border
* Show a tooltip in the upper right of the map when a zip code is hovered with details for that zip
* Make the Layer Selector and Report Downloads more prominently featured with icons in the upper right
* Move the visualization variable scale over the map on the bottom right.
* Makes consistent use of colors for typography
* Include the # of Children of Color in selected age ranges on the zip card
* When showing the forecast in the report results, show the % change for each value
* Fix a display issue with labels that have tooltips



### Version 4.2.0

**Released Dec 01, 2020**

* Update the icon for the menus on charts
* Update the export options on charts
* Add clarification about scope of data on the Demographics pane of the zip card
* Update links to Help, add additional link to Help in the header
* Bugfix: Fix styling of menus on library
* Bugfix: Ensure files that are text/csv successfully upload

### Version 4.1.0

**Released Nov 09, 2020**

* Fix a bug where financial gap was not available in exports



### Version 4.0.0

**Released Oct 16, 2020**

* Use a hosted image for the twitter card

