# <ACCREU / CWatM RCP4.5 Hydrological Data – Daily and Monthly Outputs >

**Public Accelerator folder:** This Zenodo record provides the documentation and persistent access point for the dataset. Due to the size of the underlying files, the data are hosted externally and can be accessed through the download links provided in the accompanying HTML file (file_access.html).

## Summary
CWatM is a spatially distributed rainfall-runoff and channel routing water resources model (Burek et al., 2020). 
It is process-based and quantifies water availability, human water withdrawals across sectors (industry, domestic, agriculture), 
and the effects of water infrastructure, including reservoirs, groundwater pumping, and irrigation canals. 
CWatM is designed at the grid level, with two native versions at 0.5◦ and 0.0833° resolutions at global scales 
(with sub-grid resolution accounting for topography and land cover). It operates at daily time steps (with sub-daily time stepping for soil and river routing).

The daily and monthly simualtions provide runoff and river flow data used be other impact models participating in the ACCREU project to assess climate change impact 

## Citation
- Burek, P., Guillaumot, L., Fridman, D., & Smilovic, M. (2026). CWatM RCP4.5 Hydrological Data – Daily and Monthly Outputs [Data set]. Zenodo. https://doi.org/10.5281/zenodo.23581419
- Burek, P., Satoh, Y., Kahil, T., Tang, T., Greve, P., Smilovic, M., Guillaumot, L., Zhao, F., and Wada, Y et al. Development of the Community Water Model (CWatM v1.04) - a high-resolution hydrological model for global and regional assessment of integrated water resources management. Geosci. Model Dev,13,3267–3298,2020 

## License
- **Model Version:** Model version 1.06 27/04/21 
- **Model Output License:** CC0 
- **Model Homepage:** https://cwatm.iiasa.ac.at/ 
- **Model License:** GNU General Public License v3.0 


## Repository Contents (Metadata only)
This readme file provides the documentation for the dataset. Due to the size of the underlying files, the data are hosted externally and can be accessed through the download links: .
## Folder Structure (on Accelerator)
```text
/cwatm_rcp245/
├─ README.md                  # optional readme in the data folder
├─ /daily/                    # daily simulation results (qtot)
│  ├─ GFDL-ESM4/              # results for the GFDL-ESM4 global climate model
│  	└─ future/                # results for the future (2015-2100)
│  ├─ IPSL-CM6A-LR/           # results for the IPSL-CM6A-LR global climate model
│  	└─ future/                # results for the future (2015-2100)
│  ├─ MPI-ESM1-2-HR/          # results for the MPI-ESM1-2-HR global climate model
│  	└─ future/                # results for the future (2015-2100)
│  ├─ MRI-ESM2-0/             # results for the MRI-ESM2-0 global climate model
│  	└─ future/                # results for the future (2015-2100)
│  ├─ UKESM1-0-LL/            # results for the UKESM1-0-LL global climate model
│  	└─ future/                # results for the future (2015-2100)
├─ /monthly/                  # monthly simulation results (qtot, dis)
│  ├─ GFDL-ESM4/              # results for the GFDL-ESM4 global climate model
│  	└─ future/                # results for the future (2015-2100)
│  ├─ IPSL-CM6A-LR/           # results for the IPSL-CM6A-LR global climate model
│  	└─ future/                # results for the future (2015-2100)
│  ├─ MPI-ESM1-2-HR/          # results for the MPI-ESM1-2-HR global climate model
│  	└─ future/                # results for the future (2015-2100)
│  ├─ MRI-ESM2-0/             # results for the MRI-ESM2-0 global climate model
│  	└─ future/                # results for the future (2015-2100)
│  ├─ UKESM1-0-LL/            # results for the UKESM1-0-LL global climate model
│  	└─ future/                # results for the future (2015-2100)
