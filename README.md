# Spotify Song Recommendation System
A content-based recommendation system that suggests songs based on audio features using cosine similarity. This project analyzes the top 2000 tracks on Spotify from 2000-2019 to find similar songs.

## Features
* Content-based filtering using cosine similarity

* Two recommendation modes: same-genre and cross-genre suggestions

* Analysis of audio features including danceability, energy, tempo, and more

* Easy-to-use interface for song recommendations

## Dataset
The dataset contains 2000 songs with 18 audio features including:

* Danceability

* Energy

* Key

* Loudness

* Speechiness

* Acousticness

* Instrumentalness

* Liveness

* Valence

* Tempo

* Duration

* Popularity

* Year

## How It Works
1. The system calculates cosine similarity between song vectors based on their audio features:

2. Select a target song from the dataset

3. Compute similarity scores between the target and all other songs

4. Rank songs by similarity score

5. Provide recommendations either from the same genre or across different genres

## Usage
1. Clone the repository

2. Ensure you have the required dependencies: pandas, numpy

3. Run the Jupyter notebook recsys_songs.ipynb

4. Modify the song variable to any track from the dataset

5. Execute the recommendation cells to get suggestions

## Example
Input: "Circles" by Post Malone

Output recommendations might include:

* Similar pop songs with comparable audio features

* Or cross-genre suggestions with similar musical characteristics

## Files
* recsys_songs.ipynb - Main Jupyter notebook with implementation

* songs_normalize.csv - Dataset of Spotify songs (not included in this repo)

## Future Enhancements
* Integration with Spotify API for real-time recommendations

* User interface for easier interaction

* Collaborative filtering implementation

* Hybrid recommendation approach

This project demonstrates the application of cosine similarity and content-based filtering for music recommendation systems.
