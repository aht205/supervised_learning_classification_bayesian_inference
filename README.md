# Bayesian Inference & Supervised Learning (R)

This repository contains my **Advanced Topics in Statistics** coursework which looks at:
- **Bayesian inference** of reaction times using **R + JAGS (MCMC)**  
- **Supervised classification** with **KNN, QDA, Random Forest, SVM** (caret)

## 📁 Repo Structure
```
data/            # raw data kept local; small processed samples only
notebooks/       # main .Rmd analysis
reports/         # figures/outputs; coursework PDF
```

## ⚙️ How to Run (Reproducibility)

**R / RStudio**
```r
install.packages(c(
  "ggplot2","dplyr","tidyr","gt","psych","caret","class",
  "plotROC","MASS","e1071","randomForest","R2jags",
  "MCMCvis","coda","lattice","kernlab"
))
# Open notebooks/supervised_learning_classification_bayesian_inference.Rmd
# Knit or run top-to-bottom
```

> Data: the data given for the coursework.

## 📊 Findings (headline bullets)
- **Bayesian:** posterior summaries separate groups meaningfully; diagnostics (trace/GR) acceptable.  
- **Classification:** KNN/QDA competitive; AUCs ~0.88–0.89 on the provided dataset; RF/SVM comparable.  
- **Reproducibility:** single `.Rmd` runs end-to-end; dependencies listed above.

## 🧠 Skills Demonstrated
- Bayesian hierarchical modelling (JAGS)
- MCMC diagnostics & interpretation
- Supervised ML methods (KNN, QDA, RF, SVM)
- Model evaluation (confusion matrices, ROC, AUC)
- Data wrangling (`tidyverse`) and reproducible reporting (`RMarkdown`)

## 🔑 Keywords
`R` `RMarkdown` `Bayesian` `JAGS` `MCMC` `caret` `KNN` `QDA` `RandomForest` `SVM` `ROC` `AUC` `statistics`
