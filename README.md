# Song-Organizer
A Spotify Web App that will organize all of the songs in my Liked Songs playlist to playlists specified for certain genres

For example:

| Playlist title | Genre |
| -------------- | ----- |
| metal | metal |
| punk/rock | punk, garage rock|
| アニメ | jpop|

etc


for (song in Liked Songs):
  get(song.genre)
  if (song.genre == metal)
    metal_playlist.add(song)
  elif (song.genre == jpop)
    アニメ.add(song)

    and so on
