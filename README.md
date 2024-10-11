[![Documentation Status](https://readthedocs.org/projects/osemosys-kenya-psm/badge/?version=latest)](https://osemosys-kenya-psm.readthedocs.io/en/latest/?badge=latest)

# OSeMOSYS Kenya Power System Model

This repository houses the OSeMOSYS Kenya Power System Model (PSM), developed within the Climate Compatible Growth (CCG) Project. The model describes Kenya's power sector at a single power plant level and uses OSeMOSYS' latest storage implementation. Version 2 introduces an improved representation of solar and wind resources based on Model Supply Regions<sup>1</sup>.

### Versions

| Version | Date    | DOI                                                                                                         | Description                                                                                   |
|---------|---------|-------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------|
| 1.0.0   | 09/2023 | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.11111018.svg)](https://doi.org/10.5281/zenodo.11111018) | First release of the model, LCPDP-CCG collaboration. |
| 2.0.0   | 05/2024 | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.11165893.svg)](https://doi.org/10.5281/zenodo.11165893) | Model Supply Region (MSR) implementation, LCPDP-CCG-WRI collaboration. |

### Citing OSeMOSYS-Kenya PSM 

#### Version 1.0.0
M. Kihara, P. Lubello, A. Millot, M. Akute, J. Kilonzi, M. Kitili, F. Mukuri, B. Kinyanjui, P. Hoseinpoori, A. Hawkes, A. Shivakumar, D. Welsby, S. Pye, Mid- to long-term capacity planning for a reliable power system in Kenya, Energy Strategy Reviews 52 (2024) 101312. https://doi.org/10.1016/j.esr.2024.101312.

BibTeX:

    @article{osemosys_kenya_psm,
      title = {Mid- to long-term capacity planning for a reliable power system in Kenya},
      author = {Mungai Kihara and Pietro Lubello and Ariane Millot and Michelle Akute and Julius Kilonzi and Monicah Kitili and Felister Mukuri and Boniface Kinyanjui and Pooya Hoseinpoori and Adam Hawkes and Abhishek Shivakumar and Dan Welsby and Steve Pye},
      journal = {Energy Strategy Reviews},
      volume = {52},
      pages = {101312},
      year = {2024},
      issn = {2211-467X},
      doi = {https://doi.org/10.1016/j.esr.2024.101312},
      url = {https://www.sciencedirect.com/science/article/pii/S2211467X24000191}
      }

#### Version 2.0.0
A. Millot, P. Lubello, E. M. Tennyson, M. Mutembei, M. Akute, D. Mentis, S. Pye, A. Hawkes, S. Sterl, The map behind the roadmap — Introducing a geospatial energy model for utility-scale solar and wind power buildout in Kenya,
Cell Reports Sustainability 1 (2024) 100222. https://doi.org/10.1016/j.crsus.2024.100222.

BibTeX:

    @article{,
      title = {The map behind the roadmap — Introducing a geospatial energy model for utility-scale solar and wind power buildout in Kenya},
      author = {Ariane Millot and Pietro Lubello and Elizabeth M. Tennyson and Martin Mutembei and Michelle Akute and Dimitris Mentis and Steve Pye and Adam Hawkes and Sebastian Sterl},
      journal = {Cell Reports Sustainability},
      volume = {1},
      pages = {100222},
      year = {2024},
      issn = {},
      doi = {https://doi.org/10.1016/j.crsus.2024.100222},
      url = {https://www.cell.com/cell-reports-sustainability/fulltext/S2949-7906(24)00354-9}
      }


### Acknowledgements
This material has been produced with support from the Climate Compatible Growth (CCG) programme, which brings together leading research organisations and is led out of the STEER centre, Loughborough University. CCG is funded by UK aid from the UK government. However, the views expressed herein do not necessarily reflect the UK government's official policies.

### Licenses
[![License: Apache 2.0](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://github.com/ClimateCompatibleGrowth/osemosys_kenya?tab=Apache-2.0-1-ov-file#readme)

The model files located at ```psm/v1_0_0/...``` and ```psm/v12_0_0/...``` are released under the Apache 2.0 license, and the copyright holders, per each version of the model, are listed in the author's list. The model has been developed starting from the original [OSeMOSYS modelling framework](https://github.com/OSeMOSYS/OSeMOSYS_GNU_MathProg?tab=readme-ov-file)<sup>2</sup>.

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY--4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

The data files located at ```psm/v1_0_0/...``` and ```psm/v12_0_0/...``` are released under the [CC BY 4.0](https://creativecommons.org/licenses/by/4.0) license, and the copyright holders, per each version of the model, are listed in the author's list.

### References
[1] Sterl, Sebastian, et al. "An all-Africa dataset of energy model “supply regions” for solar photovoltaic and wind power." Scientific Data 9.1 (2022): 664.
[2] Howells, Mark, et al. "OSeMOSYS: the open source energy modeling system: an introduction to its ethos, structure and development." Energy Policy 39.10 (2011): 5850-5870. https://doi.org/10.1016/j.enpol.2011.06.033
