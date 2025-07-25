# Pomodoro App

A simple web-based Pomodoro timer to help you focus and manage your work sessions.

## Features

- Start a 25-minute Pomodoro session with a single click
- Visual countdown timer
- Audio notification when the session ends
- Responsive and modern design

## Usage

1. Open `index.html` in your browser.
2. Click the **start** button to begin a Pomodoro session.
3. The timer will count down from 25:00. When it reaches 0, a bell sound will play.

## Project Structure

- [`index.html`](index.html): Main HTML file for the app interface
- [`style.css`](style.css): Stylesheet for layout and design
- [`app.js`](app.js): JavaScript logic for the timer

## Requirements

- Modern web browser
- The bell sound file should be placed at `./sounds/bell.wav`

## Customization

- To change the session length, edit the value inside `<span class="minutes">25</span>` in [`index.html`](index.html).
- You can update styles in [`style.css`](style.css) to match your preferences.
