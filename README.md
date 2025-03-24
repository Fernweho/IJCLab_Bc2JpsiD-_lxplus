# IJCLab_Bc2JpsiD*_lxplus

This repository contains various Jupyter notebooks and models used for analyzing particle decay data from the cluster. The primary focus is on the preprocessing, modeling, and analysis of data related to B meson decays, using machine learning, likelihood models, and statistical tools.

## Contents

### Notebooks
- **all_decays.ipynb**: A notebook for analyzing all decay channels.
- **analysis_production_checking.ipynb**: This notebook contains checks for the production process of the data.
- **BDT.ipynb**: A notebook focused on using Boosted Decision Trees for classification tasks.
- **Ds_norm_chan.ipynb**: A notebook for the analysis of the `Ds` normalization channel.
- **D_star.ipynb**: A notebook for analyzing the D* meson decays.
- **fakedatasets_new.ipynb**: Generates toys for testing models and analysis.
- **K3pi_preselection.ipynb**: Pre-selection criteria for the `K3pi` decay mode.
- **K3pi_PRESELECTION.ipynb**: Another notebook for the preselection of the `K3pi` decay mode.
- **Kpipi_PRESELECTION.ipynb**: Pre-selection for the `Kpipi` decay mode.
- **mass_sideband.ipynb**: A notebook for analyzing mass sidebands in the data.
- **model_searching.ipynb**: A notebook that searches for optimal models for the data analysis.
- **PRESELECTION.ipynb**: General pre-selection notebook for the data.
- **PRESELECTION_NEW_CORRECT_GREAT.ipynb**: A corrected version of the pre-selection steps for Ds channel.

### Models
- **best_optuna_model.pkl**: The best model found using the Optuna optimization library.
- **best_optuna_model_new.pkl**: Another version of the best model found via Optuna.

### Results
- **likelihood_results.json**: Likelihood model results in JSON format.
- **toys_likelihood_results.json**: Likelihood results for toy datasets.
- **toys_likelihood_results_new.json**: Updated results for toy datasets.
- **toys_likelihood_results_neww.json**: A variant of the previous likelihood results.

### Environment
- **myenv**: A directory containing the virtual environment and related packages used for running the notebooks.
