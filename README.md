# <img height="150px" src="https://raw.githubusercontent.com/Xen0phobe/Chess-Game-Visualizer/master/readme-resources/disappointmentRook.svg?sanitize=true" width="150px"></img>The Chess Game Visualizer README
![General screenshot](https://github.com/Xen0phobe/Chess-Game-Visualizer/blob/master/readme-resources/Screen%20Shot%202019-02-28%20at%2011.32.32%20AM.png?raw=true)
## About
The Chess Game Visualizer (CGV) is a free-to-use program hosted on https://printchessgames.com, designed to turn Portable Game Notation (PGN) into pictures of the game. CGV was written using HTML5, JavaScript (vanilla), and Node.js (zero dependencies) by Taylor Lovell Shockey in February, 2019 as a solution to a problem he noticed while working as a chess instructor.
> ### How does a chess instructor provide individualized feedback on games to a classroom of kids in a printed format that is clean, compact, and easy to understand?

## Example
To view an example game outlining the various features of CGV:
1. Go to https://printchessgames.com.
2. Click the "example" button in the top menu.
3. Wait for the PGN to be processed by the server and then scroll-down to see the results.

<img height="50%" src="https://github.com/Xen0phobe/Chess-Game-Visualizer/blob/master/readme-resources/ShamefulAssuredFallowdeer-size_restricted.gif?raw=true"></img>

## Features
* Capable of parsing unlimited nested deviations (please don't crash my server).
* Deviations can be toggled between indented pictures or flat text at the user's discretion.
* Command Strings (arrows, circles, evaluations, and clocks) and Numeric Annotation Glyphs (NAGs) are automatically rendered.
* Graphics can be toggled to better facilitate printing in black-and-white.
* Lichess URL's for studies and games are automatically fetched and the PGN parsed.
