# Wordle Tweet Analysis

This project analyzes tweets containing results from the popular online
game Wordle
It explores how players share their results, how many attempts are
typically needed to solve puzzles, and provides visual insights into
daily tweet activity and guess accuracy.



## Project Overview

The notebook performs the following steps:

1.  Data Loading & Cleaning
    -   Reads tweet data from `tweets.csv`
    -   Extracts relevant fields such as `wordle_id`, `n_attempts`, and
        `tweet_date`
    -   Normalizes tweet text formatting (e.g., ensuring consistency of
        squares ⬛/⬜)
2.  Exploratory Data Analysis (EDA)
    -   Counts number of tweets per day
    -   Examines how many attempts players typically need to solve
        Wordle
    -   Groups attempts by puzzle ID (`wordle_id`) for comparison
3.  Visualization
    -   Line chart of Wordle tweets per day
    -   Bar charts showing attempts distribution
    -   Heatmaps summarizing attempt counts across Wordle IDs
    -   Breakdown of correct, wrong spot, and incorrect guesses by
       attempt number



## Installation

Clone the repository and install dependencies:


git clone <your-repo-url>
cd <your-repo-folder>
pip install -r requirements.txt




## Requirements

This project uses:

-   Python 3.9+
-   Pandas
-   NumPy
-   Matplotlib
-   Seaborn

Install everything via:


pip install pandas numpy matplotlib seaborn




## Usage

Run the Jupyter notebook:


jupyter notebook main.ipynb


Make sure `tweets.csv` is in the same directory as the notebook.



## Example Results

-   Daily tweet counts show how Wordle hype grew over time.
-   Distribution of attempts reveals most players solve Wordle in
    3-5 tries.
-   Heatmaps provide a clear picture of how success rates vary
    across puzzles.


