# Anthro GHG, Aerosols, and other species 
This code script quantifies historical (1750-2022) emissions, ERF, and temperture (del_T) contributions by sector of the the following:
* GHG: 
Carbon Dioxide (CO2),
Methane (CH4),
Nitrous Oxide (N2O),
Fluorinated Gases (PFCs, HFCs, HCFCs)
* Air pollutants:
NOx,
VOC’s,
CO,
SO2,
NH3,
* Aerosols:
Organic carbon,
Black Carbon

Emissions, ERF, and del_T contributions are allocated to the following sectors:
* Power
* fossil fuel production and distribution (ffpd)
* Industry
* Transportation
* Buildings
* Waste
* Agriculture

Initial Emissions Data Gathered from [EDGAR - Emissions Database for Global Atmospheric Research](https://edgar.jrc.ec.europa.eu/emissions_data_and_maps), specifically EDGAR v8.0
https://edgar.jrc.ec.europa.eu/dataset_ghg70 and EDGAR v6.1 https://edgar.jrc.ec.europa.eu/dataset_ap61#sources

Final Emissions Data for major GHGs and air pollutants from [Community Emissions Data Systems (CEDS)](https://github.com/JGCRI/CEDS/blob/master/README.md) version v_2024_04_01. Emissions pre-1970 are from v_2021_04_21 fuel data with sector partitioning from latest version 1970 allocation.

HC (CFC, HCFC) emissions data from [WMO Ozone 2022 Report](https://csl.noaa.gov/assessments/ozone/2022/), CFC and HCFC emission data from [EDGAR - Emissions Database for Global Atmospheric Research](https://edgar.jrc.ec.europa.eu/emissions_data_and_maps), specifically EDGAR v8.0. HC emissions sectoral fractions calculated using UNFCCC AFEAS database and [UNEP Ozone Depleting Substance databases](https://ozone.unep.org/countries/data-table). See HC Section for specific details.
