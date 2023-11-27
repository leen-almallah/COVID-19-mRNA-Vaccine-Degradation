# COVID-19 mRNA Vaccine Degradation Prediction

## Project Overview

The fight against the COVID-19 pandemic requires the development of an effective and stable mRNA vaccine. This Kaggle competition aims to leverage data science expertise to predict degradation rates at various locations along RNA sequences, focusing on reactivity, deg_Mg_pH10, and deg_Mg_50C.

## Problem Statement

mRNA vaccines, a promising candidate for COVID-19, face challenges in stability during transportation due to the spontaneous degradation of RNA molecules. This competition seeks to address the need for stable mRNA vaccines by predicting degradation rates and understanding the vulnerabilities in RNA sequences.

## Evaluation

Submissions are scored using **MCRMSE** (mean columnwise root mean squared error) for reactivity, deg_Mg_pH10, and deg_Mg_50C.

## Columns

- **id**: Identifier for each sample.
- **seq_scored**: Number of positions used in scoring.
- **seq_length**: Length of the RNA sequence.
- **sequence**: RNA sequence (combination of A, G, U, C).
- **structure**: Array indicating paired or unpaired bases.
- **reactivity**: Experimental reactivity values for the first 68 bases.
- **deg_pH10**: Experimental degradation values at high pH (pH 10).
- **deg_Mg_pH10**: Experimental degradation values with magnesium at high pH (pH 10).
- **deg_50C**: Experimental degradation values at high temperature (50 degrees Celsius).
- **deg_Mg_50C**: Experimental degradation values with magnesium at high temperature (50 degrees Celsius).
- **error**: Errors in experimental values.
- **predicted_loop_type**: Structural context of each character in the sequence.
