# Heterogeneity index: supporting material

Supporting code and reproducibility material for the paper **“Beyond Global Importance: A Heterogeneity Index for Sensitivity Analysis.”**

The notebooks reproduce the numerical experiments and figures reported in the paper using the `simdec` implementation of the heterogeneity index.

## Contents

- **`01_heterogeneity_vs_global_sensitivity.ipynb`**  
  Comparison of conventional global sensitivity indices \(S_i\) with input-conditioned heterogeneity indices \(H_{X_i}\).

- **`02_raw_vs_normilized.ipynb`**  
  Controlled binary and continuous models used to illustrate the behavior of the heterogeneity index.

- **`03_number_of_regions.ipynb`**  
  Sensitivity of the heterogeneity estimates to the number of regions.

- **`04_sample_size_stability.ipynb`**  
  Monte Carlo and quasi-Monte Carlo experiments examining estimation stability across sample sizes.

- **`05_case_wood_pallet.ipynb`**  
  Wooden-pallet carbon-footprint case study, including global sensitivity and regional heterogeneity analysis.

- **`06_case_flood.ipynb`**  
  Flood-risk case study, including output- and input-conditioned heterogeneity and the custom Flood/OK regime analysis.

- **`07_case_steel_reliability.ipynb`**  
  Steel-structure reliability case study using the published benchmark dataset.

## Software

The heterogeneity index is implemented in the open-source Python package:

- **SimDec:** https://github.com/Simulation-Decomposition/simdec-python

## Data

The practical-case notebooks either generate the required simulation data internally or retrieve the original published datasets from their source repositories. Dataset versions are pinned where appropriate to support reproducibility.

## License

The code and notebooks in this repository are released under the **MIT License**. See [`LICENSE`](LICENSE) for details.

External datasets used in the case studies remain subject to the licenses and terms of their original sources.
