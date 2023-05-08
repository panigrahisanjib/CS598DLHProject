# Diabetes Dataset Analysis Using Deepr
This repository contains three different Python scripts that analyze the diabetes dataset from the University of California Irvine Machine Learning Repository. The dataset contains data from patients who were hospitalized with diabetes and includes demographic information, medical history, and medication information.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [Execuation](#Execution)

## Installation

To use these scripts, you will need to install the following packages:

pandas,
sklearn,
numpy,
tensorflow,
gensim,
matplotlib

## Usage

logistic_regression.py
This script uses logistic regression to predict whether a patient will be readmitted to the hospital. It preprocesses the data, creates a bag-of-words representation of the diagnosis codes, and trains a logistic regression model on the data.

neural_network.py
This script uses a neural network to predict whether a patient will be readmitted to the hospital. It preprocesses the data, splits it into training and testing sets, scales the numerical features, and trains a neural network on the data.

word2vec.py
This script uses Word2Vec to embed the diagnosis codes and trains a neural network to predict whether a patient will be readmitted to the hospital. It preprocesses the data, creates a corpus of diagnosis codes, trains a Word2Vec model on the corpus, tokenizes the diagnosis codes, and trains a neural network on the data.

## Contribution
| Task | Owner | Time |
| --- | --- | --- |
| Topic Selection | Mony, Sanjib | 2h |
| Finding Dataset | Mony, Sanjib | 10h |
| Proposal/Draft/Final Reports | Mony, Sanjib | 6h |
| Implementation BOW | Mony, Sanjib | 3h |
| Implementation Deepr (Rand-Init) | Mony | 6h |
| Implementation (word2Vec) | Sanjib | 6h |

## [Execuation](#Execution)

The model [Deepr_Project.ipynb](./Deepr_Project.ipynb) can be run from jupytor notebook or google colab. If running from google colab the dataset file [diabetic_data.csv](./diabetic_data.csv) needs to be uploaded in google colab directory



