---
layout: default
title: ICES-MH Distributional Impacts of Climate Change and Adaptation Dataset
---

# ACCREU / ICES-MH Distributional Impacts of Climate Change and Adaptation Dataset

**Public Accelerator folder:** This file provides the documentation and persistent access point for the dataset. [ACCREU ICES-MH Data Access](https://iiasa.github.io/ACCREU_datasets/ices/ices-mh-file_access.html)

**Permanent dataset record:** [Zenodo – ICES-MH Distributional Impacts of Climate Change and Adaptation Dataset](https://doi.org/10.5281/zenodo.23771290).

## Summary

This dataset presents the distributional implications of climate change and adaptation in the European Union, assessed using the ICES-MH (ICES-MultiHousehold) computable general equilibrium model developed at CMCC.

The analysis considers climate change impacts across multiple sectors, including sea-level rise, riverine floods, agriculture, forestry, labour productivity and supply, energy demand, health, biodiversity, and wildfires.

The dataset reports changes in household income per adult equivalent, expressed as percentage changes relative to a no-climate-change scenario. Results are provided at the country level for household income quintiles.

## Model and Methodology

The analysis uses the ICES-MH model, a multi-household extension of the ICES general equilibrium modelling framework.

Further information on the model is available at [ICES Model](https://www.icesmodel.org).

## Citation

Campagnolo, L. (2026). ICES-MH Distributional Impacts of Climate Change and Adaptation Dataset [Dataset]. Zenodo. [10.5281/zenodo.23771290](https://doi.org/10.5281/zenodo.23771290).

When using these data in publications, reports, or other research outputs, please cite the Zenodo dataset record provided above. The GitHub repository and associated download interface are intended to facilitate access to the data and should not replace the formal dataset citation.

## Data Access and Repository Contents

The dataset is formally published on Zenodo, which provides a permanent DOI, citation information, and dataset metadata. 
This GitHub repository hosts the HTML download interface, which provides a browsable representation of the dataset's folder structure and direct links to the individual data files.

- **Zenodo dataset record (permanent DOI):** [Zenodo](https://doi.org/10.5281/zenodo.23771290)
- **Browse and download the data:** [ACCREU ICES-MH Data Access](https://iiasa.github.io/ACCREU_datasets/ices/ices-mh-file-access)

The folder structure below describes the organization of the underlying data on the IIASA Accelerator.

## Data Description

| Variable | Description and unit |
|------------------------------------|------------------------------------|
| *Household income per adult equivalent* | Percentage change relative to the no-climate-change scenario, expressed in real terms using country-specific CPI |

## Scenario Coverage

- **Socioeconomic scenario:** SSP2
- **Climate scenarios:** RCP4.5 and RCP7.0
- **Time horizon:** 2020–2070
- **Temporal resolution:** Five-year intervals
- **Geographic coverage:** European Union
- **Spatial and distributional resolution:** Country level, by income quintile
  
## Folder Structure (on Accelerator)

```text
/CMCC_ICES/
├── ACCREU_ICES_MH_D4.2_Distributional_results.xlsx    # ICES-MH distributional impact results
└── ACCREU_ICES_MH_D4.2_MetaData-CMCC.csv              # Dataset metadata and documentation
```

The `CMCC_ICES/` directory contains one Excel file presenting ICES-MH distributional impacts and adaptation scenarios and one metadata file in csv format. 

## Data Access and Availability

The dataset is made available through three complementary resources:

- **Zenodo:** Provides the permanent dataset record, DOI, citation information, and metadata.
- **GitHub:** Hosts the HTML download interface (`ices-mh-file_access.html`) providing links to the individual data files.
- **ACCREU Accelerator:** Hosts the underlying outputs.

**Permanent dataset record:** [Zenodo – ICES-MH Distributional Impacts of Climate Change and Adaptation Dataset](https://doi.org/10.5281/zenodo.23771290)

## Contact ##

For questions regarding the dataset, please contact:
	
Lorenza Campagnolo (lorenza.campagnolo (at) cmcc.it)

## Funding Acknowledgement ## 

This dataset was produced as part of the ACCREU (Assessing Climate Change Risk in Europe) project, 
funded by the European Union's Horizon Europe research and innovation programme under Grant Agreement No. 101081358. 

The distributional Impacts simulations were conducted using
the ICES model, developed at the Euro-Mediterranean Center on Climate Change (CMCC).
The underlying data files are hosted on the IIASA Accelerator platform.

