# Dialogue Act Recognition
Experimenting whether text-based or speech-based features are more effective.

## Requirements
`parselmouth`
`nltk`
`pandas`
`matplotlib`
`numpy`
`sklearn`

## Feature Sets

### Text Features
`train_text_features.csv`
`test_text_features.csv`

### Speech Features
`train_speech_features.csv`
`test_speech_features.csv`

### Text + Speech Features
`train_features.csv`
`test_features.csv`

## Setup
Obtain the `.wav` files and place them a folder `/data/wav`.

## To Run
1. Add the wav files (see `Setup`)
2. Run the [feature extraction script](code/raw_feature_extraction.ipynb)
3. Run the [feature preprocessing script](code/feature_preprocessing_analysis.ipynb)
4. Run the [classification script](code/classification.ipynb)
