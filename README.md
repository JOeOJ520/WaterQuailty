## Background
Water is essential for all human life, it is important to have safe drinking water for health protection. This dataset from Kaggle describes the water quality metrics of different water bodies around the world. The sample size,n, for this dataset is 3276. There are 10 variables in this dataset in total: "Ph", "Hardness", "Solids", "Chloramines", "Sulfate", "conductivity", "Organic carbon", "Trihalomethanes", "Turbidity", and "Potability".

Within these variables, solids(ppm), or the total dissolved solids, are the major evaluation of the inorganic and organic minerals in the public water system. Higher solid level results in unwanted tastes in the water. This analysis will focus on the data on the level of solids (ppm) in the samples. More information about this dataset and the descriptions for each variable can be found [here](https://www.kaggle.com/adityakadiwal/water-potability?select=water_potability.csv)

## Project Goal
Using the computing power of modern computers,  this project applied unsupervised learning techniques, iteration algorithm, and data generation methods (Bootstrap and MCMC) to two major displaces of statistical inferences, Frequentist And Bayesian. the goal of this project is to estimate the parameters for possible statistical models for the samples.

## Enviorment
This project uses R with R markdown for better visualization. Please visit the official websites for documentation and installation of [R](https://www.r-project.org/), and [R Markdown](https://rmarkdown.rstudio.com/). [R studio](https://www.rstudio.com/) is recommended to open the .rmd file.

## Highlights
### Frequentist inference
- Newton-Raphson method for maximum likelihood estimation

- Bootstrap Confidence Interval with parametric bootstrap sampling

### Bayesian inference
- Choice of Priors

- Markov chain Monte Carlo (MCMC) Random Walk for posterior distributions

## Files in this project
- Unsupervised Anaylsis.rmd: R Markdown version for the report (with executable codes). R 4.1.2 or above, R studio and R Markdown package is required for executions.

- Unsupervised Anaylsis.pdf: The PDF version for the report,

- water_potability.csv: Dataset for this project.



 
 
