# DQ-Lipsync-rhubarb

A simple web-based lip sync demo that synchronizes mouth shapes with audio playback, using Rhubarb Lip Sync for generating lip sync data.

## Features

- Real-time lip sync animation with audio playback
- Adjustable mouth position, size, and rotation
- Live preview of current mouth shape
- Debug panel showing timing information
- Smooth mouth shape transitions

## Structure

- `index.html`: Main demo file
- `data/output.json`: Lip sync timing data
- `images/mouth-shapes/`: Contains mouth shape images for different phonemes
- `audio/`: Contains the audio file used for lip sync

## Setup

1. Download the required assets:
   - Create `data/`, `images/`, and `audio/` directories
   - Download the assets package from the releases section
   - Extract the contents into their respective directories

2. Your directory structure should look like this:
```
lip-sync-demo/
├── index.html
├── data/
│   ├── input.wav
│   └── output.json
├── images/
│   ├── doctor.jpg
│   └── mouth-shapes/
│       ├── lisa-A.png
│       ├── lisa-B.png
│       └── ... (other mouth shapes)
└── audio/
    └── input.wav
```

## Usage

1. Set up the project structure as described above
2. Open `index.html` in a web browser
3. Click the play button to start the audio and lip sync animation
4. Use the controls to adjust the mouth position and size
5. Watch the debug panel for timing information

## Development

To generate new lip sync data for different audio:

1. Install [Rhubarb Lip Sync](https://github.com/DanielSWolf/rhubarb-lip-sync)
2. Place your audio file in the `data/` directory as `input.wav`
3. Run: `rhubarb -f json data/input.wav -o data/output.json`

## Credits

This demo uses [Rhubarb Lip Sync](https://github.com/DanielSWolf/rhubarb-lip-sync) for generating lip sync data.
