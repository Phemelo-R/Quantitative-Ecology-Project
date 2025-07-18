## BCB743 Quantitative Ecology Project Repository
This repository contains the data files, analysis scripts, and final outputs for the Honours Quantitative Ecology (BCB743) module project. The materials here show the data cleaning, transformation, and statistical analysis done collaboratively by Shane Ngwenya, Phemelo Rutlokoane, and Kezia Samuels as part of the coursework requirements.

The primary output is a Quarto document (.qmd) that provides an analytical workflow from initial data preparation to final statistical summaries and visualisations. Each section of the document is annotated with the names of the students responsible for that component of the work.

Repository Contents
📄 Quarto Document
BCB743_Final_Project.qmd: The main report file, containing the full workflow used to process and analyse the datasets. This document integrates R code and narrative interpretation, and produces a rendered HTML report on execution.

📊 Data Files
Adder_Spe_ABD_Clean.csv
This is the cleaned adder species abundance matrix, where each row represents a site and each column represents a species. Species abundances are recorded as raw counts.

Env_var_clean.csv
This file includes environmental variables relevant to each sampling site. These variables include vegetation types and climatic variables drawn from the South African National Biodiversity Institute (SANBI) and WorldClim. This file was used as the basis for multivariate environmental analysis (e.g. PCA, CCA).

Num_env_var.csv
This file contains land cover classification groups gathered from raster-based spatial data. It quantifies proportions of different land cover classes at each site and was used as the basis for multivariate environmental analysis (e.g. NMDS).

