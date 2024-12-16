This directory contains the script to reproduce the analysis and all figures:

* **1.calculate_Causal_Shapley.R**: Trains XGB models and calculates Causal Shapley values.

* **2.figures**: Scripts to reproduce all figures in the main text.

* **3.supplementary**: Scripts to reproduce all figures in the Supplementary Material.

-   **plot_Fig_1.R**
-   **plot_map_variables.R**: plots maps of the main variables used in this study
-   **plot_summary_SHAP.R**: loads SHAP results and plots nice summary plots SHAP (bee-swarm and dependence plots)
-   **plot_map_SHAP.R**: plots map of SHAP values of each feature/predictor
-   **plot_crosscorr_scatters.R**: plot the cross-correlation between variables used in the XGB models (supplementary figure)
-   The other figures presented in the supplementary materials were plotted using the scripts above with other settings and different data (see for instance plot_summary_SHAP.R)
