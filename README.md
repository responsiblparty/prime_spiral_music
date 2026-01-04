<img width="1231" height="622" alt="Screen Shot 2026-01-04 at 12 50 50 PM" src="https://github.com/user-attachments/assets/d412e7f6-c548-4707-8877-fc09996d9af3" />
# ◈ Prime Spiral Music Box

An interactive, browser-based audiovisual experience that maps the distribution of prime numbers to geometric spirals and generative soundscapes.

## 🚀 Features

* **Three Mathematical Visualizations**: Toggle between the **Ulam Spiral** (square), **Sacks Spiral** (Archimedean), and **Vogel Spiral** (Golden Angle) to see how primes form distinct patterns.
* **Generative Audio**: Each prime number triggers a unique note. The pitch is determined by the prime's value and mapped to your choice of musical scales (Pentatonic, Minor, Major, etc.).
* **Dynamic Sound Synthesis**: Features built-in reverb, stereo panning based on screen position, and special harmonic intervals for Twin Primes.
* **Real-time Analytics**: Tracks current number, prime density, and twin prime counts as the spiral expands.
* **Interactive Controls**: Adjust playback speed, volume, and visual effects like glow and trails in real-time.

## 🎹 How to Use

1. **Open** `index.html` in any modern web browser.
2. **Click "Play"** to initialize the Web Audio API and start the sequence.
3. **Navigate** using the control panel or keyboard shortcuts:
* `Space`: Play/Pause
* `R`: Reset the spiral
* `Up/Down Arrows`: Adjust speed
* `M`: Mute/Unmute
* `Mouse Wheel`: Zoom in/out of the visualization



## 🛠️ Tech Stack

* **HTML5 Canvas**: For high-performance rendering of thousands of points.
* **Web Audio API**: For real-time oscillator synthesis and spatial audio.
* **JavaScript (ES6)**: Pure vanilla JS—no external libraries or frameworks required.
* **Google Fonts**: Uses 'JetBrains Mono' for a clean, technical aesthetic.

## 📜 Mathematical Logic

The project uses several coordinate systems to plot numbers:

* **Ulam**: A rectangular grid where numbers spiral outward.
* **Sacks**: Plots numbers along an Archimedean spiral where .
* **Vogel**: Uses the Golden Angle () to create Fermat's spiral patterns found in nature.
