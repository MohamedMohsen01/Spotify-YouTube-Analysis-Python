<h2>Project Name :</h2> Spotify and YouTube Data Analysis

<h4>Dataset  link </h4>: https://www.kaggle.com/datasets/salvatorerastelli/spotify-and-youtube
<h3>Overview : </h3>
The Spotify and YouTube Data Analysis project aims to gain insights into music streaming trends and artist performance by analyzing data from both platforms. Through an extensive Exploratory Data Analysis (EDA), this project explores the relationship between views, likes, streams, and other variables to uncover interesting patterns and provide actionable insights for music streaming platforms, artists, and enthusiasts.



## Cases & Features Interpretability

1. Track: name of the song, as visible on the Spotify platform.
2. Artist: name of the artist.
3. Url_spotify: the Url of the artist.
4. Album: the album in which the song is contained on Spotify.
5. Album_type: indicates if the song is relesead on Spotify as a single or contained in an album.
6. Uri: a spotify link used to find the song through the API.
7. Danceability: How suitable a track is for dancing (0.0 = least danceable, 1.0 = most danceable).
8. Energy: Intensity and activity of a track (0.0 - 1.0). Energetic tracks feel fast, loud, and noisy.
9. Key: The track's musical key (-1 if not detected).
10. Loudness: Overall loudness of a track in decibels (dB) (-60 to 0 dB).
11. Speechiness: Presence of spoken words in a track (0.0-1.0). Higher values indicate speech-like content.
12. Acousticness: Confidence measure of track's acoustic nature (0.0-1.0).
13. Instrumentalness: Likelihood of a track containing no vocals (0.0-1.0).
14. Liveness: Presence of an audience in the recording (0.0-1.0). Higher values indicate live performance.
15. Valence: Positiveness conveyed by a track (0.0-1.0). High valence = positive, low valence = negative.
16. Tempo: Estimated tempo of a track in beats per minute (BPM).
17. Duration_ms: Duration of the track in milliseconds.
18. Streams: Number of streams of the song on Spotify.
19. YouTube URL: URL of the video on YouTube (if available).
20. Title: Title of the video clip on YouTube.
21. Channel: Channel name that published the video.
22. Views: Number of views.
23. Likes: Number of likes.
24. Comments: Number of comments.
25. Description: Description of the video on YouTube.
26. Licensed: Indicates whether the video represents licensed content.
27. Official Video: Indicates if the video is the official video of the song (boolean value).

<h3>Project Highlights</h3
📌 Imported essential libraries such as pandas, numpy, matplotlib, and seaborn to facilitate efficient data processing and analysis. <br>📌
Meticulously loaded and prepared the dataset, ensuring data quality and integrity for comprehensive analysis.  <br>📌
Engaged in initial data exploration during the EDA phase to gain a profound understanding of the variables and their distributions. <br>📌
Employed effective data cleaning techniques to handle missing values, outliers, and inconsistencies, ensuring precise and reliable analysis.  <br>📌
Presented captivating data visualizations using matplotlib and seaborn to unveil hidden patterns and trends in the Spotify and YouTube data.  <br>📌
Derived meaningful conclusions from the analysis, providing valuable insights into artist popularity, likes, views, streams, album types, and correlations between variables.
 <h2>Insights : </h2>
Based on the Spotify and YouTube Data Analysis, the following intriguing insights were derived:

 <br>📌The artist "Macklemore & Ryan Lewis" secured the highest number of views, amassing a staggering 10.23 billion views. They were closely followed by "Justin Bieber" in second place with 10.12 billion views and "BTS" in third place with 10 billion views. <br>📌
"BTS" emerged as the most liked artist, accumulating a whopping 14 million likes. "Blackpink" secured the second position in terms of likes. In terms of streams, "Post Malone" claimed the first position with 1.2 billion streams, closely trailed by "Ed Sheeran" with 1.74 billion streams. <br>📌
The most popular album type was "Album," representing 75% of the total data, surpassing compilation and single types. <br>📌
The album "Album Vida" received the highest number of likes, accumulating 120 million likes. "See You Again" and "The Heist" secured the second and third positions, respectively, with 80 million and 74 million views. <br>📌
The album "BE" stood out as the most commented album, followed by "Map of the Soul." Interestingly, a higher number of comments implies a lesser-known album.  However, "Vida" defied this trend by amassing higher likes while also being the most commented song, garnering a positive response. <br>📌
A correlation between speechiness and tempo was evident. Songs with faster tempos tended to exhibit a higher level of speechiness. <br>📌
Songs with a higher level of speechiness often possessed a lower level of instrumentalness, reflecting the emphasis on lyrics and vocal delivery in spoken word or rap.

<h2>Conclusion</h2>
The Spotify and YouTube Data Analysis project provides valuable insights into music streaming trends and artist performance. Based on the analysis of the provided data, the following conclusions can be drawn:

<br>📌Artist Popularity: "Macklemore & Ryan Lewis" emerged as the most viewed artist, amassing a staggering 10.23 billion views. "BTS" secured the highest number of likes with 14 million likes. "Post Malone" claimed the top position in terms of streams with 1.2 billion streams. These findings highlight the popularity and influence of these artists in the music streaming landscape.

<br>📌Album Types: The majority of the data (75%) corresponds to the "Album" type, indicating that albums are the preferred form of music consumption among users. This insight can guide music platforms and artists in prioritizing album releases and promotional efforts to cater to user preferences.

<br>📌Likes and Comments: "Album Vida" received the highest number of likes, accumulating 120 million likes. Additionally, it stood out as the most commented album, indicating strong engagement and positive feedback from users. These findings suggest that "Album Vida" has resonated well with the audience and has generated significant user interaction.

Speechiness and Instrumentalness: A correlation was observed between speechiness and tempo, where songs with faster tempos exhibited a higher level of speechiness. Furthermore, songs with higher speechiness tended to have a lower level of instrumentalness. This implies that genres or styles emphasizing vocal delivery, such as spoken word or rap, tend to have faster tempos and lower emphasis on instrumental elements.

In conclusion, the Spotify and YouTube Data Analysis project provides valuable insights into artist popularity, album preferences, user engagement, and musical characteristics. These insights can be leveraged by music streaming platforms, artists, and marketing teams to make informed decisions regarding content promotion, audience targeting, and playlist curation.
