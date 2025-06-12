# Multi-Timer App

A simple web-based timer application that lets you run multiple stopwatches and countdown timers simultaneously.

## Quick Start

1. Open the HTML file in your browser
2. Click "+ Add Timer" to create a new timer
3. Choose stopwatch or countdown type
4. For countdown: set hours, minutes, seconds
5. Click "Create Timer" and use Start/Pause/Reset controls

## Features

- **Multiple Timers**: Run as many timers as you need
- **Two Types**: Stopwatch (counts up) or countdown (counts down)
- **Persistent Storage**: Timers are saved and restored between sessions
- **Audio Alert**: Beep sound when countdown reaches zero
- **Visual Feedback**: Cards pulse when running, flash when finished
- **Editable Names**: Click timer names to rename them

## Controls

- **Start/Pause**: Toggle timer running state
- **Reset**: Return to initial time (0 for stopwatch, set time for countdown)
- **Delete**: Remove timer completely (× button)
- **Rename**: Click timer name to edit

## Browser Requirements

- Modern browser with localStorage support
- Audio support for countdown alerts

## Storage

All timers are automatically saved to your browser's local storage and restored when you reload the page.