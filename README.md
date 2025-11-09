# 🕰️ Theme Clock

A beautiful, responsive analog and digital clock with a dark/light mode toggle. Built with HTML, CSS, and JavaScript.

![Theme Clock](https://github.com/Rusith1204/simple-clock/blob/66c7dabbc79091c275b22cfd879d180dbcfe1a09/Screenshot%202025-11-09%20082932.png) 

## ✨ Features

- **Dual Display**: Simultaneous analog and digital time reading.
- **Dark/Light Mode**: Toggle between themes with a smooth transition.
- **Real-time Updates**: The clock updates every second.
- **Dynamic Date**: Shows the current day, month, and date.
- **Easter Egg**: Click the center point of the clock for a fun surprise! 🥚

## 🚀 Live Demo

Check out the live project here: [https://rusith1204.github.io/simple-clock/]


## 🧠 How It Works

- The clock uses JavaScript's `Date` object to get the current time.
- The hands of the analog clock are rotated using CSS transforms, with calculations done via a `scale` function to map time units to degrees.
- CSS custom properties (variables) are used for theming, which are toggled via JavaScript when the dark mode button is clicked.
