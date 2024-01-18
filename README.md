# Predicting the Geographical Origin of Music based on Soundtrack Analysis

This project implements a solution to predict the geographical origin of music, inspired by Fang Zhou's article ["Predicting the Geographical Origin of Music"](https://ieeexplore.ieee.org/document/7023456).

## Dataset

The dataset comprises approximately 250-300 examples for each country, consisting of 323 features. The last 5 features include labels such as geographical coordinates, country name, subregion, and region.

## Classifiers and Results

The dataset was tested on 10 different classifiers, and the best models were optimized. After hyperparameter optimization, the Random Forest classifier achieved an accuracy of 60.19% in predicting the country of recording origin. Results were compared to Fang Zhou's dataset metrics.

## Usage

To use the notebook:
- Fill in paths to the required files as indicated in the notebook.
- For analysis, use tracks from traditional music examples.
- For classification, use the `Dataset.csv` file.
- For comparison, use the `Dataset_comparison.csv` file.

## Note on Dataset

The dataset was created using recordings that couldn't be published due to copyright restrictions. The first part of the notebook (Data preparation) can be used with your own data.


