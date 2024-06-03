# Music Data Analysis

## Overview
This project performs a detailed analysis of a music dataset to uncover insights into track popularity, artist performance, and other key features. The analysis includes visualizations and statistical summaries to provide a comprehensive understanding of the dataset.

## Data
The dataset used in this project contains information about various music tracks. Key columns include:

- `instance_id`: Unique identifier for each track.
- `artist_name`: Name of the artist.
- `track_name`: Name of the track.
- `popularity`: Popularity score of the track.
- `acousticness`: A measure of how acoustic the track is.
- `danceability`: A measure of how suitable a track is for dancing.
- `duration_ms`: Duration of the track in milliseconds.
- `energy`: Energy measure of the track.
- `instrumentalness`: Predicts whether a track contains no vocals.
- `key`: The key the track is in.
- `liveness`: Detects the presence of an audience in the recording.
- `loudness`: Overall loudness of the track.
- `mode`: Modality of the track (major or minor).
- `release_date`: Release date of the track.
- `tempo`: Speed of the track.
- `valence`: Measure of the musical positiveness conveyed by a track.
- `genre`: Genre of the track (if available).

## Analysis Performed
1. **Top 10 Most Popular Tracks**: Lists and visualizes the top 10 tracks based on popularity.
2. **Average Popularity by Genre**: Calculates and visualizes the average popularity of tracks by genre (if the genre column exists).
3. **Distribution of Danceability**: Plots the distribution of danceability scores.
4. **Top Artists by Number of Tracks**: Identifies and visualizes the artists with the most tracks.
5. **Comparison of Features by Popularity Quartiles**: Divides tracks into quartiles based on popularity and compares their features using box plots.
6. **Feature Importance for Popularity**: Uses a Random Forest model to identify which features are most important for predicting a track's popularity.
7. **Time Series Analysis**: Performs a time series analysis to see how track features have evolved over time, provided a release date column exists.

## Visualizations
- **Histograms**: For distributions of popularity and danceability.
- **Scatter Plots**: To show relationships between danceability and energy, and energy and loudness.
- **Bar Plots**: For top artists by average popularity and number of tracks.
- **Box Plots**: For comparing features across popularity quartiles.
- **Correlation Heatmap**: To show correlations between numeric features.
- **Time Series Plot**: For tracking average popularity over time.

## Requirements
- Python 3.6+
- pandas
- matplotlib
- seaborn
- scikit-learn
