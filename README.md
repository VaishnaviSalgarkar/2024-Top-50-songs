#Top 50 Songs of 2024 (Conceptual)

This repository contains a conceptual dataset of the top 50 songs on Spotify in 2024. 

**Disclaimer:**

This data is for illustrative purposes only and may not reflect the actual 2024 Spotify Top 50. 
Please refer to official sources for accurate data.

**Data Dictionary:**

* `rank`: Rank of the song on the chart.
* `song_name`: Name of the song.
* `artist`: Artist(s) of the song.
* `album`: Album the song belongs to.
* `release_date`: Release date of the song.
* `duration_ms`: Duration of the song in milliseconds.
* `popularity`: Spotify's popularity score for the song (0-100).

**Analysis (in `analysis/analyze_songs.py`)**

The `analyze_songs.py` script includes a basic analysis of the data:

* Calculates the average song duration.

**To Use:**

1. **Obtain Actual Data:** Replace the sample data in `data/top_50_songs_2024.csv` with the actual 2024 Spotify Top 50 songs list.
2. **Run Analysis:** Execute the `analyze_songs.py` script to perform the analysis.

**Note:**

This is a basic example. You can expand on this by adding more sophisticated data analysis, visualizations, and features to this repository.

**Copyright and Licensing:**

Be mindful of copyright and licensing restrictions when using and sharing music data.
