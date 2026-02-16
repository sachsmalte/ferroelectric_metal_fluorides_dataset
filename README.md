# ferroelectric_metal_fluorides_dataset
This repository contains the DFT raw data and analysis for the publication "A First-Principles Analysis of Metal Fluorides with Polar Crystal Structures as Candidates for New Ferroelectric Materials".

## Methods
The DFT calculations have been performed with Crystal23 using the hybrid functional PBE0 and TZVP basis sets. 

## Contents
- The directory Database contains the DFT data (currently for testing only for the compound BaZnF4). Please extract the compressed data_set.tar.xz file into this directory for all data.
- The compounds.csv contains crystallographic information of all investigated compounds together with their location within the database.
- The jupyter-notebook data_selection.ipynb gives virtuall access to the database by printing out cif-files and plotting RDF-analyses as well as IR and Raman spectra.
- The directory SVM-Modell contains the test and training data of the SVM model discussed in the publication as well as a jupyter-notebook with the used SVM routine.

---

## License
This repository is licensed under the  
**Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)**.  

For details, see: [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/)  

---

## Citation
If you use these data, please cite as follows:

Malte Sachs, Antti J. Kartunnen, Florian Kraus, A First-Principles Analysis of Metal Fluorides with Polar Crystal Structures as Candidates for New Ferroelectric Materials, Mater Chem. **2026**, *38*, *3*, 1204–1219. https://doi.org/10.1021/acs.chemmater.5c02528


