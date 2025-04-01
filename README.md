# P-Wave Arrival-Time Tomography of the Middle East using ISC-EHB and Waveform Data

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.15115350.svg)](https://doi.org/10.5281/zenodo.15115350)

## Data

P-wave arrival-time data is available is available at [International
Seismological Centre (ISC)-EHB
474Bulletin](https://www.isc.ac.uk/isc-ehb/). The waveform data used
in this study is not open-access which is maintained and provided by
the [Saudi Geological Survey](https://sgs.gov.sa/en).


## Travel time Inversion Software

The travel time inversion software BD-soft is available at

https://www.geoazur.fr/GLOBALSEIS/Soft.html


## Horizontal Model Cross-sections

Horizontal model cross-sections are provided as individual files for
each depth (11-1400 km). Files contain three columns: longitude,
latitude, and the model perturbation.

- `horizontal_xsections/isc_and_saobs_m1_ytry02`: inverted model using ISC-EHB and Saudi Arabia waveform data.
- `horizontal_xsections/isc_only_m1_ytry02`: inverted model using only ISC-EHB data.


## Model files

Model data in Princeton Standard Grid format are stored under the
`models` folder. To generate horizontal cross-sections `plotglobal`,
and for vertical cross-sections `slicedcubedsphere` scripts from the
[BD-Soft](https://www.geoazur.fr/GLOBALSEIS/Soft.html) can be used.

- `models/solx.02.dlnVp.invSAobsM1stder0p65regdataer_ytry0p02`: inverted model using ISC-EHB and Saudi Arabia waveform data.
- `models/solx.02.dlnVp.iscm1ytry0p02`: inverted model using only ISC-EHB data.

