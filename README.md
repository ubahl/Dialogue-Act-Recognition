# Dialogue Act Recognition
Experimenting whether text-based or speech-based features are most effective for recognizing dialogue acts in speech.

## Requirements
`parselmouth`
`nltk`
`pandas`
`matplotlib`
`numpy`
`sklearn`

## Setup
Obtain the `.wav` files and place them a folder `/data/wav`.

## To Run
1. Add the wav files (see `Setup`)
2. Run the [feature extraction script](code/raw_feature_extraction.ipynb)
3. Run the [feature preprocessing script](code/feature_preprocessing_analysis.ipynb)
4. Run the [classification script](code/classification.ipynb)

## Notebooks

[raw_feature_extraction.ipynb](code/raw_feature_extraction.ipynb) extracts both the text-based and speech-based features.

[feature_preprocessing_analysis.ipynb](code/feature_preprocessing_analysis.ipynb) analyzes the features and preprocesses them.

[classification.ipynb](code/classification.ipynb) runs different classifiers and reports the results.
