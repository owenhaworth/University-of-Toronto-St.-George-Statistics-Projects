# Spatial Data Analysis of Malaria Prevalence in The Gambia

Welcome! This repository contains my Spatial Data Analysis assignment completed at the University of Toronto.  
The report was created using **R Markdown** and knitted to **HTML**, allowing all analyses, maps, and tables to be viewed directly in your web browser.

---

## How to View

Click the link below to open the HTML file via **GitHub Pages**.  
No GitHub account is required — the HTML will open like a regular website.

**→ [_View the full HTML report here_](https://owenhaworth.github.io/spatial-malaria-analysis/docs/Spatial-Data-Analysis.html)**

---

## About the Project

This assignment explores **geospatial statistics**, **Bayesian modeling**, and **spatial prediction** using malaria data from **The Gambia**.  
Analyses were conducted in **R**, using packages such as **geoR**, **sf**, **INLA**, **tmap**, and **raster**.

The project demonstrates:

- Spatial data wrangling and visualization  
- Prior predictive simulation  
- Spatial binomial regression using INLA  
- SPDE approaches with Matérn and exponential covariance models  
- Spatial prediction and uncertainty quantification  
- Mapping exceedance probabilities  

---

# Assignment Overview

## Q1.1 – Spatial Data Preparation and Visualization

### Key Tasks

- Load the malaria dataset and aggregate malaria test results by sampling location.  
- Convert coordinates to an **sf spatial object** with a proper CRS.  
- Extract elevation values (altitude) from raster data.  
- Produce a two-panel map displaying the **total number tested** and **prevalence** across The Gambia.

---

## Q1.2 – Prior Predictive Simulation

### Key Tasks

- Compute geodesic distance matrices between sampling locations.  
- Simulate **100 prior predictive datasets** using Bayesian logistic regression with:  
  - Normal priors for regression coefficients  
  - Gamma priors for spatial range and smoothness  
  - A Matérn covariance structure  
- For the first six locations, generate histograms of prior-predicted prevalence with observed values overlaid.

---

## Q1.3 – Mapping Prior Predictive Draws

### Key Tasks

- Generate maps of four distinct prior predictive simulations of malaria prevalence.  
- Visualize spatial variability implied purely by the **prior**, before observing any data.

---

## Q1.4 – Spatial Modeling with INLA

Three spatial binomial regression models were fitted using INLA:

1. **Exponential covariance model**  
2. **Matérn model using SPDE2**  
3. **Matérn model with Penalized Complexity (PC) priors**

### Key Tasks

- Construct spatial meshes for the SPDE models.  
- Build INLA stacks for estimation and spatial prediction.  
- Fit all three models and extract posterior summaries for fixed effects and spatial parameters.  
- Organize parameter estimates (mean and 95% credible intervals) into a results table.

---

## Q1.5 – Mapping Predictive Distributions

### Key Tasks

For each of the three spatial models, produce:

- **Map 1:** Posterior mean predicted malaria prevalence  
- **Map 2:** Lower bound of the 95% credible interval  
- **Map 3:** Upper bound of the 95% credible interval  

These maps show areas of high uncertainty and contrast differences between covariance structures.

---

## Q1.6 – Exceedance Probabilities

### Key Tasks

- Compute the probability that malaria prevalence exceeds **50%** across The Gambia.  
- Map exceedance probabilities for each spatial model to identify regions with significant malaria burden.

---

## Purpose of the Assignment

This assignment demonstrates:

- Spatial data manipulation using **sf**, **sp**, and **raster**  
- Bayesian logistic regression with spatial random fields  
- Use of **INLA + SPDE** for scalable geostatistical modeling  
- Prior predictive checks and model comparison  
- Spatial prediction and uncertainty quantification  
- Creation of interactive and static maps using **tmap**  
- Interpretation of spatial model outputs and exceedance surfaces

---

## Thank You for Visiting!

Feel free to explore the HTML report and source code.  
If you have questions or suggestions, I’d be happy to connect!
