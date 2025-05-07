# Music analysis


Link to Dataset (API) : https://wiki.musicbrainz.org/MusicBrainz_API/Search

Link to Lyrics : https://docs.genius.com/#/getting-started-h1 

### Dataset including:
- Song name
- Area
- Artist
- Label
- Popularity score
- Work (artist, composer, lyricist, writer)
- Lyrics
Maybe:
- Genre


### Project disposition:
- Introduction
- Create dataset
    - Find list with titel and artist
    - Fetch composer, lyricist, writer, area, label from MusicBrainz
    - Fetch duration, popularity, release data from spotify
    - Fetch Lyrics from genius
- Data preprocessing
    - Cleaning
    - Parsing Lyrics
- Exploritory Data Analysis
    - Extract tokens from lyrics
    - Frequency - tf, idf, tf-idf
    - Lyric sentiment score
    - Correlation
        - Between popularity and sentiment in songs, duration, other atributes
        - Popularity and release date
- Modeling
    - Clustering
        - Network graphs
        - Nodes: tracks, links: artists/songwriters
- Results
    - Summarize
    - Discuss
- Conclusion
- Appendix



### Description