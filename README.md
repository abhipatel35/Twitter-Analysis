# Twitter-Analysis

This Python script retrieves tweets using the [GetOldTweets3](https://github.com/Mottl/GetOldTweets3) library and performs sentiment analysis on the gathered data.

## Overview

The script collects tweets posted between January 1, 2020, and April 1, 2020, using the specified search query. It then preprocesses the text data, cleans it by removing punctuations and stop words, and conducts sentiment analysis using a predefined sentiment lexicon.

## Technologies Used

- Python
- GetOldTweets3 Library
- Matplotlib Library

## Getting Started

To use this script:

1. Install the required libraries. You can install them via `pip`:

    ```bash
    pip install GetOldTweets3 matplotlib
    ```

2. Clone the repository:

    ```bash
    git clone https://github.com/abhipatel35/Twitter-Analysis.git
    ```

3. Run the script by executing:

    ```bash
    python main.py
    ```

## Acknowledgments

The script utilizes the [GetOldTweets3](https://github.com/Mottl/GetOldTweets3) library by Mottl to access historical tweets based on specified search criteria.

## Results

The script generates a bar graph illustrating the sentiment distribution among the collected tweets. Additionally, the sentiment analysis results are printed to the console.

## File Structure

- `main.py`: Python script containing the code for data collection and sentiment analysis.
- `sentiments.txt`: File containing sentiment lexicon or word sentiment associations.
- `graph.png`: Generated bar graph showing the sentiment distribution among the tweets.

---

Feel free to adjust and expand upon this content to better suit your project's specifics and provide more detailed instructions or explanations if needed.
