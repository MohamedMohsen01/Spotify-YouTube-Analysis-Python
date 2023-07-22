## Project Name:
#### Spotify and YouTube Data Analysis

<h4>Dataset  link </h4>: https://www.kaggle.com/datasets/salvatorerastelli/spotify-and-youtube



## Summary:

In this project, we embark on a journey to unravel the fascinating world of music streaming trends and artist performance. By delving into data from both Spotify and YouTube, we seek to gain valuable insights and shed light on the dynamics that drive the success of artists and songs on these platforms. Through an extensive Exploratory Data Analysis (EDA), we will explore the intricate relationships between views, likes, streams, and other variables, ultimately uncovering captivating patterns and offering actionable insights for music streaming platforms, artists....



## Cases & Features Interpretability:

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




## Methodology:

#### 1. Data Exploration: 
- Explored the dataset's structure, encompassing columns, data types, and data dictionary.
- Identified the relevant business inquiries or objectives from the dataset.

#### 2. Data Pre-processing and Cleaning: 
In data wrangling and cleaning, I performed essential tasks to ensure reliable and usable data. Here are the key steps I took:
- Addressed missing data using python techniques to delete and clean the data .
- Ensured data integrity by searching for and cleaning duplicate records.
- Changed the data types as needed.



## Exploratory Data Analysis (EDA): 
Some of the questions I've answered based on the data:
1. What are the Top 10 Artists with the highest total Streams on Spotify?
2. Retrieve the top 10 Artists with the highest total views on YouTube?
3. Which are the Top 10 Artists with the highest total number of comments?
4. What are the Top 10 Artists with the highest total likes on YouTube?
5. What are the Top 10 Songs with the highest total Streams on Spotify?
6. Retrieve the top 10 Artists with the highest average total views on YouTube and streams on Spotify?
7. Which are the Top 10 Songs with the highest total number of comments on YouTube?
8. Which Songs have the highest total likes on YouTube in the top 10 ranking?
9. How can you retrieve the top 10 Songs with the highest total views on YouTube?
10. Can you provide a list of the Top 10 most liked Songs on YouTube along with their Artists?
11. What are the Top 10 Most Viewed Songs on YouTube along with their Artists?
12. How do the most-watched Songs on YouTube compare to the Songs with the highest total number of Streams on Spotify?
13. Which Album type tends to receive higher views on YouTube?
14. How can you identify the top 10 Albums with the highest number of views on YouTube?
15. Which album has garnered the highest number of comments on YouTube?
16. Which album has received the highest number of Likes on YouTube?
17. What albums have received the highest total number of Streams on Spotify?
18. Can you provide a list of the Top 10 YouTube channels with the highest total number of likes?
19. How can you find the Top 10 YouTube channels with the highest number of Views?
20. What is the distribution of Album Types?
21. What are the Top 10 Licensed Albums on YouTube and Spotify?
22. What is the distribution of the 'official_video' and 'Licensed' features?
23. Can you conduct a comprehensive analysis of different features for the top 10 most viewed songs?
24. How can you visualize the correlation between different numerical variables using a Pairplot?
25. Can you create a histogram to visualize all the important features of Songs?
26. What does the Pairplot of the most important numerical features reveal?
27. Is there any correlation between the features displayed in the matrix heatmap?
28. Are there any relationships between views and likes on YouTube videos with respect to their Album type?
29. How do Likes and Comments relate to the album type of YouTube videos?
30. Is there a correlation between Views and Streams for the analyzed data?
31. Can you explore the correlation between Acoustiness and Energy?
32. Is there a correlation between Energy and Loudness in the Songs data?
33. How does Speechiness correlate with Tempo in the Songs dataset?
34. What is the relationship between Tempo and Key in the Songs dataset?
35. Can you analyze the relationship between Liveness and Speechiness?
36. What is the relationship between Speechiness and Instrumentalness in the Songs data?
37. How are Instrumentalness and Acousticness related to each other?
38. Is there a relationship between Danceability and Energy in the Songs dataset?
49. What is the relationship between Loudness and Energy in the analyzed data?
50. Can you explain the relationship between Valence and Energy in the Songs data?





## Functions and methods used:
- plt.style.use)
- pd.set_option()
- sns.light_palette()
- head()
- tail()
- describe()
- info()
-  nunique()
- isna().sum()
- drop()
- dropna()
- duplicated()
- duplicated().sum()
- groupby()
- sum()
- sort_values()
- plt.subplots()
- plt.title
- set_xlabel()
- set_ylabel()
- sns.barplot()
- xaxis.set_major_formatter()
- yaxis.set_major_formatter()
- ticker.FuncFormatter()
- reset_index()
- lambda function
- plt.pie()
- plt.figure()
- sns.countplot()
- value_counts()
- size()
- df.columns
- agg()
- lineplot()
- xticks()
- sns.pairplot()
- hist()
- corr()
- heatmap()
- sns.scatterplot()
- sns.lmplot()
- sns.jointplot()
- sns.regplot()
- jointplot(kind='resid')
- jointplot(kind='hex')



## Insights

- "Dua Lipa" claimed the top position with an impressive 13.4 billion streams, closely followed by "XXXTENTACION" in second place with 12 billion streams. "Coldplay" secured the third spot with 11 billion streams.
YouTube Views Milestone:
- "Bruno Mars" achieved an incredible milestone, accumulating a staggering 10.23 billion views, securing the top spot. "Macklemore & Ryan Lewis" followed closely in second place with 10.12 billion views, and "Coldplay" took the third spot with 10 billion views.

- "BTS" dominated with an astonishing 39.5 million comments, securing the top spot. "BLACKPINK" came in second place with 19.6 million comments, and "Stray Kids" took the third spot with 8.4 million comments.

- "BTS" emerged as the most liked artist with a whopping 139.4 million likes. "Blackpink" secured the second position with 132.3 million likes, followed by Charlie Puth in the third position with 86.3 million likes.


- The most popular song with the highest total streams on Spotify is "Can't Hold Us (feat. Ray Dalton)" with an impressive 5.2 billion streams. "Happier" followed in second place with over 4.7 billion streams, and "The Middle" took the third spot with 4.5 billion streams.

- "Despacito" claimed the top spot with 101 million likes, followed by "See You Again (feat. Charlie Puth)" in the second position with 80 million likes, and "Boy With Luv (feat. Halsey)" in third place with 55 million likes.

- "Swalla (feat. Nicki Minaj & Ty Dolla $ign)" secured the top spot with an impressive 5 billion views, followed by "Thrift Shop (feat. Wanz)" in second place with 4.5 billion views, and "Something Just Like This" in third place with 4.2 billion views.


- "Albums" dominated the music landscape, representing a significant 75% of the total data, surpassing compilation and single types.

- "The Heist" stood out as the most popular album, receiving the highest number of views on YouTube, with a total of 11.2 billion. "Swalla (feat. Nicki Minaj & Ty Dolla $ign)" and "Hollywood's Bleeding" secured the second and third positions, respectively, with 5.1 billion views each.

- "Album Vida" emerged as the most popular album, receiving the highest number of likes, with a total of 120 million. "See You Again" and "The Heist" followed closely in the second and third positions with 80 million and 74 million likes, respectively.

- "Vida" surprisingly defied the trend, garnering higher likes while also being the most commented song, receiving a positive response.

- "The Heist" stood out as the most popular album, receiving the highest total streams, with an impressive total of 9.7 billion. "Un Verano Sin Ti" and "SOUR" secured the second and third positions, respectively, with 8.4 billion and 8.3 billion streams.


- There was a noticeable correlation between speechiness and tempo in songs. Faster tempos tended to exhibit a higher level of speechiness.

- Songs with a higher level of speechiness often had a lower level of instrumentalness, reflecting the emphasis on lyrics and vocal delivery, particularly in spoken word or rap.



## Conclusion
Through this comprehensive project, we have delved into the fascinating world of music streaming and social media to uncover the remarkable milestones achieved by various artists and songs. 

- "Dua Lipa" firmly claimed the top position with an impressive 13.4 billion streams on Spotify, closely followed by "XXXTENTACION" and "Coldplay" with 12 billion and 11 billion streams.

- On YouTube, "Bruno Mars" achieved an incredible milestone, amassing a staggering 10.23 billion views, securing the top spot, while "Macklemore & Ryan Lewis" and "Coldplay" closely followed with 10.12 billion and 10 billion views, respectively.

- "BTS" emerged as an unstoppable force on the digital stage, dominating with a record-breaking 39.5 million comments, securing the top spot in YouTube comments. Meanwhile, their massive fan following translated into social media popularity, as they emerged as the most liked artist with an astounding 139.4 million likes. "BLACKPINK" and Charlie Puth also gained significant admiration, securing the second and third positions with 132.3 million and 86.3 million likes, respectively.

- Among the top streamed songs on Spotify, "Can't Hold Us (feat. Ray Dalton)" stole the show with an impressive 5.2 billion streams, closely followed by "Happier" and "The Middle" with over 4.7 billion and 4.5 billion streams, respectively.

- On YouTube, "Despacito" reigned supreme, amassing a staggering 101 million likes, with "See You Again (feat. Charlie Puth)" and "Boy With Luv (feat. Halsey)" securing the second and third positions with 80 million and 55 million likes, respectively.

- In terms of YouTube views, "Swalla (feat. Nicki Minaj & Ty Dolla $ign)" captured the top spot with an impressive 5 billion views, followed by "Thrift Shop (feat. Wanz)" and "Something Just Like This" with 4.5 billion and 4.2 billion views.

- Our exploration of album types revealed that "Albums" were overwhelmingly dominant, representing a significant 75% of the total data, outshining compilation and single types.

- Among the top albums on YouTube, "The Heist" garnered the highest number of views, amassing a total of 11.2 billion, with "Swalla (feat. Nicki Minaj & Ty Dolla $ign)" and "Hollywood's Bleeding" securing the second and third positions with 5.1 billion views each.

- On the other hand, "Album Vida" emerged as the most popular album in terms of likes, amassing a total of 120 million, with "See You Again" and "The Heist" closely following in the second and third positions with 80 million and 74 million likes, respectively.

- Notably, "Vida" defied the trend by garnering higher likes while also being the most commented song, receiving a positive response from the audience.

- In the realm of streaming, "The Heist" maintained its popularity, securing the top spot with an impressive total of 9.7 billion streams on Spotify. "Un Verano Sin Ti" and "SOUR" followed closely in the second and third positions with 8.4 billion and 8.3 billion streams, respectively.

- Finally, we explored intriguing correlations between song traits, revealing a noticeable link between speechiness and tempo in songs. Faster tempos tended to exhibit a higher level of speechiness, while songs with higher speechiness often had a lower level of instrumentalness, highlighting the emphasis on lyrics and vocal delivery, particularly in spoken word or rap.

Overall, this project offers valuable insights into the ever-changing music industry, shedding light on the influence of streaming platforms and social media on an artist's success. The data and trends presented here will undoubtedly serve as a valuable resource for understanding the dynamic landscape of music and the preferences of modern audiences.
