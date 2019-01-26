# Spotify-Song-Recommender
Analyzing attributes of the songs in your library and automatically adding recommended songs from a given playlist back to your library.

Contributors:
Mohnish Chakravarti
Anant Majumdar

Methods used: k-NN, and a Euclidean distance-based approach where we check if the value of the song's attributes fall within a certain range of your playlist's average.

Note: You need to register yourself with Spotify's API to get your own client ID, client secret and set a redirect uri for yourself. Go to https://developer.spotify.com/dashboard/applications/ for more info

You also need to make a playlist of disliked songs for this to work (you can also pick a random playlist of songs that you generally don't like). We assume your list of saved songs to be your playlist of liked songs
