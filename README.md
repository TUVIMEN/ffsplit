# ffsplit
A shell script for splitting albums.

## Requirements

 - ffmpeg

## Example
	ffsplit album.webm artist album 2010 ogg -c:a libopus -b:a 64k

inside $EDITOR:

	00:03:02 First track
	00:08:39 Second track
	00:11:24 Third track
	00:16:03 Fourth track
	00:22:55 fifth track

created files:

	01-first-track.ogg
	02-second-track.ogg
	03-third-track.ogg
	04-fourth-track.ogg
	05-fifth-track.ogg

## Instalation
	git clone 'https://github.com/TUVIMEN/ffsplit'
	cd ffsplit
	sudo install -m 755 ffsplit /usr/bin
