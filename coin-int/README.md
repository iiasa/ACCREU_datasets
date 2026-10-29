# ACCREU / COIN-INT Macroeconomic Impacts and Adaptation Scenarios Dataset

**Public Accelerator folder:** This file provides the documentation and persistent access point for the dataset. Due to the size of the underlying files, the data are hosted externally and can be accessed here: 
[ACCREU COIN-INT Data Access](https://iiasa.github.io/ACCREU_datasets/coin-int/COIN_file_access)

## Summary

COIN-INT2.0 is a multi-regional and multi-sectoral model of the global
economy, which is tailored to the analysis of macroeconomic effects of
climate policy with a European focus. Within ACCREU, the model is
expanded by a set of impact and adaptation modules covering a range of
different climate impacts under three Representative Concentration
Pathways (RCPs) and three different adaptation levels until 2080. For a
detailed description of the model extensions, refer to the [Technical
documentation of COIN-INT model extensions within the ACCREU project](https://iiasa.github.io/ACCREU_datasets/coin-int/ACCREU_COIN_documentation.pdf).


## Citation

-Knittel, N., Lehner, A., Preinfalk, E., Bednar-Friedl B. (2026). COIN-INT2.0 Macroeconomic and Fiscal Effects of Climate Impacts and Adaptation - Results [Data set]. Zenodo. [To Add]

When using these data in publications, reports, or other research outputs, please cite the Zenodo dataset record provided above. The GitHub repository and associated download interface are intended to facilitate access to the data and should not replace the formal dataset citation.


## Data Access and Repository Contents

The dataset is formally published on Zenodo, which provides a permanent DOI, citation information, and dataset metadata. 
This GitHub repository hosts the HTML download interface, which provides a browsable representation of the dataset's folder structure and direct links to the individual data files.

- **Zenodo dataset record (permanent DOI):** ADD
- **Browse and download the data:** [ACCREU COIN-INT Data Access](https://iiasa.github.io/ACCREU_datasets/coin-int/COIN_file_access)

The folder structure below describes the organization of the underlying data on the IIASA Accelerator.

## Data Description

| Variable | Description |
|------------------------------------|------------------------------------|
| *GDP_real* | real GDP |
| *welfare* | total welfare, composed of private and public welfare (Hicksian equivalent vairation with impact-specific adjustments |
| *tax_revenue* | public tax revenue (equivalent to total public expenditure due to budget-neutral assumption |

Results are listed for 3 RCPs (RCP2p6, RCP4p5, RCP7p0), the baseline
without climate impacts nor adaptation (no_impact), and 3 scenarios with
impacts and 3 adaptation levels (low_ada, medium_ada, high_ada), for 25
European regions, in yearly aggregates for the years 2020-2080 in 5-year
steps.

## Folder Structure (on Accelerator)

```text
/D4_3_Fiscal_COIN/
├── ACCREU_COIN-INT_agricultural_impacts.xlsx  # Results for Agricultural Impacts: GLOBIOM+Biodiversity 
├── ACCREU_COIN-INT_all_impacts.xlsx           # Results for all impacts: agricultural, flooding, health, labour, sea level rise 
├── ACCREU_COIN-INT_flooding.xlsx              # Results for Flood Impacts: GLOFRIS
├── ACCREU_COIN-INT_health_impacts.xlsx        # Results for Health/Energy Impacts
├── ACCREU_COIN-INT_labour_impacts.xlsx        # Results for Labour/Energy Impacts
└── ACCREU_COIN-INT_sea_level_rise.xlsx        # Results for Sea Level Rise Impacts
```

The `D4_3_Fiscal_COIN/` directory contains six Excel files presenting COIN-INT macroeconomic impacts and adaptation scenarios. 
The files cover agricultural impacts, flooding, health impacts, labour productivity impacts, and sea-level rise, alongside a combined dataset covering all impacts.


## Data Access and Availability

The dataset is made available through three complementary resources:

- **Zenodo:** Provides the permanent dataset record, DOI, citation information, and metadata.
- **GitHub:** Hosts the HTML download interface (`COIN_file_access.html`) providing links to the individual data files.
- **ACCREU Accelerator:** Hosts the underlying outputs.

**Permanent dataset record:** [Zenodo – COIN-Int Macroeconomic Impacts and Adaptation Scenarios Dataset](ADD)

## Contact ##

For questions regarding the dataset, please contact:
Nina Knittel nina.knittel(a)uni-graz.at

## Funding Acknowledgement ## 

This dataset was produced as part of the ACCREU (Assessing Climate Change Risk in Europe) project, 
funded by the European Union's Horizon Europe research and innovation programme under Grant Agreement No. 101081358. 

The macroeconomic and fiscal simulations were conducted using
the COIN-INT2.0 model, developed at the Wegner Center for Climate and
Global Change, University of Graz. The underlying data files are hosted
on the IIASA Accelerator platform.
