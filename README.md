# jukeboxx
a jukebox that plays music from a yt music playlist 

<img width="1919" height="994" alt="image" src="https://github.com/user-attachments/assets/7fb08135-6020-4bf1-875b-59ab255a7e9c" />


## Features

* **Audio & Album Art Playback**: Streams audio in the background via a hidden YouTube IFrame player while dynamically extracting and displaying album artwork (`hqdefault.jpg`).
* **Queue Management**: Add individual tracks (by video ID or full URL), load full playlists, reorder/remove songs, and navigate tracks (`prev`, `skip`).
* **Responsive Controls**: Intuitive playback controls including play, pause, skip, and volume adjustment.
* **Local & URL Parsing**: Smart helper functions to automatically parse out 11-character video IDs and playlist IDs (`PL...`) from raw inputs or full YouTube URLs.

## Getting Started

1. Clone or download this repository to your local machine.
2. Localhost `index.html` directly in any modern web browser.

## Built With

* HTML5 & CSS3
* JavaScript (ES6)
* YouTube IFrame Player API & oEmbed Service
