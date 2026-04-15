# Spotify tracks analysis

I wanted to find out what actually makes a song popular on spotify, does it have to be danceable? Loud? Happy? It turns out that the answer is more interesting than I expected

## What I used
- Python, pandas, matplotlib, seaborn
- Dataset: 114,000 Spotify tracks from Kaggle

## What I found
1. **How a song sounds barely predicts how popular it gets** 
none of the audio features had a strong correlation with popularity. The biggest factor was loudness and even that was 0.05. Stuff like artist fame and playlist placement probably matters way more.

2. **Pop-film and K-pop are the most popular genres**
Soundtrack music from movies and TV ranked #1, Pop-film and K-pop came in at #2 with the highest danceability of any genre.

3. **Sad songs actually do better than happy ones**
I expected happy upbeat songs to perform best but the data showed the opposite. Melancholic songs consistently score higher on Spotify.

4. **High energy doesn't mean popular**
grunge had the most energy of any genre but only ranked 5th in popularity. Energy alone doesn't make a hit.

##  Summary
I cleaned and analyzed 114,000 rows of real data, built a correlation heatmap, a genre comparison bar chart, and a scatter plot of every song in the dataset.
