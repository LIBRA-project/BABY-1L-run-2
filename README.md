# libra-run-template

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.14532208.svg)](https://doi.org/10.5281/zenodo.14532208)

This is a template repository for experimental runs of LIBRA.

This repository has the data for the run BABY-1L-run-2.

## How to reproduce the results

### In Binder

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/LIBRA-project/BABY-1L-run-2/HEAD)

### Locally

1. Create a conda environment (requires conda):

```
conda env create -f environment.yml
```

2. Run the notebooks with the created environment `baby_1l_run_2`

## Todo list:
- [x] [Link to Zenodo](https://zenodo.org/)
- [x] Change environment name in [`environment.yml`](environment.yml)
- [x] Add general run data to [`data/general.json`](data/general.json)
- [x] Add LSC data to [`data/tritium_detection`](data/tritium_detection)
- [x] Add neutron detection data to [`data/neutron_detection`](data/neutron_detection)
- [x] Add OpenMC model to [`analysis/neutron`](analysis/neutron)
- [x] Add Tritium model to [`analysis/tritium`](analysis/tritium)
- [x] Add the right version tags to [`environment.yml`](environment.yml)
- [x] Add and update information in the README
- [x] Modify [binder](https://mybinder.org/) badge by inserting the repo name
- [x] Update [CI workflows](.github/workflows)
- [x] Make first release on GitHub
- [x] Update Zenodo badge with new DOI
- [x] Link Zenodo record (created automatically) to the [LIBRA-project Zenodo community](https://zenodo.org/communities/libra-project/records)
