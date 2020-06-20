# WebPlayerAJ 

Created by Antoni Jankowski.

## Why?

This little project is a simple use of [hls.js](https://github.com/video-dev/hls.js) library. It's part of the Multimedia Information Processing and Communications class at AGH University.

**DISCLAIMER**

I know it's ugly, I'm no UI designer, pardon me.

## Functionality

1. HSL playback: choose one of the 5 most viewed HLS test playlists!
2. Displays current HLS info:
	* bitrate
	* height
	* width
	* video/audio codecs
	* hls.level index
	* playlist level url

**BONUS FUNCTIONALITY**

3. Displays all the URLs being requested by the player "on-the-fly".

	In fact, what you'll see are the urls to the *ts* segments being parsed by the player at the moment.

## How to launch the WebPlayerAJ?

I recommend using simple python server to display the project.
It's enough for the purpose and It's the one I use.

```sh
$ python3 -m http.server
```
