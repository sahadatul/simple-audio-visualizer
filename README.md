# Simple Audio Visualizer

Version 0.1

A single-file web app that turns any song on your device into a music visualizer and records it as a video with audio.

## Features

- Load any audio file (plays locally, nothing is uploaded)
- Customize: background color, soul (shape, size, color), rings, wave line, ground bars, raindrops, song title (font, size, color)
- Screen sizes: Fit, 16:9, 9:16, 1:1
- Record and export as MP4 (H.264), 720p or 1080p, in real time

## Run

Open `index.html` in a browser, or serve the folder:

```
python3 -m http.server 8000
```

Then open http://localhost:8000

## Export notes

- Recording runs in real time. Keep the tab open until it finishes.
- MP4 needs a browser that can encode H.264 (recent Chrome, Edge or Safari). Otherwise the app records WebM and says so on screen.
- The MP4 muxer (mp4-muxer 5.1.3) loads from jsDelivr, so an internet connection is needed.

## License

MIT
