# DQ-Lipsync-rhubarb

A simple web-based lip sync demo that synchronizes mouth shapes with audio playback, using Rhubarb Lip Sync for generating lip sync data.

## Features

- Real-time lip sync animation with audio playback
- Adjustable mouth position, size, and rotation
- Live preview of current mouth shape
- Debug panel showing timing information
- Smooth mouth shape transitions

## Usage

1. Open `index.html` in a web browser
2. Click the play button to start the audio and lip sync animation
3. Use the controls to adjust the mouth position and size
4. Watch the debug panel for timing information

## Customization

To use your own audio:

1. Download [Rhubarb Lip Sync](https://github.com/DanielSWolf/rhubarb-lip-sync/releases)
2. Place your audio file in the `data/` directory as `input.wav`
3. Generate lip sync data: `rhubarb -f json data/input.wav -o data/output.json`
4. Refresh the page to see your audio with synchronized lip movements

## Credits

This demo uses [Rhubarb Lip Sync](https://github.com/DanielSWolf/rhubarb-lip-sync) for generating lip sync data.
