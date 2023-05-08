# Spotify_playlist_collage

This project uses the Spotify Web API (Spotipy) to create a collage of the user's playlist cover images. It is modular, with separate functions for handling authentication, getting playlist data from Spotify, and generating the photo collage which was done with the Pillow library. The result is a PNG file that can be downloaded. Below is an example using my own Spotify playlists.

<img src="https://user-images.githubusercontent.com/109233807/236917794-84ed0d40-95d1-4474-9e53-4e47ccabe82d.png" width="400" height="400" />

The inspiration for this came from looking at how standard Spotify playlist cover images are a square 2x2 grid of four album covers, where the albums are the first four unique albums appearing in the playlist in chronological order. I thought it would be interesting to be able to make a collage of multiple playlist cover images to have as a saveable image for my laptop home screen.

It was my first time using Spotipy and I learnt a lot from experimenting around with what I could do with it. Using the API and urllib packages, I could scrape the web page, and save the cover images, of the inputted playlists URLs. Then with the Pillow packge, I created a square canvas and pasted each downloaded image to create the collage.


