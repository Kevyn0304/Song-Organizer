# Song-Organizer
A Spotify Web App that will organize all of the songs in my Liked Songs playlist to playlists specified for certain genres

For example:

| Playlist title | Genre |
| -------------- | ----- |
| metal | metal |
| punk/rock | punk, garage rock|
| アニメ | jpop|

etc

```
for (song in Liked Songs):
  get(song.genre)
  if (song.genre == metal)
    metal_playlist.add(song)
  elif (song.genre == jpop)
    アニメ.add(song)

    and so on
```


Next projects:
- Webapp thats always running to automatically sort any songs added to my Liked Songs playlist
- Actual website desgined for people to insert a given playlist of theirs, and ask them questions to add or remove certain genres and suggest such songs
