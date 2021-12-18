# cs519-project

## Title
Interactive choropleth of COVID-19 measures across the USA

## Project Aim
The aim of the project is to develop an interactive choropleth of COVID-19 measures across the USA at the county-level using JHU CSSE COVID-19 Data published on Github (https://github.com/CSSEGISandData/COVID-19). Choropleth visualizations will be generated for confirmed cases, deaths, and recoveries which the user can toggle through, with an option for the user a slider to toggle through dates. Additionally, tooltips will show up when the user hovers over the county map with an optional zoom. 

## Team Members
* Sam Parmar
* Joseph Allen
* Vishwa Kapoor

## Project Elements
* Data Parsing - Load and parse Covid data from JH datasets - 10
* Choropleth chart - display chart with county level resolution - 30
* Chart shading - shade chart using county level covid data - 30
* Timeline visualization - alter chart to show covid data over time - 20
* Additional measure toggles - add toggles to chart additional covid metrics besides cases - 10

# Core files 
* `usa_map.js` - d3js code
* `index.html` - html page
* `styles.css` - css styles
* `geojson-counties-fips.json` - geojson map county data
* `fall-2021_cs-519_project-paper_sjv_report.pdf` - report

## References
* Choropleth U.S. county map: http://bl.ocks.org/jadiehm/af4a00140c213dfbc4e6
* geoAlbersUsa: https://bl.ocks.org/rveciana/ee2119324e835e1bad42d0e4c1b9ab0d
* Date slider: https://bl.ocks.org/officeofjane/47d2b0bfeecfcb41d2212d06d095c763
* USA state map: http://bl.ocks.org/michellechandra/0b2ce4923dc9b5809922
* Sam's Personal COVID-19 Dashboard: https://github.com/parmsam/covid-19-dashboard
