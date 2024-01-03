# WetNet
WetNet: An Ensemble SAR/Optical Deep model for Wetland Mapping

This repository shares the model developed for mapping complex wetlands. The input data consists of multi-temporal images of dual-polarized Sentinel-1 SAR and multi-spectral Sentinel-2 imagery. The architecture of the model is an ensemble of three parallel deep modules, with each module capturing different temporal or spatial features from the inputs. The outputs of these modules are combined to estimate the label corresponding to the wetland class.

<p align="center">
 <img src="WetNet.jpg" width=80%>
</p>

## Paper
Link to the paper: 

[IEEE](https://ieeexplore.ieee.org/abstract/document/9576524/) 

[ResearchGate](https://www.researchgate.net/publication/355335892_WetNet_A_Spatial-Temporal_Ensemble_Deep_Learning_Model_for_Wetland_Classification_Using_Sentinel-1_and_Sentinel-2?_tp=eyJjb250ZXh0Ijp7ImZpcnN0UGFnZSI6InByb2ZpbGUiLCJwYWdlIjoicHJvZmlsZSIsInBvc2l0aW9uIjoicGFnZUNvbnRlbnQifX0)

## Citation
If you find this work useful, please cite us in your work:
```
@article{WetNet,
    title = {WetNet: A spatial–temporal ensemble deep learning model for wetland classification using Sentinel-1 and Sentinel-2},
    author = {Hosseiny B., Mahdianpari M., Brisco B., Mohammadimanesh F., Salehi B.},
    year = {2021},
    journal = {IEEE transactions on geoscience and remote sensing},
    pages = {1-14},
    url = {https://ieeexplore.ieee.org/abstract/document/9576524/},
    doi = {10.1109/TGRS.2021.3113856}
}
```
