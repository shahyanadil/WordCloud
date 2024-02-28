# New York Times Comments Analysis

## Overview
This project analyzes comments and articles data from The New York Times for the period spanning January 2017 to April 2018. It aims to provide insights into common words used in comments, identify top-rated comments, visualize comments selected as Editor's pick, and analyze user engagement based on usernames and locations.

## Requirements
- Python 3.x
- Libraries: pandas, numpy, matplotlib, wordcloud, PIL

## Installation
1. Clone the repository to your local machine.
2. Install the required Python libraries using pip:

## Usage
1. Ensure that you have the necessary CSV files (`CommentsJan2017.csv`, `CommentsFeb2017.csv`, ..., `ArticlesApril2018.csv`) in the `data` directory.
2. Run the Jupyter Notebook `analysis.ipynb`.
3. The notebook will generate various word clouds and visualizations based on the provided data.
4. Word clouds will be created for:
- Common words in comments
- Most common words in the top 10% most upvoted comments
- Most common words in the comments selected as Editor's pick
- Usernames with most comments
- Most common locations of the commenters

## Files Included
- `analysis.ipynb`: Jupyter Notebook containing the analysis code.
- `data/`: Directory containing CSV files with comments and articles data.
- `images/`: Directory containing image files used as masks for word clouds.

## Acknowledgments
- The New York Times for providing the dataset used in this analysis.
