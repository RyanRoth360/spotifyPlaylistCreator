Spotify Playgen

Spotify Playgen is a Python application built with tkinter and Spotipy that allows users to create playlists in their Spotify account based on their top artists, top songs, and recently played songs.

Features
Login: Users can log in to their Spotify account using their credentials and authenticate the application.

Top Artists: Users can choose to create a playlist based on their top artists. The application will retrieve the user's top artists from Spotify and display them in a list. The user can select one or more artists to create a playlist.

Top Songs: Users can choose to create a playlist based on their top songs. The application will retrieve the user's top songs from Spotify and display them in a list. The user can select one or more songs to create a playlist.

Recently Played: Users can choose to create a playlist based on their recently played songs. The application will retrieve the user's recently played songs from Spotify and display them in a list. The user can select one or more songs to create a playlist.

Playlist Creation: Once the user has selected the artists or songs they want to include in their playlist, they can create the playlist in their Spotify account. The application will create a new playlist with the selected tracks and give it a name chosen by the user.

Installation

1. Clone the repository using the following command:
   git clone https://github.com/RyanRoth360/spotifyProject.git

2. Install the required dependencies using the following command:
   pip install -r requirements.txt

3. Install the following third party libraries by using the following commands:
   pip install spotipy
   pip install tkinter
   pip install spotipy.oauth2

4. Before you can use Spotify Paygen, you'll need to set up a Spotify developer account and create a new Spotify application. Once you've done that, you can enter your Spotify application credentials into the cred.py file in the root directory of the application. https://developer.spotify.com/

License
The Spotify Playlist Creator is released under the MIT License. See the LICENSE file for more information.
