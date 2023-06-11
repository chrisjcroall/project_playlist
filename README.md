# project_playlist

![Screenshot 2023-06-11 144546](https://github.com/chrisjcroall/project_playlist/assets/126267745/029c375c-adc2-4463-a845-9cfd12c3a687)

The provided code demonstrates how to create Spotify playlists based on song clusters using the Spotipy library, which is a Python wrapper for the Spotify Web API. It first authenticates the user using Spotify API credentials and initializes a Spotify client. The code then iterates over unique cluster IDs in a DataFrame containing song data. For each cluster, it creates a new playlist on Spotify, adds representative songs from that cluster to the playlist, and prints the number of songs added. The code allows users to organize their music into curated playlists based on clustering analysis, providing a convenient way to explore and enjoy music with similar audio features. 
