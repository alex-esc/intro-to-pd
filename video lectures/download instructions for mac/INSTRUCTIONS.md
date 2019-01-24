# Download the video lectures on Mac

1. Open the terminal.
2. Install Homebrew.
3. Install youtube-dl.
4. Open terminal on desired download location.
5. Decide what mirror to use.
6. Run the corespondent command.


## How to open the terminal.

Click on the 'search icon' on the top right corner of the screen, the icon looks like a *magnifying glass*, once you click it a search bar will appear, on it type 'terminal' and hit enter, the terminal should now open. 

To download the video lectures we need a program not available on the mac app store, the program is called 'youtube-dl' and it's available on the terminal based app store called 'homebrew', so first we must install homebrew.

## install Homebrew

Inside your terminal paste the following string of code and hit enter.

	/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

Once the process is done you can exit out of the terminal.

## install youtube-dl

Open another terminal and paste this command, press enter.

	brew install youtube-dl

So far we have opened the terminal and used it inside the default directory, now to download the video lectures on a different folder will need to open the terminal inside our desired folder.

To open the terminal on a specific folder we need to enable this feature.


## Enable New Terminal at Folder

Click on the Apple icon on the top bar and click 'System Preferences', then choose 'Keyboard', click on the 'Shortcuts' section, a list will appear on the left, on it click on 'services', now you need to look for 'New Terminal at Folder' on the right, it's inside 'Files and Folders' and click on the check box.

> System Preferences > Keyboard > Shortcuts > Services > Files and Folders > Check "New Terminal at Folder"

## Choosing download location

Navigate with *finder* to the folder you want the video lectures inside, placing the inside the 'video lectures' folder from this repository is recommended.

Once you are on your desired folder: Click on 'finder' at the top bar, select 'services' and choose 'New terminal at folder', a terminal on this folder will open.

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