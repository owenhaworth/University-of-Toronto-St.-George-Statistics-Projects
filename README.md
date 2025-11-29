# Spatial Data Analysis of Malaria Prevalence in The Gambia

Welcome! This repository contains my Spatial Data Analysis Assignment I completed during my time at the University of Toronto. You can view the assignment in HTML format by clicking the link below.

## About

This assignment was created using **R Markdown** and knitted to HTML. Each HTML file contains fully rendered analyses, plots, and tables, so you can view the final results directly in your browser.

## How to view

Click the link below to open the HTML file via GitHub Pages. You do not need GitHub to view the files; they will open in your browser like a regular website.

## Assignment

* [Spatial Data Analysis](https://owenhaworth.github.io/University-of-Toronto-St.-George-Statistics-Projects/Spatial-Data-Analysis.html)

## Overview

This assignment explores spatial analysis of malaria prevalence in The Gambia using R and geostatistical methods. Key tasks include:

* Question 1.1: Load and preprocess the malaria dataset from the geoR R package, aggregate by location, convert to a spatial sf object, and create a two-panel plot of total cases and prevalence.

* Question 1.2: Simulate data from the prior predictive distribution using a Matérn covariance matrix; create histograms of simulated prevalence for selected locations.

* Question 1.3: Generate maps of four different prior predictive draws of prevalence in The Gambia.

* Question 1.4: Fit three spatial models with INLA:

        1. Exponential covariance model

        2. Matérn model using SPDE2

        3.Matérn model with penalized complexity priors

    Construct meshes, prediction stacks, and prepare data for model fitting.

* Question 1.5: Create three maps per model showing predicted prevalence, lower 95% credible interval, and upper 95% credible interval.

* Question 1.6: Calculate and map the probability that malaria prevalence exceeds 50% across The Gambia.

This homework demonstrates the application of geospatial statistics, spatial modeling, and Bayesian inference in R, providing both numeric summaries and interactive HTML visualizations of the results.

---

Thank you for checking out my work!
