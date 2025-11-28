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

* Loading and preprocessing the malaria dataset from the geoR R package, aggregating by location, and converting it into a spatial sf object.

* Mapping observed malaria prevalence and visualizing total cases across locations.

* Simulating data from the prior predictive distribution using Matérn covariance and creating histograms of simulated prevalence for selected locations.

* Fitting three spatial models with INLA:

    1. Exponential covariance model

    2. Matérn model using SPDE2

    3. Matérn model with penalized complexity priors

* Constructing meshes, prediction stacks, and generating maps of predicted prevalence, 95% credible intervals, and exceedance probabilities.

* Organizing estimated parameters into tables and visualizing model outputs on maps for comparison.

This homework demonstrates the application of geospatial statistics, spatial modeling, and Bayesian inference in R, providing both numeric summaries and interactive HTML visualizations of the results.

---

Thank you for checking out my work!
