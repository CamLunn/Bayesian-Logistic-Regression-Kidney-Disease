# Bayesian-Logistic-Regression-Kidney-Disease

## Repo Structure

```
.
├── README.md
├── R_analysis
│   ├── Bayesian_DEGs_Comparison.Rmd
│   ├── Kidney_vignette.Rmd
│   ├── R_data
│   │   ├── LMM_results_general.csv
│   │   ├── beta_filtered_genes_indv.csv
│   │   ├── beta_filtered_genes_indv_horseshoe.csv
│   │   ├── beta_filtered_genes_rand_horseshoe.csv
│   │   └── beta_filtered_genes_random_20.csv
│   └── images
│       ├── full_venn.pdf
│       ├── full_venn_complete.pdf
│       ├── individual_beta_horse_venn.pdf
│       ├── individual_beta_laplace_venn.pdf
│       ├── random_beta_horse_venn.pdf
│       ├── random_beta_laplace_venn.pdf
│       └── random_beta_laplace_venn.png
├── build
│   └── temp.macosx-10.9-x86_64-cpython-39
│       └── Users
│           └── ethanratliff-crain
│               └── Library
│                   └── Caches
│                       └── httpstan
│                           └── 4.10.1
│                               └── models
│                                   ├── 3zzh3wl5
│                                   │   └── model_3zzh3wl5.o
│                                   ├── b5fqgrf5
│                                   │   └── model_b5fqgrf5.o
│                                   └── ducafblz
│                                       └── model_ducafblz.o
├── data
│   ├── filtered_genes_indv.csv
│   ├── filtered_genes_indv_horseshoe.csv
│   ├── filtered_genes_rand_horseshoe.csv
│   ├── filtered_genes_random_20.csv
│   ├── kidney_countdata.txt
│   ├── kidney_genedata.txt
│   └── kidney_metadata.txt
├── model_notebook_1.ipynb
└── plots
    ├── betas_ccdf_indv.png
    ├── betas_ccdf_rand.png
    ├── horseshoe_indv_testing.png
    ├── horseshoe_indv_training.png
    ├── horseshoe_prior_density.png
    ├── horseshoe_prior_zeros.png
    ├── horseshoe_rand_testing.png
    ├── horseshoe_rand_training.png
    ├── laplace_indv_testing.png
    ├── laplace_indv_training.png
    ├── laplace_prior_density.png
    ├── laplace_prior_zeros.png
    ├── laplace_rand_testing.png
    ├── laplace_rand_training.png
    ├── largest_betas_hist_indv.png
    ├── largest_betas_hist_rand.png
    ├── mean_expression_hist.png
    ├── std_expression_hist.png
    ├── test_plot_indv.png
    ├── test_plot_rand.png
    ├── test_predictions_indv.png
    ├── test_predictions_indv_horseshoe.png
    ├── test_predictions_indv_region.png
    ├── test_predictions_rand_horseshoe.png
    ├── test_predictions_rand_region.png
    ├── test_predictions_random_20.png
    ├── train_predictions_indv.png
    ├── train_predictions_indv_horseshoe.png
    ├── train_predictions_indv_region.png
    ├── train_predictions_rand_horseshoe.png
    ├── train_predictions_rand_region.png
    ├── train_predictions_random_20.png
    ├── training_plot_indv.png
    └── training_plot_rand.png
```
