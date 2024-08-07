# Spotify Playlist Analysis

## Project Overview

This project involves analyzing data from a Spotify playlist of mine using Python and Power BI. The data was scraped through Spotify's Python Library 'Spotipy', and it includes various attributes of the songs in the playlist such as name, artist, album, duration, release date, popularity, genres, track URL, and image URL.

The main goals of this project are:
- To perform data analysis using Pandas.
- To visualize the data using 3 different Python libraries (Matplotlib, Seaborn, and Plotly).
- To do further analysis and visualization using Power BI.

## Data Description

The data in use is from a Spotify playlist of mine that has over 1100 songs and that I've been adding songs to since 2018.

Playlist --> [Here](https://open.spotify.com/playlist/2TcJW6fV7JKdd4aAiYRGYc?si=d2aa1e392a1c4cd3)

## Data Analysis

### Python and Pandas

The data was initially analyzed using Python and Pandas. Here are some of the analyses performed:
- **Missing Values**: Some songs had missing values in multiple cells.
- **Data Calculation**: Calculating basic statistics such as mean, median, and standard deviation for numeric columns.
- **Genre Extraction**: Column for genres was extracted on its own and it was a list of lists instead of a list of strings.
- **Extraction**: Extracted year of release from the release date for simplification of some plots later.

## Data Visualization in Python

### Python's Plotly Library

- **Popularity vs Duration**

![Popularity vs Duration](PDFs%20and%20Images/Popularity%20vs%20Duration.png)

- **Top 25 Most Frequent Artists**

![Top 25 Most Frequent Artists](PDFs%20and%20Images/Top%2025%20Most%20Frequest%20Artists.png)

### Python's Matplotlib and Seaborn Libraries

- **Distribution of Song Durations**

![Distribution of Song Durations](PDFs%20and%20Images/Song%20Durations.png)

- **Top 10 Artists by Average Popularity**

![Top 10 Artists by Average Popularity](PDFs%20and%20Images/Top%2010%20Artists%20by%20Average%20Popularity.png)


## Data Visualization in Power BI

The following Power BI Dashboard shows the following:
- Dropdown List for Song Choosing
- Information About the Chosen Song
- Most Popular Songs in the Playlist
- Longest 25 Songs
- Total Songs Released by Year

![Power BI Dashboard](PDFs%20and%20Images/SpotifyDashboard.png)

## Conclusion

This project demonstrates the process of scraping data from Spotify playlists using Spotify's Python library (Spotipy), performing data analysis using Pandas, and visualizing the results using Matplotlib, Seaborn, Plotly, and Power BI. The interactive elements in Power BI allow users to explore the playlist data dynamically, making it a powerful tool for data analysis and presentation.

## Files in the Folders Included

- `1 - ScrapedPlaylist.csv`: The dataset containing the playlist data.
- `2 - AnalysedPlaylist.csv`: The dataset post-analysis ready for visualizations.
- `1 - ScrapePlaylist.ipynb`: Jupyter Notebook File for scraping the playlist.
- `2 - AnalysePlaylist.ipynb`: Jupyter Notebook File for analyzing and visualizing the playlist.
- `SpotifyDashboard.pbix`: Power BI report file with the visualizations.
- `README.md`: This readme file.

As well as various images and a single PDF file for the Power BI report.

## How to Run

1. **Scrape Playlist**: Open `1 - ScrapePlaylist.ipynb` in Jupyter Notebook or any compatible environment and run the cells to perform data analysis. This will extract `1 - ScrapedPlaylist.csv` to the same folder that you're running the Jupyter Notebook file from.
2. **Analyze Playlist**: Analyze your playlist for empty cells and rows by running `2 - AnalysePlaylist.ipynb`, it will also visualize some of the data using multiple visualization libraries.

Feel free to customize and expand upon this project to suit your specific needs and interests.
