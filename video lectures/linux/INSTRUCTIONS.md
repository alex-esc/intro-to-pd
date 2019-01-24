# Download the video lectures on Linux

1. Install youtube-dl.
2. Decide what mirror to use.
3. Run the corespondent command.


## install youtube-dl

First you need to install youtube-dl to download the videos in batch.

### Install from Software repo

	sudo apt-get install youtube-dl

### Install from pip

	sudo pip install youtue-dl

After youtube-dl is installed you can proceed:


## Choose what mirror to download

There are 3 different ways to download the video lectures, you could download from YouTube or from the original source, open the terminal and continue.

### How to download from source, best quality.

Run the next command in the terminal.

	youtube-dl -ci --batch-file=download-from-source-url-list.txt

### How to download from YouTube, worst quality.

On YouTube two users have mirrored the lectures on two playlists, we can use either of those playlist to download the files, place the following text in the terminal.


#### To download from YouTube user sqdr

	youtube-dl https://www.youtube.com/playlist?list=PLdZadTeiAR0khkY1Lk-XVNpIDuhMg8wOI

#### To download from YouTube user toitoitoy

	youtube-dl https://www.youtube.com/playlist?list=PLRjUk6Y71rvRQa95tqspy5fdI23ReD1Cv