![SVO](svologo.png)
# SVO Notebooks

This repository is intended to provide examples of the use of different Spanish Virtual Observatory services. Currently there are examples for the next services.

## Carlos Rodrigo Filter Profile Service Notebooks: 

The service provides the transmission curve, algebraic and calibration
properties for thousands of astronomical filters, and it is designed to be compliant
to the IVOA Photometry Data Model.

Detailed service information can be found at <http://svo2.cab.inta-csic.es/theory/fps/index.php?mode=voservice>.

Notebooks:
- General usage: [filter_profile_service.ipynb](filter_profile_service/filter_profile_service.ipynb)


## SVO Theory Server Notebooks

This project provides programmatic access to the [SVO Theory Server](http://svo2.cab.inta-csic.es/theory/newov2/index.php), which hosts 70 collections of theoretical stellar spectra and observational templates (approximately 285,000 spectra and 668 GB of data).

| Notebook | Description |
|------|-------------|
| [stellar_theoretical_espectra.ipynb](theory/stellar_theoretical_espectra.ipynb) | Theoretical spectra access: discovery, download and visualization |
| [mag2flux.ipynb](flux_to_magnitude/mag2flux.ipynb) | Photometric magnitudes to fluxes: batch conversion, empty-value handling and CSV or VOTable output |
| [colors.ipynb](color_calculations/colors.ipynb) | Reproduces the color computation based on theoretical models, physical parameter ranges, and selected filters |

---