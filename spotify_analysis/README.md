## Visualizing Spotify Streaming Data with Python & Tableau

A Python and Tableau-based project about analyzing and visualizing my Spotify streaming data from January 2025 to October 29th 2025. 

### Overview
- Goal: Summarize streaming habits and surface high-level trends in artists, genres, and streaming behavior.
- Stack: Python (pandas & spotipy), data visualization libraries, static site via GitHub Pages.

### Dataset
- Source: Spotify personal streaming history (exported from Spotify).
- Included: N/A

I will not be including my streaming data due to privacy concerns. You can request a copy of your own data from Spotify to follow along with the notebook. 

### Methods
- Preparation: Parsing JSON exports, timestamp normalization, feature derivation (counts, rankings).
- Analysis: Aggregations by artist, track, genre, and time.
- Visualization: Bar charts and summary visuals designed to mirror Spotify Wrapped themes.

### Results
- Top artists and tracks by total plays.
- Clear concentration in streaming behavior across a small subset of artists.
- Temporal streaming patterns visible across the year.
- Interactive/static visuals embedded in the project site.

### How to Run
1. Export your Spotify streaming history.
2. Process data using the analysis notebook.
3. Generate visual outputs and deploy via GitHub Pages.

### Structure
- `notebooks/`: analysis and aggregation
- `visualization/`: charts and rendered outputs


### Next
- Add artist map, indicating geographic locations of top artists. 
- Incorporate audio feature analysis (energy, tempo, valence).

### License
GNU GPL v3
