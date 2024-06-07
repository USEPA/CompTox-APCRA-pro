# CompTox-APCRA-pro
Disclaimer: The United States Environmental Protection Agency (EPA) GitHub project code is provided on an "as is" basis and the user assumes responsibility for its use. EPA has relinquished control of the information and no longer has responsibility to protect the integrity, confidentiality, or availability of the information. Any reference to specific commercial products, processes, or services by service mark, trademark, manufacturer, or otherwise, does not constitute or imply their endorsement, recommendation or favoring by EPA. The EPA seal and logo shall not be used in any manner to imply endorsement of any commercial product or activity by EPA or the United States Government. 

# What the project does. 
This project includes all of the code for analysis and figures for the manuscript, Paul Friedman et al, "Integration of New Approach Methods for the Assessment of Data Poor Chemicals."

## 1-chemical-space-ad.Rmd
This .Rmd and knitted html handles the data and visualization around the in vitro aqueous screening applicability domain and describing the chemicals included in this case study based on their physicochemical properties and use properties.

## 2-toxicodynamic-nams.Rmd
This .Rmd and knitted html handles the data from ToxCast (invitrodb v3.5) and flat files from the high-throughput transcriptomics (HTTr), Cell Painting (high-throughput phenotypic profiling, or HTPP), and A*STAR HIPPTox platforms. The goal of this .Rmd is to create the source data file of all in vitro toxicodynamic NAMs to develop NAM-based POD values.

## 3-toxval-data.Rmd
This .Rmd and knitted html handles the data from EPA's Toxicity Value Database (ToxVal v9.4) to create summary in vivo point-of-departure (POD) values from ToxVal.

## 4-ivive-pod.Rmd
This .Rmd and knitted html handles the in vitro to in vivo extrapolation of administered equivalent doses from the in vitro bioactivity nams from 2-toxicodynamic-nams.Rmd. The IVIVE approach here is based on methods in the R library(httk). This .Rmd further explores the best way to estimate the NAM-based POD (POD-NAM), using animal-based PODs from ToxVal and other sources as benchmarking comparators. Finally, this .Rmd looks at understanding the ratios of PODs from different data streams.

## 5-ber-flags.Rmd
This .Rmd and knitted html handles the POD-NAM information alongisde exposure predictions from ExpoCast SEEM3 to produce bioactivity:exposure ratios (BERs). Further, this .Rmd describes creation of the hazard flags in this case study. 

# Why the project is useful.  
This project is useful as a way to view pre-knitted code (from the .html files). It is also a useful source for regenerating analyses in this manuscript, or borrowing code chunks and repurposing them for new, similar analyses.

# How users can get started with the project. 
This repository contains .html of pre-run code that can be browsed to understand what was done in Paul Friedman et al. 2024.

# Where users can get help with the project. 
Check out our manuscript available here:
paul-friedman.katie@epa.gov

