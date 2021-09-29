# Using the Companies House API for research into Charities
## Overview
In my research I make extensive use of the [Companies House API](https://developer.company-information.service.gov.uk/) in order to understand the characteristics of charities that are also registered as companies, in either England & Wales or Scotland. This repository collects together my repositories for using the Companies House API for research into charities. These form current research projects, and not all of these repositories are currently public. Please contact me if you have any queries about repositories marked as private. I am also keen to talk to others using Companies House data in order to study charities.

## Charities as companies
A significant number of larger UK charities are constituted as companies, usually "limited by guarantee". Where this is the case, the charities will be registered with both a charity regulator and Companies House. Companies are identified by a company number. In England & Wales the Charity Commission E&W records this company number. In Scotland, the company number is not made available by the Scottish Charity Regulator, and so we have had to build a list of Scottish charity company numbers using probabilistic matching.   

The Companies House API can be queried to extract a range of company details, either through searching by keyword or by supplying a company number. I am very grateful to [James Gardiner](https://github.com/JamesGardiner) for his Python package [chwrapper](https://github.com/JamesGardiner/chwrapper) which makes accessing the Companies House API very straightforward.

## List of repositories
I have organised my repositories broadly by topic. These include a mixture of projects to gather data, as well as projects to analyse the data.
- Charity Company Numbers
- Company profiles
- Insolvency data
- Trustee/Director data
- Filing history data

### Charity Company Numbers
All the data processing below hinges on there being a list of company numbers associated with the correct charity. This repository documents the process of producing a list of validated company numbers for charities in the UK.
- https://github.com/a1asdair/charitycompanynumbers

### Company Profiles
- https://github.com/a1asdair/chcompanyprofiles

### Insolvency
- https://github.com/a1asdair/charityinsolvencies

### Trustee/Director data
- https://github.com/a1asdair/scottishcharityboardscovid
- https://github.com/a1asdair/covid-boardrecruitment
- https://github.com/a1asdair/CompaniesHouse
- https://github.com/a1asdair/companieshouseapi

### Filing History data
Work in progress

### Repositories belonging to others
 - https://github.com/JamesGardiner/chwrapper
 - https://github.com/clairestuart1/CompaniesHouse

