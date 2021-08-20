# COVID19-variants-modelling-paper-2021
A repository for code from the paper "Possible future waves of SARS-CoV-2 infection generated by variants of concern with a range of characteristics"

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.5224546.svg)](https://doi.org/10.5281/zenodo.5224546)

Preprint details: L Dyson, EM Hill, S Moore, J Curran-Sebastian, MJ Tildesley, KA Lythgoe, T House, L Pellis, MJ Keeling. (2021) Possible future waves of SARS-CoV-2 infection generated by variants of concern with a range of characteristics. medRxiv doi: 10.1101/2021.06.07.21258476. URL: https://doi.org/10.1101/2021.06.07.21258476.

Model simulations are performed using the programming language Matlab.

Please find below an explainer of the main files within this repository.

## make_parameters.m
Construct parameter structure that is then passed into the main model simulation

## run_simple_vaccines.m
Function to carry out simulation of two variant SARS-CoV-2 transmission model

## run_gillespie_model_for_mex.m
Function to run the VOC importation model (a Gillespie simulation)

## get_parsimonious_model_results.m
Script to perform the simulations presented in the main text and Supporting Information associated with the parsimonious model and analysis of VOC targeted vaccines.

## get_hybrid_model_results.m
Generate results from the VOC importation model and hybrid stochastic-parsimonious transmission model

## plot_script_parsimonious_model.m
Script to generate plots presented in main text and Supporting Information associated with the parsimonious model and analysis of VOC targeted vaccines.

## cbrewer
A package with colorbrewer schemes for Matlab
