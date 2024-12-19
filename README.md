# Music Player 🎵

A simple and interactive music player web application that lets users play, pause, and skip through songs. The app supports dynamic song selection and includes features like song duration, progress bar, and cover art for each track.


## Features

- **Play, Pause, Next, Previous**: Control playback of songs with easy navigation buttons.
- **Track Progress**: View the progress of the current song with a dynamic progress bar.
- **Song Duration**: See the current time and total duration of the song.
- **Rotating Album Cover**: Enjoy a spinning album cover while the music is playing.
- **Multiple Songs**: Add as many songs as you want, and easily navigate through them.
- **Responsive Design**: The app adjusts to different screen sizes and devices.


## Files Overview

- **index.html**: Contains the structure of the music player interface, including audio player, title, buttons, and cover image.
- **styles.css**: Provides the styling and layout for the app, with animations, background gradients, and responsive design.
- **script.js**: Handles the logic for playing, pausing, switching songs, updating progress, and managing song duration.


## How to Use

1. **Play a Song**:
   - Click the **Play** button to start playing the song.
   
2. **Pause a Song**:
   - Click the **Pause** button (same as the Play button) to stop the song.
   
3. **Skip to Next/Previous Song**:
   - Use the **Next** and **Previous** buttons to navigate between the songs in the playlist.

4. **Song Progress**:
   - The progress bar will update in real-time as the song plays.
   - You can click on the progress bar to skip to a specific part of the song.

5. **Song Duration**:
   - The app displays both the current song's time and its total duration in minutes and seconds.


## Files Description

### index.html

The `index.html` file provides the structure for the music player application:
- Contains the audio player element, which loads a song when selected.
- Includes buttons for controlling the music (Play, Pause, Next, Previous).
- Displays the title of the current song and album cover.
- Embeds a progress bar and time display to show the current position of the song.

### styles.css

The `styles.css` file adds styling to the music player:
- A modern and responsive design with a gradient background.
- Animates the album cover to spin when a song is playing.
- Includes smooth hover effects for buttons and elements.
- Styled with flexibility in mind, so the player is visually appealing across devices.

### script.js

The `script.js` file contains the app's main functionality:
- Handles music playback (Play, Pause, Next, Previous).
- Updates the progress bar and time display in real-time.
- Switches between songs in the playlist when the "Next" or "Previous" buttons are clicked.
- Ensures smooth song transitions when a song ends.


## How to Run

1. **Download or Clone the Repository**:
   - Download or clone this repository to your local machine.

2. **Open the `index.html` File**:
   - Open the `index.html` file in your web browser to use the Music Player.

3. **Add More Songs**:
   - Add songs to the `music/` directory and their corresponding images to the `images/` directory.
   - Update the song list in the `script.js` file.


## Technologies Used

- **HTML**: Used for the structure of the music player.
- **CSS**: Provides the styling, layout, and animations for the music player.
- **JavaScript**: Handles the logic for song playback, controls, and dynamic updates.


## License

This project is open-source and available under the MIT License. See the [LICENSE](LICENSE) file for more details.


## Acknowledgments

- Inspiration for the design comes from modern music player interfaces.
- Built to offer a simple yet interactive way of listening to music in the browser.
