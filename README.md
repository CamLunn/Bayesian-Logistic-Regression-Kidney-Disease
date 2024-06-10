# Bayesian-Logistic-Regression-Kidney-Disease

## Repo Structure

```
.
├── README.md
├── R_analysis # Contains all files used in R
│   ├── Bayesian_DEGs_Comparison.Rmd    # Process coefficients (DEGs) from STAN models
│   ├── Kidney_vignette.Rmd             # Reproduce results from Nanostring
│   ├── R_data  # DATA
│   │   ├── 5 .csv files with results from STAN
│   └── images # Figures
│       ├── 7 venn diagram figures
├── build # Contains models
├── data        # DATA from both R and STAN
│   ├── 7 .csv/.txt files
├── model_notebook_1.ipynb    # STAN models in python
└── plots # FIGURES
```


## Project Summary

We present a Bayesian logistic regression model applied to the publicly available diabetic kidney disease (DKD) spatial transcriptomic dataset. The model took gene expression profiles from kidney tissue samples and predicted disease status. We construct logistic regression models using Laplace and horseshoe priors, and introduce a hierarchical model to account for spatial dependencies within kidney regions. Model performance is evaluated using both random and individual-based train/test splits. Results indicate that while the Laplace model exhibits strong predictive accuracy, it tends to overfit when tested on unseen individuals. The horseshoe model, although providing stricter regularization, faces convergence issues during optimization. Additionally, the hierarchical model performs poorly, suggesting potential limitations in the spatial dependency assumption. Prior-predictive checks reveal the ability of the models to capture disease status probabilities but highlight challenges in achieving balanced predictions. Analysis of model coefficients identifies differentially expressed genes (DEGs) associated with DKD, with both uniqueness and some overlap with the DEG list from the reference analysis by Nanostring. However, the models tend to overfit to outlier genes, impacting generalizability. Despite these challenges, the models consistently identify a subset of genes strongly associated with kidney disease, offering potential insights into disease mechanisms. In conclusion, our Bayesian logistic regression approach shows promise in identifying disease-associated genes in spatial transcriptomics data. Future work should address overfitting issues and refine model regularization to improve predictive performance and generalizability. Additionally, exploration of alternative sparsity priors and incorporation of additional metadata may enhance model robustness and biological interpretability.
