# SoundCloud Tracklist Archive

sc playlist description char limit is 4000 and some tracks may dissapear over time so.. here is a data backup



### Method to download a text list of tracks using [yt-dlp](https://github.com/yt-dlp/yt-dlp) (fork of [youtube-dl](https://github.com/ytdl-org/youtube-dl)) 
> • yt-dlp -a SETLIST.txt --default-search ytsearch --download-archive downloaded_mp3.txt -x --audio-format mp3
> 
> • yt-dlp -o "%(title)s.%(ext)s" -a SETLIST.txt --default-search ytsearch --download-archive downloaded_opus.txt --no-post-overwrites --embed-thumbnail --embed-metadata --parse-metadata "%(autonumber)03d:%(track_number)s" -x --audio-format opus 



*artist/title cleaned thx to touchdesigner + python*
