# Intro to HTML, CSS, and JavaScript

## Overview of Core Web Technologies: HTML, CSS, and JavaScript
Web pages and applications rely on **HTML**, **CSS**, and **JavaScript** to structure, style, and add functionality to content. Here's how these technologies work together, illustrated through two examples: a digital clock and an interactive video player.

### 1. Digital Clock Example

#### Purpose
- A web page that displays a digital clock, updating every second.

#### Files Involved
1. **HTML (clock.html)**:
   - Defines the structure of the web page.
   - Contains elements for hours, minutes, and seconds.
   - Without CSS or JavaScript, displays plain, unstyled content like `00:00:00`.
2. **CSS (styles.css)**:
   - Adds styling such as position, size, colors, font type, and background.
   - Enhances the visual presentation of the clock.
3. **JavaScript (clock.js)**:
   - Dynamically updates the time every second.
   - Ensures the clock shows the current hour, minute, and second in real time.

#### Process
1. **HTML** provides the content structure (e.g., `00:00:00` for the clock).
2. **CSS** styles the content, making it visually appealing and properly positioned.
3. **JavaScript** updates the displayed time every second, making the clock functional and dynamic.

### 2. Interactive Video Player Example

#### Purpose
- A web page that plays or pauses a video interactively via a button.

#### Files Involved
1. **HTML**:
   - Contains the structure of the page, including the video element and a Play button.
2. **CSS**:
   - Styles the video player and button, determining their size, position, and appearance.
3. **JavaScript (videoplayer.js)**:
   - Handles interactivity, enabling the Play button to start or stop the video.
   - Changes the button icon between "Play" and "Stop".

#### JavaScript Functionalities
1. Registers a listener on the button to detect clicks.
2. Checks the video state when the button is clicked:
   - **If stopped**:
     - Starts playing the video.
     - Changes the button to a Stop icon.
   - **If playing**:
     - Stops the video.
     - Reverts the button to a Play icon.

#### Process
1. **Initial State**:
   - The video is stopped by default when the user lands on the page.
2. **Clicking the Play Button**:
   - Changes the button to a Stop icon.
   - Starts the video playback.
3. **Clicking the Stop Button**:
   - Changes the button back to a Play icon.
   - Stops the video playback.

### How HTML, CSS, and JavaScript Work Together
1. **HTML**:
   - Provides the structure and content of the web page.
2. **CSS**:
   - Defines the visual appearance and styling of elements.
3. **JavaScript**:
   - Adds interactivity and dynamic behavior to the page.

#### In Both Examples:
- **HTML** references the CSS and JavaScript files.
- **CSS** enhances visual presentation.
- **JavaScript** enables core functionality and user interaction.

These three technologies form the foundation of modern web development.
