# Spicetify HTPC Interface

A full-screen, 10-foot interface for Spotify designed for home theater PC setups and remote control navigation. Built as a Spicetify extension with a focus on living room usability.
<img width="2560" height="1440" alt="{EF98AF6E-60D2-4207-86B7-5A3999F57859}" src="https://github.com/user-attachments/assets/727672c7-4c89-4ae6-ab94-5fcb36243c15" />

## Overview

This extension transforms Spotify into a lean-back experience optimized for large displays and remote control navigation. It features a clean, minimal interface with large text, simplified controls, and a 5-key navigation system (up, down, left, right, enter) that works perfectly with media center remotes.

Based on Spicetify-Fullscreen-Canvas by khanhas, this project extends the concept with additional features for kiosk and HTPC environments.

## Features

### Interface
- Full-screen mode with optional automatic activation on startup
- Album artwork with blur effects and smooth transitions
- Sidebar navigation with library access
- Search functionality with on-screen keyboard
<img width="756" height="1340" alt="{E5713917-2541-435C-8738-112EB2037776}" src="https://github.com/user-attachments/assets/137be3f1-4471-496d-b41a-29cd3e6962fb" />


### Navigation
- Complete 5-key remote control support
- Keyboard-only navigation throughout the interface
- Focus indicators for current selection
- Library browsing
<img width="2560" height="1440" alt="{A83DFD64-3F27-468E-8A57-9D61CEA1EB5C}" src="https://github.com/user-attachments/assets/74b5862c-5290-4a2a-b1e2-a438f968ac68" />

### Playback Controls
- Standard transport controls (play, pause, skip)
- 15-second skip forward and backward
- Shuffle toggle
- Progress bar 
- Track metadata display (title, artist, album, release date)

### Additional Features
- Lyrics Plus integration support
- Song change animations
- Configurable startup delay
<img width="605" height="961" alt="{3B6B86BB-B2E9-4F08-8C01-BD303C60B93B}" src="https://github.com/user-attachments/assets/c7b29805-a97f-41c5-8691-49cf5a4df6b3" />


## Installation

### Prerequisites
- Spotify Desktop Client (Windows)
- [Spicetify CLI](https://spicetify.app/) installed and configured

### Steps

1. Download `HTPC-Interface.js` from this repository

2. Copy the file to your Spicetify extensions directory: `%APPDATA%\spicetify\Extensions\`


3. Enable the extension using Spicetify CLI:
```bash
spicetify config extensions HTPC-Interface.js
spicetify apply
```


## Startup

For HTPC setups, its recommended to use the argument `--kiosk` on the spotify exe, this removes some annoying things about the desktop app, mostly the "Press escape to exit fullscreen" popup on start.

```bash
"C:\Users\USER\AppData\Roaming\Spotify\Spotify.exe" --kiosk
```

<img width="678" height="881" alt="{DAF3885B-567F-488D-A1FA-3CEED4ACDCA4}" src="https://github.com/user-attachments/assets/6e7a0fa3-e8f0-438f-b454-e509e6039f3a" />
