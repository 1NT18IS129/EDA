# EDA
Extensive set of variables for each of the songs which made it to the top 200 charts in 35 (+ global) countries between Jan '17 and Dec '20.
The data include:
Country
Songs' specifics (artist, title, single/album, genre, … from Spotify API)
Songs' features (parameters retrieved by Spotify API like Energy, Loudness, …)
Songs' tone (positive/negative/neutral), emotions and topics (computed and normalized by us using different dictionaries)
NB the value for Popularity was computed by us and is NOT the one provided by spotify API, as we found such number biased and depending on time (i.e. a song with very low popularity now could have been very popular in the past, and this is not reflected in Spotify's score).
