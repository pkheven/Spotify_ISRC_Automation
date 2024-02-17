# Spotify_ISRC_Automation

This small script that allows you to automate the process of searching ISRC codes for songs with spotify sharing links.
Using the website https://www.isrcfinder.com, the playwright codegen and spotypy package you can extract relevant track information
including Track Name, Artist, Track_ID, Sharing Link and ISRC. 

After finishing the operation the programm returnss a csv file with the information

## IMPORTANT:
get your own client_id and secret with this: https://www.youtube.com/watch?v=G14OsI6PZR8

Once you have your own spotify credentials insert a playlist_id which is in the sharinglink

### example: 
sharing_link = https://open.spotify.com/playlist/1URvJKNZ2koMLyreqhyZO5?si=d696b13a3d6d4df0
cool playlist

playlist_id = 1URvJKNZ2koMLyreqhyZO5
