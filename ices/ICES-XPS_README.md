# ACCREU / ICES-XPS Macro-fiscal Implications of Climate Change and Adaptation Dataset

**Public Accelerator folder:** This file provides the documentation and persistent access point for the dataset. The underlying data are hosted on the IIASA Accelerator and can be accessed here: [ACCREU ICES-XPS Data Access](https://iiasa.github.io/ACCREU_datasets/ices/ices-xps-file_access.html).

**Permanent dataset record:** [Zenodo – ICES-XPS Macro-fiscal Implications of Climate Change and Adaptation Dataset](https://doi.org/10.5281/zenodo.23769839).

## Summary

This dataset presents the macroeconomic and fiscal implications of climate change and adaptation in Europe, assessed with ICES-XPS (ICES-eXtended Public Sector), a multi-regional, multi-sectoral, recursive-dynamic computable general equilibrium (CGE) model of the global economy developed at the Euro-Mediterranean Center on Climate Change (CMCC).

The analysis considers seven climate impacts: sea-level rise, riverine floods, agriculture, pollination, wildfires, heat-related health and heat-related labor productivity and supply. Adaptation includes planned public adaptation, with implications for public budgets and investment, and private adaptation, such as energy use for cooling and heating. Results are reported for three adaptation levels.

The dataset provides estimates of changes in gross domestic product (GDP), government income, government investment and public debt. Results are expressed as percentage changes relative to the no climate change scenario (NO_CC). For a detailed description of the model extensions, refer to the [Technical documentation of ICES-XPS model extensions within the ACCREU project](https://iiasa.github.io/ACCREU_datasets/ices/ICES-XPS_Database_Update_and_Modeling_of_Climate_Impact_and_Adaptation_Channels_for_the_ACCREU_Project.pdf).

## Model and Methodology

ICES-XPS extends the ICES CGE model by splitting the regional household into a private household and a government, and by modeling public borrowing, debt and interest payments. It is based on the GTAP 11 database (base year 2017), enriched with government and household flows, and covers 45 regions, including the 27 EU Member States and the United Kingdom individually.

Climate impacts enter the model as shocks to factor stocks, factor productivity, public expenditure and energy-use efficiency; adaptation acts on the government budget through higher public expenditure and public investment, which affect borrowing, debt and interest payments. The model is solved in five-year steps up to 2070.

For a description of the model and of the extensions developed within ACCREU, refer to the technical documentation: *ICES-XPS: Database Update and Modeling of Climate Impact and Adaptation Channels for the ACCREU Project*.

## Citation

Campagnolo, L. (2026). *ACCREU ICES-XPS Macro-fiscal Implications of Climate Change and Adaptation Dataset* [Dataset]. Zenodo. [10.5281/zenodo.23769839](https://doi.org/10.5281/zenodo.23769839).

When using these data in publications, reports, or other research outputs, please cite the Zenodo dataset record above. The Accelerator folder and any download interface are intended to facilitate access to the data and should not replace the formal dataset citation.

## Scenario Coverage

* **Socioeconomic scenario:** SSP2
* **Climate scenario:** RCP7.0
* **Adaptation levels:** low, ref, high
* **Time horizon:** 2020–2070
* **Temporal resolution:** five-year intervals
* **Geographic coverage:** global
* **Spatial resolution (Europe):** country level (EU27 and UK)
* **Spatial resolution (rest of world):** 17 countries and macro-regions

## Variables and Units

| Variable | Description |
|-|-|
| *GDP* | Real gross domestic product |
| *GOVINC* | Real government income |
| *INVGOV* | Real government investment |
| *DEBT* | Real public debt |

**Units:** all variables are expressed as **% change with respect to the no climate change scenario** (NO_CC). Real values are obtained by deflating the nominal values of each region with its GDP price index (base year 2020 = 1).

Results are reported for the following dimensions:

| Dimension | Content |
|-|-|
| *Region* | 28 individual countries (EU27 and UK), 4 macro-regions (Western, Northern, Central-Eastern and Southern Europe), the EU27+UK aggregate, and 17 non-EU regions of the model (AUNZ, China, JPNKOR, REastAsia, Indonesia, RSouthAsia, India, Canada, USA, Mexico, Brazil, LACA, REurope, FSU, MENA, SAfrica, SSA). Macro-regions and EU27+UK are sums of the real values of their countries. |
| *Impact* | AGRI (agriculture), FLOOD (riverine floods), HEALTH (heat-related health), LAB (heat-related labor productivity), SLR (sea-level rise), BIOD (pollination), FIRE (wildfires), and ALL (all impacts combined). |
| *RCP* | RCP7 (RCP7.0). |
| *Adapt_level* | low, ref, high adaptation. |
| *Channel* | all (impacts and adaptation), imp (impacts only), ada (adaptation only). |
| *Years* | 2020–2070, in 5-year steps. |

Notes:

* **Impact "ALL"** is the baseline plus the sum, across impacts, of the deviations of each single-impact run from the baseline. Interactions between impacts are not modeled. FIRE and BIOD are available for one adaptation level only and without an impacts/adaptation split. Their deviation is used at every adaptation level in the "all" and "imp" channels and set to zero in the "ada" channel.
* **NO_CC** is the baseline without climate impacts or adaptation.

## Data Format

The dataset is provided as an Excel file (xlsx) and a metadata file (csv). The results file contains one sheet (`Fiscal_results`) with one row per variable, region, impact, RCP, adaptation level and channel, and one column per year. The first columns identify the model (`ICES-XPS`), partner (`CMCC`), model type (`CGE model`), variable, unit (`% ch`) and unit description.

## Data Format

The dataset is provided in csv format.

## File Structure

```text
/D4_3_Macro-fiscal_ICES-XPS/
├── ACCREU_ICES_XPS_D4.3_Macro-fiscal_results.xlsx   # ICES-XPS macro-fiscal results
└── ACCREU_ICES_XPS_D4.3_MetaData-CMCC.csv           # Dataset metadata and documentation
```


## Authors and Contact

* **Author/contact:** Lorenza Campagnolo, lorenza.campagnolo(at)cmcc.it
* **Institution:** Euro-Mediterranean Center on Climate Change (CMCC)
* **Dataset version:** 1
* **Metadata date:** 22 October 2026

## Data Access and Citation

* **Dataset access:** [ACCREU ICES-XPS Data Access](https://iiasa.github.io/ACCREU_datasets/ices/ices-xps-file_access.html).
* **Permanent dataset record:** [Zenodo](https://doi.org/10.5281/zenodo.23769839) (permanent record, DOI, citation information and metadata).

## Acknowledgements

This dataset was developed within the ACCREU (Assessing Climate Change Risks in Europe) project, funded by the European Union's Horizon Europe research and innovation programme under Grant Agreement No. 101081358.

The macro-fiscal simulations were conducted using the ICES-XPS model, developed at CMCC. The underlying data files are hosted on the IIASA Accelerator platform.
