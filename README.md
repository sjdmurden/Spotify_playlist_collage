# Spotify_playlist_collage
 ```diff
Languages used: Python
 ```

 
This code uses the Spotify API (Spotipy) to collate playlist cover images from the input playlists and create a collage of them in a square grid which is then able to be saved as a png file. This function requires a square number of playlists to be inputted, so 1,4,9,16, etc., as a list of string URLs.

See the .ipynb file for the Jupyter Notebook, and I have included an example png output image, using my personal playlists, under the name "official".

The inspiration for this came from looking at how standard Spotify playlist cover images are a square 2x2 grid of four album covers, where the albums are the first four unique albums appearing in the playlist in chronological order. I thought it would be interesting to be able to make a collage of multiple playlist cover images to have as a saveable image for my laptop home screen.

It was my first time using Spotipy and I learnt a lot from experimenting around with what I could do with it. Using the spotipy and urllib packages, I could scrape the web page, and save the cover images, of the inputted playlists URLs. Then with the Pillow packge, I created a square canvas and pasted each downloaded image to create the collage.


