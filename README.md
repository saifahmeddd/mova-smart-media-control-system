# Mova - Gesture-Controlled Media Player

A Python application that uses computer vision to control media playback through hand gestures. Currently supports YouTube and Spotify on macOS.

## Features

- Control media playback using simple hand gestures
- Supports both YouTube and Spotify
- Real-time hand tracking with MediaPipe
- Intuitive gesture recognition:
  - Open Palm → Play/Pause
  - Victory Sign → Next Track
  - Thumbs Up → Volume Up
  - Thumbs Down → Volume Down

## Requirements

- Python 3.x
- OpenCV (`cv2`)
- MediaPipe
- macOS (for AppleScript functionality)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/saifahmeddd/mova.git
cd mova
