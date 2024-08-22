# AI-Powered Artwork Description and Emotion Classification

## Objective

This project demonstrates the integration of AI/ML models to generate descriptive text from images and classify the emotional tone of the generated descriptions. The Python application uses pre-trained models to analyze image URLs and their descriptions.

## Project Overview

The script performs the following tasks:
1. Accepts an image URL.
2. Generates a descriptive text (artwork description) using a pre-trained image-to-text model.
3. Analyzes the emotional tone of the generated description using a sentiment analysis model.
4. Outputs the image description and the identified emotional tone.

## Prerequisites

- **Python 3.7** or higher
- Required libraries:
  - `requests`
  - `Pillow`
  - `transformers`
  - `torch` (if not already installed, it will be required for running models)

## Installation

1. **Install Python** from [python.org](https://www.python.org/downloads/).
2. **Install the required libraries** using pip:

   ```bash
   pip install requests pillow transformers torch
