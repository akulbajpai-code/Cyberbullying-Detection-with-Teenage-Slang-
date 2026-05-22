# Cyberbullying Detection with Teenage Slang

A research and demonstration project for detecting cyberbullying in social media text by accounting for modern teenage slang, abbreviations, and informal language.

## Overview

This project explores how natural language processing (NLP) and machine learning can identify online harassment, rude language, and bullying content in text written by teenagers. It focuses on the unique challenges posed by slang, abbreviations, emojis, and informal expressions common in teen conversations.

## Goals

- Build a model capable of detecting cyberbullying in teen text.
- Improve classification accuracy by handling slang and nonstandard language.
- Provide a foundation for safer online social platforms and content moderation tools.

## Key Features

- Bullying detection for social media-style text
- Support for teen slang, abbreviations, and informal wording
- Modular design for dataset preparation, modeling, and evaluation
- Clear structure for future extension and experimentation

## Suggested Workflow

1. Collect or prepare a dataset of social media posts, comments, or chat text.
2. Preprocess text to normalize slang, abbreviations, and punctuation.
3. Train a classification model to distinguish bullying vs. non-bullying content.
4. Evaluate the model using standard metrics like accuracy, precision, recall, and F1-score.
5. Iterate on data cleaning and model features to improve performance.

## Installation

> This repository currently contains documentation only. Add code, dataset, and model files to implement the pipeline.

1. Clone the repository:

```bash
git clone https://github.com/<username>/Cyberbullying-Detection-with-Teenage-Slang-.git
cd Cyberbullying-Detection-with-Teenage-Slang-
```

2. Create a Python environment and install dependencies once code is added:

```bash
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

## Usage

Once implementation files are added, use this repository to:

- preprocess raw text data
- create feature representations for teenage slang
- train and validate cyberbullying classifiers
- run predictions on new text samples

## Future Improvements

- Add a curated teen slang lexicon and normalization module
- Support transformer-based models and embeddings
- Expand detection to multimodal content (text + images)
- Build a web interface for reviewing flagged text

## Contributing

Contributions are welcome. Please open issues or submit pull requests to:

- add dataset preprocessing scripts
- improve model training and evaluation
- document experiments and results

## License

Add a license file to specify how this project may be used.
