# Podcast Scraping with Spotify Web API

This project uses the Spotify Web API and BeautifulSoup to scrape and analyze podcast data available in Australia. It collects various details about podcasts, including viewer counts, episode numbers, and listener statistics.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Data Description](#data-description)
- [Analysis](#analysis)
- [Results](#results)
- [License](#license)

## Installation

To run this project, you need to install the following Python libraries:

```bash
pip install requests pandas beautifulsoup4 plotly textblob scikit-learn
Usage
Set Up Credentials: Replace the client_id and client_secret in the script with your Spotify API credentials.

Run the Script: Execute the script to scrape the podcast data and save it to a CSV file.


python podcast_scraping.py
View Results: After running the script, check the australian_podcasts.csv file for the collected podcast data.
Data Description
The dataset contains the following columns:

Column	Description
Title	Podcast title
Total Episodes	Total number of episodes
Link	Link to the podcast on Spotify
Description	Podcast description
Publisher	Publisher of the podcast
Reviews	Reviews extracted from the podcast webpage
Analysis
This project includes various analyses, including:

Word Count Distribution: Analyzing the length of podcast descriptions.
Most Common Words: Identifying the most frequently used words in podcast descriptions.
Popularity Analysis: Visualizing the distribution of total episodes by publisher.
Sentiment Analysis: Assessing the sentiment of podcast descriptions using TextBlob.
Topic Modeling: Using Latent Dirichlet Allocation (LDA) to discover topics within the podcast descriptions.
Results
Visualizations generated from the analysis include:

Histograms of word counts and sentiment distributions.
Bar plots for top podcasts by total episodes.
Box plots for total episodes across different publishers.
Pie charts showing podcast distribution by publisher.
Check out the results by exploring the generated plots!

License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgments
Spotify Developer API
BeautifulSoup Documentation





