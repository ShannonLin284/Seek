# Seek

Seek is a music discovery project designed to identify emerging artists whose sound is similar to popular artists or to a user’s listening preferences. The system analyzes audio features from the Spotify Web API, applies dimensionality reduction, and uses clustering techniques to reveal underexposed artists in acoustic feature space.

# Overview

Seek constructs numerical representations of songs using Spotify audio features, reduces the feature space with PCA, and applies clustering algorithms such as HDBSCAN and K-Means. Clusters containing both popular and emerging artists are flagged as discovery regions. A simple recommendation component suggests emerging artists based on proximity to a user’s favorite artists.

# Features
- Audio feature extraction from the Spotify Web API
- PCA-based dimensionality reduction
- Clustering with HDBSCAN and K-Means
- Identification of emerging artists near popular artists
- Basic recommendation logic based on cluster proximity

# Resources
Python, Spotify Web API, NumPy, Pandas, Scikit-learn, HDBSCAN, Matplotlib

# Acknowledgments
This project was completed for ASTRO 4523 under the guidance of Professor Shami Chatterjee.
