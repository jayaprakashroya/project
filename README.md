# Arpeggiator Web App

A browser-based interactive music and visualization app featuring a hand-controlled arpeggiator, drum machine, and real-time waveform visualizer.

## Features
- Hand-controlled arpeggiator
- Drum machine
- Real-time waveform visualizer using Three.js
- Modern, modular JavaScript codebase

## Technologies Used
- JavaScript (ES Modules)
- Three.js (3D visualization)
- Tone.js (audio synthesis and analysis)
- HTML5 & CSS3

## Getting Started

### Prerequisites
- Modern web browser (Chrome, Edge, Firefox, etc.)
- [Node.js](https://nodejs.org/) or [Python](https://www.python.org/) (for running a local server)

### Running Locally
1. Clone or download this repository.
2. Open a terminal in the project directory.
3. Start a local server:
   - With Node.js:
     ```
     npx serve -l 8080
     ```
   - With Python:
     ```
     python -m http.server 8080
     ```
4. Open your browser and go to [http://localhost:8080](http://localhost:8080)

### Project Structure
- `index.html` – Main HTML file
- `main.js` – Entry point JavaScript
- `game.js` – Core game logic
- `DrumManager.js` – Drum machine logic
- `MusicManager.js` – Arpeggiator/music logic
- `WaveformVisualizer.js` – Audio waveform visualization
- `styles.css` – App styling

## Usage
- Interact with the app using your mouse, keyboard, or hand gestures (if supported).
- The app will visualize music and drum patterns in real time.

## Credits
- Built with Three.js and Tone.js
- Inspired by creative coding and music technology projects


