# Bayesian Inference & Classification – Advanced Statistical Methods

This project contains my **Advanced Topics in Statistics** coursework, demonstrating Bayesian modelling using JAGS and multiple machine learning classification algorithms in R.

## 📘 Overview

**Part A – Bayesian Inference**
- Hierarchical model of reaction times for schizophrenic vs. non-schizophrenic individuals.  
- Implemented in **R + JAGS** using MCMC sampling.  
- Diagnostics: traceplots, Gelman–Rubin statistic, posterior summaries.  
- Focus: parameter inference (`beta`, `tau`, `lambda`) and predictive model validation.

**Part B – Classification**
- Compared **KNN**, **QDA**, **Random Forest**, and **SVM** on a synthetic dataset.  
- Evaluated models using **Accuracy, Sensitivity, Specificity**, and **AUC**.  
- Applied **cross-validation** (caret) and visualised **ROC curves** with `plotROC`.

## 🧩 Repo Structure
data/            # given data for coursework
notebooks/       # main .Rmd analysis
reports/         # coursework PDF

## How to Run (Reproducibility)
**R / RStudio**
```r
install.packages(c(
  "ggplot2","dplyr","tidyr","gt","psych","caret","class",
  "plotROC","MASS","e1071","randomForest","R2jags",
  "MCMCvis","coda","lattice","kernlab"
))
# Open notebooks/supervised_learning_classification_bayesian_inference.Rmd
# Knit or run top-to-bottom

Findings (headline bullets)
	•	Bayesian: posterior summaries separate groups meaningfully; diagnostics (trace/GR) acceptable.
	•	Classification: KNN/QDA competitive; AUCs ~0.88–0.89 on the provided dataset; RF/SVM comparable.
	•	Reproducibility: single .Rmd runs end-to-end; dependencies listed above.
