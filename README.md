# Spotify Song Popularity Prediction
A more detailed version of the report can be found in the Phase 4 pdf in the repository.
## Abstract
This project focuses on identifying trends in songs on Spotify and predicting song popularity using machine learning. The data is sourced from Kaggle's Spotify Multi-Genre Playlists Data, covering seven different genres. Features such as acousticness, danceability, energy, and more are considered for analysis.

## Introduction
### Define the Problem
In the dynamic realm of music consumption, understanding the factors influencing song popularity on Spotify is paramount. Spotify's dominance in the music streaming market and its algorithmic scoring of songs form the basis of this exploration.

### Motivation and Objectives
The primary goal is to identify trends or patterns in song features that correlate with increased popularity. Motivated by a passion for music and curiosity about the factors behind song popularity, we explore Spotify's rich dataset.

### Related Work
Acknowledging previous studies that have tackled similar challenges, we contribute to the ongoing discourse around predicting song popularity.

## Methodology
### Acquisition
Datasets for seven genres were obtained from Kaggle, each containing key features. Using the Spotify library for Python, we sourced data from Spotify's official playlists in 2021.

### Preparation
In the initial stages of exploratory data analysis (EDA), we ensured clean datasets by handling null values, checking for duplicates, and selecting relevant features for analysis.

### Model Selection
Considering logistic regression, decision tree classification, random forest classification, and k-nearest neighbor models, we opted for the random forest classification model, achieving an accuracy of 81.5%.

## Results and Evaluation
The random forest model demonstrated an accuracy of approximately 81.46%. Evaluation metrics reveal a higher recall for the "unpopular" bin, emphasizing its ability to identify instances of unpopular songs.

## Conclusion
While features impacting song popularity, such as danceability and loudness, were identified, no single outstanding trend emerged. The holistic nature of music popularity suggests a complex interplay of features, providing insights for artists and producers.

## Future Work and Potential Improvements
Future research could explore additional factors affecting song popularity, considering co-dependencies and narrowing the search by genre. Surveys and real people's opinions could offer more accurate insights.

## Bibliography
- Mulligan, Mark. “Music Subscriber Market Shares Q2 2021.” MIDiA Research, 18 Jan. 2022. [source](https://www.midiaresearch.com/blog/music-subscriber-market-shares-q2-2021).
- Resler, Seth. “5 Reasons Why It's Important to Teach Popular Music History.” Jacobs Media Strategies, 28 July 2017. [source](https://jacobsmedia.com/5-reasons-why-its-important-to-teach-popularmusic-history/).
