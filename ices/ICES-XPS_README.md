# ACCREU / ICES-XPS Macro-fiscal Implications of Climate Change and Adaptation Dataset

**Public Accelerator folder:** This file provides the documentation and persistent access point for the dataset. The underlying data are hosted externally and can be accessed here: [ACCREU ICES-XPS Data Access](https://iiasa.github.io/ACCREU_datasets/ices/ices-xps-file_access.html).

**Permanent dataset record:** [Zenodo – ICES-XPS Macro-fiscal Implications of Climate Change and Adaptation Dataset](https://doi.org/10.5281/zenodo.23769839).

## Summary

This dataset presents the macroeconomic and fiscal implications of climate change and adaptation, assessed using the ICES-XPS (ICES-eXtended Public Sector) computable general equilibrium model developed at the Euro-Mediterranean Center on Climate Change (CMCC).

The analysis considers climate change impacts across multiple sectors, including sea-level rise, riverine floods, agriculture, forestry, labour productivity and supply, energy demand, health, biodiversity, and wildfires.

The dataset provides estimates of changes in key macroeconomic and public finance indicators, including gross domestic product (GDP), government income, government investment, and public debt, alongside sector-specific variables describing the economic effects of climate change.

Results are expressed as percentage changes relative to a baseline scenario.

## Model and Methodology

The analysis uses ICES-XPS (ICES-eXtended Public Sector), an extension of the ICES computable general equilibrium (CGE) modelling framework designed to assess the macroeconomic and public finance implications of climate change and adaptation.

The model provides an integrated representation of economic sectors and public finances, allowing the assessment of how climate-related impacts propagate through the economy and affect government revenues, investment, and debt.

Further information on the model is available in the [ICES-XPS model documentation](https://www.icesmodel.org/public-sector/).

**Citation:**

Campagnolo, L. (2026). *ACCREU ICES-XPS Macro-fiscal Implications of Climate Change and Adaptation Dataset* [Dataset]. Zenodo. [10.5281/zenodo.23769839](https://doi.org/10.5281/zenodo.23769839).

## Scenario Coverage

- **Socioeconomic scenario:** SSP2
- **Climate scenario:** RCP7.0
- **Time horizon:** 2020–2070
- **Temporal resolution:** Five-year intervals
- **Geographic coverage:** Global
- **Spatial resolution (Europe):** Country level
- **Spatial resolution (rest of world):** Countries and macro-regions

## Variables and Units

The dataset includes the following macroeconomic, fiscal, and sector-specific variables.

### Macroeconomic and Fiscal Indicators

| Variable | Description |
|---|---|
| GDP | Real gross domestic product |
| GOVINC | Real government income |
| INVGOV | Real government investment |
| DEBT | Real public debt |

### Sectoral and Climate Impact Indicators

| Variable | Description |
|---|---|
| Labour_productivity-All_sectors | Labour productivity across all sectors |
| Land_stock | Land stock |
| Capital_stock | Total capital stock |
| Capital_stock-Residential | Residential capital stock |
| Capital_stock-industrial | Industrial capital stock |
| Capital_stock-Services | Services capital stock |
| Crop_yield | Crop yields |
| Livestock_Production | Livestock production |
| Forest_Yield | Forest yields |
| Labour_productivity_(high_exposed_sectors) | Labour productivity in highly exposed sectors |
| Labour_productivity_(low_exposed_sectors) | Labour productivity in less exposed sectors |
| Labour_stock | Labour supply |
| Electr._demand_from_agricultural_sector | Electricity demand from agriculture |
| Electr._demand_from_industrial_sector | Electricity demand from industry |
| Electr._demand_from_service_sector | Electricity demand from services |
| Fossil_fuel_demand_from_service_sector | Fossil fuel demand from services |
| Fossil_fuel_demand_from_households | Household fossil fuel demand |
| Productivity_of_renewables | Renewable energy productivity |

**Units:** All variables are expressed as percentage changes relative to the baseline scenario.

## Data Format

The dataset is provided in csv format.

## File Structure

```text
/CMCC_ICES/
├── ACCREU_ICES_XPS_D4.3_results.csv       # ICES-XPS macro-fiscal results
└── ACCREU_ICES_XPS_D4.3_MetaData-CMCC.csv  # Dataset metadata and documentation
```

## Authors and Contact

- **Author/contact:** Lorenza Campagnolo
- **Institution:** Euro-Mediterranean Center on Climate Change (CMCC)
- **Dataset version:** 1
- **Metadata date:** 22 October 2026

## Data Access and Citation

**Dataset access:** [ACCREU ICES-XPS Data Access](https://iiasa.github.io/ACCREU_datasets/ices/ices-xps-file_access.html)

**Permanent dataset record:** [Zenodo](https://doi.org/10.5281/zenodo.23769839)

## Acknowledgements

This dataset was developed within the ACCREU (Assessing Climate Change Risks in Europe) project, funded by the European Union's Horizon Europe research and innovation programme.
