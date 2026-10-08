# Foundational Basis of Resource Physical Value

Supporting data and code for the review article:

> Freboeuf, L., Sonnemann, G., Magdalena, R., Rechberger, H., & Beylot, A. *Resource Assessment methods in Industrial Ecology and Process Engineering: a critical review towards improved consideration in LCA.* (prepared for submission to the Journal of Industrial Ecology)

This repository corresponds to **Online Resource 4** of the article. It contains the Jupyter notebooks underlying the critical analysis of Resource Assessment (RA) metrics — chemical exergy, concentration energy, and statistical entropy — all rooted in the Gibbs free energy of mixing, together with the figures produced from them.

## Repository structure

| File | Content |
|---|---|
| `3_Results_Fig-4-5_chemical-exergy-foundations.ipynb` | Calculation of standard reference species chemical exergy across ten configurations (O2, Si, Al, H2); produces Figs. 4 and 5 |
| `3_Results_Statistica-Entropy-visualisation.ipynb` | Visualisation of statistical entropy applied to resource flow mixtures |
| `4_Discussion_Calculs-CExD.ipynb` | Cumulative Exergy Demand (CExD) calculations discussed in the article |
| `Fig4.*`, `Fig5.*` | Publication figures (EPS, PDF, SVG, TIFF) |

## Data and software availability statement

All data supporting the findings are openly available in this repository. Reference exergies are taken from De Meester et al. (2006) and Szargut et al. (2005); Gibbs free energies of formation are sourced from the original studies, HSC Chemistry 10.8, and FactSage (FactPS database). CExD calculations rely on the ecoinvent database (version 3.12), which is accessible under licence at https://ecoinvent.org and must be obtained separately by the user.

## Citation

Please cite both the article and this repository (Zenodo DOI to be inserted upon archiving). The machine-readable citation metadata is provided in `CITATION.cff`.

## License

The contents of this repository are licensed under the Creative Commons Attribution 4.0 International (CC BY 4.0) license; see `LICENSE`.

## Funding

Louis Freboeuf, Guido Sonnemann and Antoine Beylot acknowledge funding from the French State managed by the National Research Agency under France 2030, reference n°ANR-22-PERE-0003.

## Contact

Louis Freboeuf — louis.freboeuf@u-bordeaux.fr
