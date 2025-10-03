# -SCT_-Track-Stop-Watching-app_Task02-
⏱ Stopwatch Web Application

A simple, responsive, and interactive Stopwatch built using HTML, CSS, and JavaScript.
This project demonstrates the implementation of time tracking logic in JavaScript along with a clean and modern UI.

🚀 Features

Start / Stop / Reset controls

Start: Begins the stopwatch.

Stop: Pauses the stopwatch.

Reset: Resets the time to 00:00:00.00.

Precise time tracking

Tracks hours, minutes, seconds, and milliseconds.

Responsive design

Centered container with adaptive layout.

Works well on desktops and mobile devices.

Modern UI styling

Dark theme with clean contrast.

Hover effects on buttons for a smooth user experience.

Lightweight & dependency-free

Written in pure HTML, CSS, and JavaScript (no external libraries required).

🛠️ Tech Stack

HTML5 – Page structure and elements.

CSS3 – Styling, layout, and hover effects.

JavaScript (ES6) – Stopwatch logic and DOM manipulation.

📂 Project Structure
Stopwatch/
│── index.html   # Main file containing HTML, CSS, and JS

📸 Preview

Stopwatch layout with time display (hours : minutes : seconds . milliseconds).

Control buttons: Start, Stop, Reset.

⚡ How It Works

When the Start button is clicked, the stopwatch begins updating every 10 milliseconds using setTimeout.

The Stop button halts the timer without resetting it.

The Reset button stops the timer and sets all values back to 00.

The displayTime() function ensures proper formatting with leading zeros (e.g., 02:05:09.07).

📚 Learning Concepts

This project is great for beginners to understand:

DOM manipulation (getElementById, innerText).

Event handling (onclick).

Timer functions (setTimeout).

Conditional formatting with leading zeros.

Responsive UI design with CSS Flexbox.

✅ Future Enhancements

Add Lap functionality to record multiple times.

Add Pause & Resume instead of a simple stop.

Improve UI with animations or themes.

Save laps/times in local storage.
