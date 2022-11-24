# Forest classification

## Overview
This project hosts the code for soluting a classification problem based on forest remote sensing datasets.


## Files
- forest_classification.ipynb	: notebook for solution
- trainging.csv   : contains trainging data
- testing.csv   : contains testing data

Data used for this work can be downloaded from the following link: https://archive.ics.uci.edu/ml/datasets/Forest%2Btype%2Bmapping

## Attribute Information:
Class: 's' ('Sugi' forest), 'h' ('Hinoki' forest), 'd' ('Mixed deciduous' forest), 'o' ('Other' non-forest land)
b1 - b9: ASTER image bands containing spectral information in the green, red, and near infrared wavelengths for three dates (Sept. 26, 2010; March 19, 2011; May 08, 2011.
pred_minus_obs_S_b1 - pred_minus_obs_S_b9: Predicted spectral values (based on spatial interpolation) minus actual spectral values for the 's' class (b1-b9).
pred_minus_obs_H_b1 - pred_minus_obs_H_b9: Predicted spectral values (based on spatial interpolation) minus actual spectral values for the 'h' class (b1-b9).

## Original paper
Johnson, B., Tateishi, R., Xie, Z., 2012. Using geographically-weighted variables for image classification. Remote Sensing Letters, 3 (6), 491-499.