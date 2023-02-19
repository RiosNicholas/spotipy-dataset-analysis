# spotipy-dataset-analysis
### <i>DATA SCIENCE FINAL PROJECT FOR RUTGERS UNIVERSITY–NEWARK COURSE, <ins>EVERYDAY DATA</ins></i>
Team Members: Nicholas Rios, Victor Armani, Jaevon Lawrence, Adam Abrahim, Domenica Torres
***

## BACKGROUND ABOUT DATASET:
- 44894 rows & 21 columns of data consisting of information about hit/flop tracks fetched using Spotify's Web API 
  - Dataset includes tracks ranging from the 1960s to the 2010s.
  - Our focus was narrowed down to tracks ranging from the 1960s to the 2010s.
- Our target variable is 'valence', and we are only looking at hit tracks (under 'target' variable labeled as 1).
- Columns describe musical elements of each track, unique identifiers, and whether a song is a "hit" or a "flop" (under the 'target' column).** 
  - <i>These terms are not a subjective description of a track's quality, but rather of its popularity in the mainstream, and of its fulfillment of particular requirements.</i>
***

## BUSINESS PROBLEM: 
- <b>Testable Hypothesis: Hit tracks in the US Spotify library that were released between the years 2000 and 2019 have decreased in happiness measured in valence by 30%.</b>
- <b>Alternate Hypothesis</b>: Hit tracks in the US Spotify library that were released between the years 2000 and 2019 have not decreased in happiness measured in valence by 30%. 

Our target variable is the valence of hit songs in the US Spotify library that were released between the years 1960 and 2019. Valence is a value between 0 and 1, and we decided that valence values that are at least .6 will be considered happy while those less than .4 are considered unhappy/somber. We will target this data using Python by comparing 'valence' data in the time range among hit songs. 
