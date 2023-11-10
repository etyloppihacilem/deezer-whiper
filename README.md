# Deezer whiper
A Python script to whipe clean your deezer account, but backup everything before.
Loved tracks, saved albums, loved artists, saved and created playlists : all gone (but still saved as json for playlists thanks to [yfe404](https://github.com/yfe404) and csv with deezer ids for the rest !)

Forked from [yfe404/deezer-backup](https://github.com/yfe404/deezer-backup).

## Disclaimers
***Use at your own risks***. I can not be held responsible to the consequences of this script on your account.

***Only use on your own account***. This is supposed to make sens.

## Usage
Create a deezer app as very well described on [yfe404/deezer-backup](https://github.com/yfe404/deezer-backup) github.
Run script and press *y* then *enter* after the script detected and saved all of your content.

## Info
Albums, artists, loved tracks saved as csv :
- albums.csv
- artists.csv
- tracks.csv

like
```
7561772
1809784247
964226972
...
```
Where each line is an id of loved content that is deleted.
