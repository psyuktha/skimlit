# SkimLit: Categorizing Medical Research Paper Abstracts

## Overview

SkimLit is a project designed to automatically categorize sections of medical research paper abstracts into five distinct categories:
- Background
- Methods
- Objective
- Results
- Conclusions

This is achieved using a multimodal model that incorporates both word and character level tokenization, as well as a model for line number.

## Dataset

The dataset is sourced from [PubMed 200k RCT](https://github.com/Franck-Dernoncourt/pubmed-rct)

## Features

- **Multimodal Tokenization**: Utilizes both word and character level tokenization to capture detailed textual features.
- **Line Number Model**: Incorporates the position of each line within the abstract to provide context.
- **Category Prediction**: Accurately predicts the category for each line in the abstract.

## Model Details

The multimodal model combines:

- **Word Level Tokenization**: Splits the abstract into words and extracts features.
- **Character Level Tokenization**: Splits the abstract into characters and extracts features.
- **Line Number Model**: Incorporates the line number of each line within the abstract.

## Training
The training process involves:

Training the model using a suitable machine learning framework Tensorflow .
