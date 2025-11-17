# Web Drum Kit

This is a small web project that implements a simple drum kit. Click the drum buttons or press the mapped keyboard keys to play sounds.

## What this project contains

- `index.html` — main HTML file with the drum buttons.
- `style.css` — styling for the page and buttons.
- `index.js` — JavaScript that wires button clicks and keyboard events to audio playback.
- `images/` — button images used by the UI (crash, kick, snare, toms).
- `sound/` — audio files used by the drum kit (MP3s).

## How to run

There are two simple ways to run the project locally:

1. Open the `index.html` file in your browser (double-click or use `File -> Open`).

2. Serve the folder with a simple local HTTP server (recommended for consistent audio behaviour):



## Usage

- Click/tap the drum buttons to play each sound.
- Press the mapped keyboard keys (as shown on each button) to trigger the same sounds.

## Notes

- Tested on modern browsers (Chrome, Firefox, Safari). If audio doesn't play, check browser autoplay/gesture policies.
- Assets are bundled locally in `images/` and `sound/`.

## License

This project is provided as-is for learning and demonstration purposes.
