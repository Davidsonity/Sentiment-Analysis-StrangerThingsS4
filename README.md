# Sentistranger: Unveiling Twitter Sentiment for Stranger Things

![ST4](https://media.giphy.com/media/l41Y9SKrl3kLVamfC/giphy.gif)

## Description

This project performs sentiment analysis on tweets related to the Netflix series "Stranger Things." The analysis focuses on tweets from the release date of the first half of Season 4 (May 27, 2022) to the complete series release date (July 2, 2022). The goal is to understand the overall sentiment of Twitter users towards the latest season.

The project consists of two main stages:
1. Web Scraping using snscrape to collect tweets related to "Stranger Things."
2. Performing Sentiment Analysis using the Transformers model.

## Repository Structure

The repository contains the following files and directories:

- `data`: Directory containing the data files used in the project.
- `images`: Directory containing images related to the project.
- `LICENSE`: License file specifying the terms of use for the project.
- `README.md`: Detailed information about the project, its purpose, and usage.
- `notebook.ipynb`: Jupyter Notebook file containing the code and analysis for the project.

## Requirements

- Python 3
- snscrape
- Jupyter Notebook
- Transformers library
- pandas, numpy, PIL, tqdm, plotly, matplotlib

## Usage

1. Clone the repository

2. Navigate to the project directory:

3. Install the required dependencies:

4. Open the Jupyter Notebook `notebook.ipynb` to run the project's code and analysis. The notebook provides step-by-step instructions and explanations of each stage of the project.

5. The notebook performs web scraping using snscrape to collect tweets and stores them in the `data` directory. It then uses the Transformers library to perform sentiment analysis on the collected tweets.

6. The analysis includes visualizations of sentiment distribution, sentiment scores, and other relevant insights.

## Acknowledgments

- The Transformers library and the Twitter-RoBERTa model by CardiffNLP were used for sentiment analysis.
- The snscrape library was used for web scraping Twitter data.

## License

This project is licensed under the [MIT License](LICENSE).
