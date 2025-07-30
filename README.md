🎵 Music Player Web App 
A stylish and responsive **Music Player** built with **HTML**, **CSS**, and **JavaScript**. This app allows users to play a song, control playback, and visually see the song progress. It’s a front-end-only project that mimics the functionality of a simple music player.

---

## 📌 Features

* ▶️ Play/Pause song toggle
* 🎧 Song title and artist display
* 📶 Real-time progress bar synced with audio
* 🎨 Beautiful gradient UI design
* 🖼️ Album art display
* 💡 Responsive design layout
* 🧠 Built with pure HTML/CSS/JavaScript

---

## 💻 Tech Stack

* **HTML5**
* **CSS3** (including Flexbox, gradients, shadows)
* **Vanilla JavaScript**
* **Font Awesome** for icons

---

## 📁 File Structure

```
music-player/
│
├── index.html         # Main HTML layout
├── style.css          # Styling for player layout and UI
├── music/             # Folder with audio and image
│   ├── Kaathu Mela(KoshalWorld.Com).mp3
│   └── 42376_4.jpg
└── (FontAwesome CDN)  # Used for control icons
```

---

## 🎮 How It Works

### 🎤 index.html

* Contains the structure for:

  * Album image
  * Song title and artist
  * Audio element
  * Range input (progress bar)
  * Playback controls (Back, Play/Pause, Forward)

### 🎨 style.css

* Handles layout, colors, gradients, and animations.
* Implements:

  * Circular album art
  * Custom-styled progress bar with gradient
  * Hover effects and shadow depth

### 🧠 Embedded JavaScript

```js
let song = document.getElementById("song");
let ctrlIcon = document.getElementById("ctrlIcon");
```

* Updates the progress bar every 0.5 seconds
* Handles click to toggle play/pause
* Handles dragging the slider to seek audio


---

## 🚀 How to Run Locally

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/music-player.git
   ```

2. Navigate to the folder:

   ```bash
   cd music-player
   ```

3. Open `index.html` in your browser:

   ```bash
   start index.html     # Windows
   open index.html      # macOS
   ```

---

## 🧪 Improvements You Can Add

* [ ] Add playlist and song switching support
* [ ] Add volume control
* [ ] Display current time / duration
* [ ] Add waveform or visualizer
* [ ] Add responsive mobile menu


---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

