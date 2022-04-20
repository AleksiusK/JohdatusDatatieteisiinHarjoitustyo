# Creating recommendations to a playlist
aleksius.kurkela@tuni.fi
274550
***

Creating a good, thematic playlist in spotify has always been difficult for me. The playlists I make end up having songs that don't fit, and ruin a perfectly good workout or study session as I have to skip songs that I don't want to hear. This is why I decided to see if building a ML model, that recommends types of songs to an existing playlists would be possible to make.

The project is built around four main sections:
1.  Gathering the data from Spotify using Spotipy, a python library that allows you to use Spotifys' Web api.
2. Preprocessing the data to a format that we can use while at the same time providing insight to the data. 
3. Building a clustering models with DBSCAN and BIRCH wich aims to categorize songs based on their attributes.
4. Using the model created to cluster songs in a playlist, and recommending songs most similar to the ones in it.

The project workflow follows the CRISP-DM model, and is built in Azure ML Studio.