# memrisk-llm
Code for evaluating memorization risk and sensitive-term reappearance in patient narrative corpora using language models.
# memrisk-llm

Research code for analyzing memorization-related signals in language models trained on prostate cancer patient narratives.

## Project description

This repository contains computational scripts for processing Reddit-based prostate cancer narratives, constructing evaluation prompts, running fine-tuned language-model experiments, and quantifying memorization-related signals in generated text.

Main components include:

- text preprocessing and paragraph-level corpus preparation
- lexical and network-based quality-control analysis
- deterministic train/validation/test split construction
- prompt-set generation for evaluation
- generation-based testing with an autoregressive language model
- computation of reconstruction and sensitive-term reappearance metrics
- figure and table generation for reporting

## Software environment

Python 3.10+

Core packages:

- nltk
- networkx
- numpy
- scipy
- matplotlib
- transformers
- torch

## Data access

The study used publicly available Reddit discussions related to prostate cancer.  
To reduce privacy risk and to respect platform policies, the raw text data are not redistributed in this repository.

## Notes


## License

Research code provided by the author for transparency and reproducibility of the associated study.
This repository is intended for research transparency and computational reproducibility.
