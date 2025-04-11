# Word Segmentation using Transitional Probabilities

This project simulates how infants can learn to segment words from continuous speech using statistical learning mechanisms, specifically transitional probabilities between syllables. The work is inspired by foundational research in language acquisition and cognitive science.

## Overview

The goal is to implement a simple model that identifies word boundaries in a stream of syllables from an artificial language, using the probability that one syllable follows another. This is based on the idea that syllables within a word are more likely to occur together than syllables from different words.

## References

Before starting, it is recommended to read the following papers:

- Aslin, R. N., Saffran, J. R., & Newport, E. L. (1998). Computation of conditional probability statistics by 8-month-old infants. *Psychological Science, 9*(4), 321–324. [DOI](https://doi.org/10.1111/1467-9280.00063)

- Brent, M. R., & Cartwright, T. A. (1996). Distributional regularity and phonotactic constraints are useful for segmentation. *Cognition, 61*(1–2), 93–125.

## Features

- Parses a continuous stream of syllables.
- Calculates **transitional probabilities** between adjacent syllables.
- Detects probable word boundaries using probability thresholds.
- Includes visualizations and analysis of segmentation results.

## Getting Started

### Prerequisites

- Python 3.7+
- Jupyter Notebook or Google Colab

### Installation

If running locally:

```bash
pip install matplotlib numpy

## Usage

This notebook is designed for educational purposes and is especially relevant for those interested in:

- Language acquisition
- Statistical learning
- Cognitive science and linguistics
- Data science applications in NLP

To use the notebook:

1. Load `language (3).ipynb` into Jupyter or Google Colab.
2. Follow the steps in each cell to compute transitional probabilities.
3. Segment an artificial syllable stream into likely words.
4. Visualize the segmentation using simple plots.

## License

This project is intended for educational use only. If using or adapting this work in a publication or project, please cite the original research papers listed in the References section.

## Author

Developed as part of an assignment exploring statistical learning in language.  
Feel free to adapt or build upon it for your own educational or research purposes.

