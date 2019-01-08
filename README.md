# silver-surf
A customized clone of a WebKit based browser called surf by suckless, patched with homepage and searchengines.
	'Ctrl-g' to bring up dmenu url bar
	preface a keyword with 'g' to google search: 'g youtube'
	edit HOMEPAGE definition in config.h to your desired homepage and then recompile

# Screen

![Screenshot](https://github.com/ZmanSilver/silver-surf/blob/master/screen.png)

## Dependencies

The webkit2gtk, gcr, and xorg-xprop packages are required to run.

dmenu is required for url bar and search.
st is the default terminal for the download handler.
curl is the default download handler.
mpv is the default video player.

## Installation

	sudo make install

## Uninstalling

	sudo make clean uninstall
