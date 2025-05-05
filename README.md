# 💖 Heart Trail Project

A simple and fun JavaScript project that creates animated heart shapes following your mouse movements across the screen. Each time the user moves their mouse, a heart appears and fades away after a short period, creating a magical trail effect.

## ✨ Features

- Dynamic heart animation that follows mouse movements.
- Randomized heart sizes for a more organic and playful visual.
- Smooth entry and timed removal of each heart element.
- Lightweight and fully client-side.

## 🛠️ Technologies Used

- **HTML**
- **CSS**
- **JavaScript**

## 🚀 How It Works

1. Listens for the `mousemove` event on the body.
2. On every movement, it:
   - Captures the current cursor position.
   - Creates a `span` element at that position.
   - Randomizes its size for variety.
   - Appends it to the DOM.
   - Removes it after 3 seconds to keep the DOM clean.
