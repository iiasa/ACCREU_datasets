# ACCREU / CWatM RCP4.5 Hydrological Data – Daily and Monthly Outputs 

**Public Accelerator folder:** This file provides the documentation and persistent access point for the dataset. Due to the size of the underlying files, the data are hosted externally and can be accessed here: [ACCREU CWatM Data Access](https://iiasa.github.io/ACCREU_datasets/cwatm/file_access)

## Summary
CWatM is a spatially distributed rainfall-runoff and channel routing water resources model (Burek et al., 2020). 
It is process-based and quantifies water availability, human water withdrawals across sectors (industry, domestic, agriculture), 
and the effects of water infrastructure, including reservoirs, groundwater pumping, and irrigation canals. 
CWatM is designed at the grid level, with two native versions at 0.5◦ and 0.0833° resolutions at global scales 
(with sub-grid resolution accounting for topography and land cover). It operates at daily time steps (with sub-daily time stepping for soil and river routing).

The daily and monthly simualtions provide runoff and river flow data used be other impact models participating in the ACCREU project to assess climate change impact. 

This dataset was produced as part of the ACCREU (Assessing Climate Change Risk in Europe) project and provides daily and monthly hydrological simulation outputs from CWatM under the RCP4.5 climate change scenario for the period 2015–2100. Simulations are available for five global climate models (GFDL-ESM4, IPSL-CM6A-LR, MPI-ESM1-2-HR, MRI-ESM2-0, and UKESM1-0-LL).

The outputs include total runoff (qtot) at daily and monthly temporal resolutions and river discharge (dis) at monthly resolution. These data support climate change impact assessments conducted within the ACCREU project, including analyses of water availability and climate-related risks across sectors. 

The outputs include total runoff (qtot) at daily and monthly temporal resolutions and river discharge (dis) at monthly resolution. 
## Citation
- Burek, P., Guillaumot, L., Fridman, D., & Smilovic, M. (2026). CWatM RCP4.5 Hydrological Data – Daily and Monthly Outputs [Data set]. Zenodo. https://doi.org/10.5281/zenodo.23581419
- Burek, P., Satoh, Y., Kahil, T., Tang, T., Greve, P., Smilovic, M., Guillaumot, L., Zhao, F., and Wada, Y et al. Development of the Community Water Model (CWatM v1.04) - a high-resolution hydrological model for global and regional assessment of integrated water resources management. Geosci. Model Dev,13,3267–3298,2020

When using these data in publications, reports, or other research outputs, please cite the Zenodo dataset record provided above. The GitHub repository and associated download interface are intended to facilitate access to the data and should not replace the formal dataset citation.

## License
- **Model Version:** Model version 1.06 27/04/21 
- **Model Output License:** CC0 
- **Model Homepage:** https://cwatm.iiasa.ac.at/ 
- **Model License:** GNU General Public License v3.0 


## Repository Contents (Metadata and Download Links)

## Data Access and Repository Contents

The dataset is formally published on Zenodo, which provides a permanent DOI, citation information, and dataset metadata. Due to the large size of the underlying files, the hydrological simulation outputs are hosted externally on the IIASA Accelerator.

This GitHub repository hosts the HTML download interface, which provides a browsable representation of the dataset's folder structure and direct links to the individual data files.

- **Zenodo dataset record (permanent DOI):** [https://doi.org/10.5281/zenodo.23581419](https://doi.org/10.5281/zenodo.23581419)
- **Browse and download the data:** [ACCREU CWatM Data Access](https://iiasa.github.io/ACCREU_datasets/cwatm/file_access)

The folder structure below describes the organization of the underlying data on the IIASA Accelerator.

## Data Description

The dataset includes the following hydrological variables:

| Variable | Description | Temporal Resolution |
|---|---|---|
| `qtot` | Total runoff | Daily and monthly |
| `dis` | River discharge | Monthly |

The simulations cover the period 2015–2100 under the RCP4.5 climate scenario, using five global climate models.

The outputs are organized by temporal resolution, climate model, and simulation period, as described in the folder structure below.

## Folder Structure (on Accelerator)

```text
/cwatm_rcp245/
├── README.md                    # Optional readme in the data folder
├── daily/                       # Daily simulation results (qtot)
│   ├── GFDL-ESM4/               # Results for the GFDL-ESM4 global climate model
│   │   └── future/              # Results for the future (2015–2100)
│   ├── IPSL-CM6A-LR/            # Results for the IPSL-CM6A-LR global climate model
│   │   └── future/              # Results for the future (2015–2100)
│   ├── MPI-ESM1-2-HR/           # Results for the MPI-ESM1-2-HR global climate model
│   │   └── future/              # Results for the future (2015–2100)
│   ├── MRI-ESM2-0/              # Results for the MRI-ESM2-0 global climate model
│   │   └── future/              # Results for the future (2015–2100)
│   └── UKESM1-0-LL/             # Results for the UKESM1-0-LL global climate model
│       └── future/              # Results for the future (2015–2100)
└── monthly/                     # Monthly simulation results (qtot, dis)
    ├── GFDL-ESM4/               # Results for the GFDL-ESM4 global climate model
    │   └── future/              # Results for the future (2015–2100)
    ├── IPSL-CM6A-LR/            # Results for the IPSL-CM6A-LR global climate model
    │   └── future/              # Results for the future (2015–2100)
    ├── MPI-ESM1-2-HR/           # Results for the MPI-ESM1-2-HR global climate model
    │   └── future/              # Results for the future (2015–2100)
    ├── MRI-ESM2-0/              # Results for the MRI-ESM2-0 global climate model
    │   └── future/              # Results for the future (2015–2100)
    └── UKESM1-0-LL/             # Results for the UKESM1-0-LL global climate model
        └── future/              # Results for the future (2015–2100)
```

Each climate model directory contains a `future/` subdirectory with simulation outputs for 2015–2100.

## Data Access and Availability

The dataset is made available through three complementary resources:

- **Zenodo:** Provides the permanent dataset record, DOI, citation information, and metadata.
- **GitHub:** Hosts the HTML download interface (`file_access.html`) providing links to the individual data files.
- **ACCREU Accelerator:** Hosts the underlying hydrological simulation outputs, which are too large to store directly on Zenodo or GitHub.

**Permanent dataset record:** [Zenodo – CWatM RCP4.5 Hydrological Data](https://doi.org/10.5281/zenodo.23581419)

Users can access the data files through the download links provided in `file_access.html`.

## Contact ##

For questions regarding the dataset, hydrological simulations, or data access, please contact:
Dor Fridman (fridman@iiasa.ac.at)

## Funding Acknowledgement ## 

This dataset was produced as part of the ACCREU (Assessing Climate Change Risk in Europe) project, funded by the European Union's Horizon Europe research and innovation programme under Grant Agreement No. 101081358. The hydrological simulations were conducted using the Community Water Model (CWatM), developed at the International Institute for Applied Systems Analysis (IIASA). The underlying data files are hosted on the IIASA Accelerator platform.

