Type Runner 2.0 by Meheraz - Documentation

Overview

Type Runner 2.0 is a web-based typing game designed to help users improve their typing speed and accuracy. The game presents players with random paragraphs to type, tracks their performance metrics (such as WPM, CPM, and mistakes), and offers various modes and settings to enhance the experience. This project is a work in progress, with plans for additional features to make the game more engaging and user-friendly.

Features





Random Paragraphs: Players type randomly selected paragraphs from a predefined list.



Performance Metrics:





Time Left: A countdown timer (default: 100 seconds) to complete the typing challenge.



Mistakes: Tracks the number of incorrect characters typed.



WPM (Words Per Minute): Measures typing speed based on correct characters typed.



CPM (Characters Per Minute): Counts the number of correct characters typed.



Typing Modes:





Normal Mode: Paragraphs include uppercase letters and punctuation.



Simple Mode: Paragraphs are converted to lowercase with punctuation removed.



Sound Toggle: Option to enable or disable typing sound effects.



Retry Option: A "Try Again" button to restart the game with a new paragraph.



Responsive Design: The game adapts to different screen sizes for a consistent experience on desktop and mobile devices.



Accessibility: Includes ARIA attributes for screen reader support.

File Structure

The game consists of three main files:





index.html:





The main HTML file that defines the structure of the game.



Contains the game title, typing area, input field, performance metrics, and buttons (Mode, Sound, Retry).



style.css:





The CSS file that styles the game.



Defines the layout, colors, typography, and responsive design for various screen sizes.



Uses custom properties (CSS variables) for maintainability.



typing_test.js:





The JavaScript file that handles the game logic.



Manages paragraph loading, user input, timer, performance metrics, mode switching, sound toggling, and game state.

Usage Instructions





Starting the Game:





Open the game in a web browser.



A random paragraph will be displayed in the typing area.



Click on the typing area or press any key to focus the input field and start typing.



Typing:





Type the displayed paragraph as accurately and quickly as possible.



Correct characters are highlighted in yellow, and incorrect characters are highlighted in red.



The timer starts automatically when you begin typing.



Monitoring Performance:





The stats bar displays:





Time Left: Remaining time in seconds.



Mistakes: Number of incorrect characters typed.



WPM: Your typing speed in words per minute.



CPM: Number of correct characters typed.



Stats update in real-time as you type.



Modes:





Click the "Mode: Normal" button to toggle between Normal Mode (with uppercase and punctuation) and Simple Mode (lowercase, no punctuation).



The game resets automatically when switching modes.



Sound:





Click the "Sound: On" button to toggle typing sound effects on or off.



Restarting:





Click the "Try Again" button to reset the game with a new paragraph.

Work in Progress

This game is actively being developed. The following features and improvements are planned:





Pause/Resume Functionality: Add a button to pause and resume the timer during gameplay.



High Score Tracking: Save and display the user’s best WPM score using localStorage.



Difficulty Levels: Introduce easy, medium, and hard modes with varying paragraph complexity or time limits.



Custom Time Limit: Allow users to set their own time limit before starting the game.



Progress Bar: Add a visual progress bar for the timer or typing progress.



Theme Toggle: Implement a light/dark theme switcher for better user customization.



Improved Accessibility: Enhance ARIA support and keyboard navigation for better accessibility.

Known Issues





The game is still being refined, and some features may have minor bugs.



Performance metrics may require further tweaking for accuracy in edge cases (e.g., rapid typing or backspacing).

Notes
