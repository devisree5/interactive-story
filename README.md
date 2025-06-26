# Interactive Cinderella Story

![Project Preview](https://img.shields.io/badge/Interactive-Storytelling-blueviolet) 
![Tech Stack](https://img.shields.io/badge/HTML-CSS-JavaScript-yellowgreen)

A choose-your-own-adventure version of the classic Cinderella fairy tale with multiple branching paths and endings, built with pure HTML, CSS, and JavaScript.

## Features

✨ **12+ Unique Endings** - Discover different outcomes based on your choices  
🔄 **Non-linear Storytelling** - Every decision creates new story branches  
🎚️ **Full Navigation Control** - Go back or restart at any point  
📱 **Responsive Design** - Works on desktop and mobile devices  
🔊 **Optional Audio** - Sound effects and background music (can be disabled)  

## How to Play

1. Clone or download the repository
2. Open `index.html` in any modern browser
3. Read the story and make choices by clicking buttons
4. Explore all possible endings!

## Story Structure
📂 root/
├── index.html # Main HTML file
├── style.css # Styling for the application
├── script.js # Core game logic and story data
├── assets/ # (Optional) For audio/image assets
│ ├── sounds/ # Sound effects and music
│ └── images/ # Character and scene illustrations

## Customization Guide

### To modify the story:
1. Edit the `story` object in `script.js`
2. Add/remove/modify story nodes following the pattern:
```javascript
nodeId: {
    text: "Your story text here",
    choices: [
        { text: "Choice 1", next: "targetNode" },
        { text: "Choice 2", next: "anotherNode" }
    ],
    ending: "Optional ending message"
}
Technical Details
Pure client-side implementation - No server required

Modular design - Easy to add new story branches

Accessibility-focused - Keyboard navigable buttons

Lightweight - Under 50KB without assets

Contributing
Contributions are welcome! Please:

Fork the repository

Create a new branch for your feature

Submit a pull request
