# Music analysis


Link to Dataset (API) : https://wiki.musicbrainz.org/MusicBrainz_API/Search

Link to Lyrics : https://docs.genius.com/#/getting-started-h1 

### Dataset including:
- Artist
- Song name
- Featuring artists
- Popularity score
- Songwriters (artist, composer, lyricist, writer)
- Popularity
- Release_year
- Duration
- Lyrics


### Project disposition:
- Introduction
- Create dataset
    - Find list with titel and artist
    - Fetch composer, lyricist, writer, area, label from MusicBrainz
    - Fetch duration, popularity, release data from spotify
    - Fetch Lyrics from genius
- Data preprocessing
    - Cleaning
    - Tokenizing Lyrics
- Networks
    -  Network graphs
        - Nodes: songs, links: songwriters
        - Nodes: artists/songwriters, links: songs
    - Community detection
- Exploritory Data Analysis
    - Count of songwriters pr. artists, most shared songwriters etc...
- Lyric analysis
    - Frequency - tf, idf, tf-idf
    - Community lyric comparison
- Discussion
