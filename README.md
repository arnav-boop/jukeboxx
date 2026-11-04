# jukeboxx
a jukebox that plays music from a yt music playlist 

## Features

* **Audio & Album Art Playback**: Streams audio in the background via a hidden YouTube IFrame player while dynamically extracting and displaying album artwork (`hqdefault.jpg`).
* **Queue Management**: Add individual tracks (by video ID or full URL), load full playlists, reorder/remove songs, and navigate tracks (`prev`, `skip`).
* **Responsive Controls**: Intuitive playback controls including play, pause, skip, and volume adjustment.
* **Local & URL Parsing**: Smart helper functions to automatically parse out 11-character video IDs and playlist IDs (`PL...`) from raw inputs or full YouTube URLs.

## Getting Started

1. Clone or download this repository to your local machine.
2. Localhost `jookboxx` directly in any modern web browser.

## Built With

* HTML5 & CSS3
* JavaScript (ES6)
* YouTube IFrame Player API & oEmbed Service
