# Anthropogenic GHG, Aerosols, and other species (Climate Forcers)

**README**

This code script quantifies estimates of historical (1750-2022) emissions, ERF, and change in GSAT (del_T) contributions by sector of the the following:
* GHG: 
Carbon Dioxide (CO2),
Methane (CH4),
Nitrous Oxide (N2O),
Halogenated Compounds (CFCs, HFCs, HCFCs, etc.)
* Air pollutants:
NOx,
VOC’s,
CO,
SO2,
NH3,
* Aerosols:
Organic carbon,
Black Carbon

Emissions, ERF, and change in GSAT (del_T) contributions are allocated to the following sectors:
* Power
* fossil fuel production and distribution (ffpd)
* Industry
* Transportation
* Buildings
* Waste
* Agriculture

**Code Sources:**

Estimates of individual species ERF and change in GSAT are derived following the code of [IPCC AR6 CH6 Fig.12](https://github.com/IPCC-WG1/Chapter-6_Fig12_22_24) adapted to quantify sectoral contributions, we thank the authors for providing their open-access code. 

**Data Sources:**

Final Emissions Data for major GHGs and air pollutants from [Community Emissions Data Systems (CEDS)](https://github.com/JGCRI/CEDS/blob/master/README.md) version v_2024_04_01. Emissions prior to the year 1970 for CH4 and N2O are from v_2021_04_21 fuel data with sector partitioning from v_2024_04_01 year 1970 allocation.

HC (CFC, HCFC, HFC, etc.; see publication methods Table 2) emissions data from [WMO Ozone 2022 Report](https://csl.noaa.gov/assessments/ozone/2022/),  emission data from [EDGAR - Emissions Database for Global Atmospheric Research](https://edgar.jrc.ec.europa.eu/emissions_data_and_maps), specifically EDGAR v7.0, with other species from [UNEP Ozone Depleting Substance databases](https://ozone.unep.org/countries/data-table). HC emissions sectoral fractions calculated using the EDGAR, UNFCCC AFEAS ([1](https://unfccc.int/files/methods/other_methodological_issues/interactions_with_ozone_layer/application/pdf/cfc1200.pdf) and [2](https://unfccc.int/files/methods/other_methodological_issues/interactions_with_ozone_layer/application/pdf/cfc1100.pdf)) and UNEP ODS databases. See HC Section for specific details.

Final fuel consumption data from [International Energy Agency (IEA)](https://www.iea.org/data-and-statistics/data-product/world-energy-balances) to allocate ffpd sector emissions to other sectors

**Project Data:**
Input data necessary to run the code script is additionally located in this repository. 
