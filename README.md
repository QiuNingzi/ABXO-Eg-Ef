# ABXO-Eg-Ef
This folder contains the processed data and codes needed to reproduce the findings of the paper "Formation Energy and Bandgap Predictions of Perovskite Materials Using a Gradient Boosting Regression Algorithm."

## Data
### ABOX_raw_data.csv
```
The raw data downloaded from the Materials Project database
```
### ABOX_raw_features_eb.csv
```
The processed data required to reproduce this work
```
## Scripts
### ABOX_data_download.ipynb
```
How to download raw DFT data with the API provided by the Materials Project database
```
### GBR_Ef_bandgap_with_Ehull_eb.ipynb
```
- Formation energy and band gap prediction with Ehull
- Feature importance ranked by SHAP method
- Results before and after parameters optimization
```
### GBR_Ef_bandgap_without_Ehull_eb.ipynb
```
- Formation energy prediction without Ehull
- The process of hyper parameters optimization
- Band gap prediction without Ehull
```
### GBR_bandgap_with_Ehull_Ef_eb.ipynb
```
- Bandgap prediction with Ehull&Ef
- Results before and after parameters optimization
- Feature importance ranked by SHAP method
```
