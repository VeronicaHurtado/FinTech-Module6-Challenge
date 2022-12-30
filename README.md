# Property Investment analysis tool

## Case study
A Proptech company wants to offer an instant, one-click service for people to buy properties and then rent them.

This is a prototype to trial the new offering in the San Francisco area. The purpose of this tool is to identify properties
in the Real Estate market that are feasible investment options; by using data visualisation tools, aggregation, interactive 
visualisations, and geospatial analysis.

## Data sources
- San Francisco's Neighborhoods coordinates: [neighborhoods_coordinates.csv](Resources/neighborhoods_coordinates.csv)
- San Francisco's Sale Price by sqr foot, Housing Units and Gross Rent for 2010-2016: [sfo_neighborhoods_census_data](Resources/sfo_neighborhoods_census_data.csv)

## Tasks to support the Analysis of the data
* Calculation and plotting of the housing units per year.
* Calculation and plotting of the average prices per square foot.
* Comparison of the average prices by neighborhood.
* Building of an interactive neighborhood map.
* Composition of data story.

## Technical Environment
This tool utilises the following technologies:
- **Pandas** DataFrame: [Documentation](https://pandas.pydata.org/docs/reference/frame.html)
- **hvplot** Bar chart, Line plot, GeoViews:  [Documentation](https://hvplot.holoviz.org/getting_started/hvplot.html)

## Disclaimer
> Please be aware this is an Academic Case Study. There are other considerations when deciding to invest on a property, 
> such as:
> Costs of buying (e.g. Conveyancing fees, Stamp Duty, etc.); 
> Costs of owning the property (e.g. Insurance, Council Rates, Water Rates, Maintenance, etc.);
> and Financing Options (e.g. Will you need a loan? What is your Borrowing Power? What is the amount of the repayments?, etc.).
> 
> For more information visit [Money Smart](https://moneysmart.gov.au/property-investment) and [Investopedia](https://www.investopedia.com/terms/i/investment-property.asp).