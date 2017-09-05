# Spotify Lyrics
Fetches and displays lyrics to currently playing song in the Spotify desktop client.

# how to
You can grab the latest release exe in the [release section](https://github.com/fr31/spotifylyrics/releases).

Just double click and start playing songs in spotify. 

If you get an error about api-ms-win-crt-runtime-l1-1-0.dll missing, you need this:

https://www.microsoft.com/en-us/download/details.aspx?id=48145

# running from source
If you want to run from source you need:

* Python 3.6.2 (probably any version of Python 3)
* pip install -r requirements.txt
* Windows: pip install pypiwin32 or [pywin32](https://sourceforge.net/projects/pywin32/) (included in anaconda 4 [*](https://github.com/fr31/spotifylyrics/issues/5))
* Linux: xwininfo (comes with ubuntu)

# screenshot
![example-img](https://i.imgur.com/51umyjo.png)
