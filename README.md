# 🎬 Web Video Player

A lightweight, **custom HTML5 video player** built with **TailwindCSS** and **vanilla JavaScript** — no frameworks or dependencies required.  
Supports **local files**, **remote URLs**, **playback controls**, **keyboard shortcuts**, **speed adjustments**, **custom progress/volume controls**, and **fullscreen mode**.

---

## 🚀 Features

### 🎛️ Custom UI Controls
- **Play / Pause**  
- **Volume & Mute**  
- **Seek Bar** with draggable thumb  
- **Playback Speed** (0.5x – 2.5x, adjustable by 0.1)  
- **Fullscreen Toggle**  
- **Time Display** (Current / Total Duration)

### 📂 Load Sources
- Upload **local video/audio files** (`.mp4`, `.webm`, `.ogg`, `.mp3`, etc.)  
- Play **public video URLs** by pasting the link

### ⚡ Dynamic Playback Speed
- Click the **speed button** to select a rate between **0.5x and 2.5x**

### ⌨️ Keyboard Shortcuts

| Key   | Action                  |
|-------|------------------------|
| `Space` | Play / Pause          |
| `F`     | Toggle Fullscreen     |
| `M`     | Mute / Unmute         |
| `→`     | Skip forward 5s       |
| `←`     | Skip backward 5s      |
| `[`     | Slow down playback (-0.1x) |
| `]`     | Speed up playback (+0.1x)  |
| `=`     | Reset speed to 1.0x   |

### 🛠️ Other Features
- Toast notifications for key actions (speed changes, mute, etc.)  
- Smooth **progress animation** using `requestAnimationFrame`  
- Fully **responsive design** for desktop & mobile  
- Clean **dark-themed Tailwind styling**  
- Memory-safe file loading with **Blob revocation**

---

## 🧱 Tech Stack
- **HTML5** (`<video>` element + custom UI)  
- **TailwindCSS** (CDN version)  
- **Vanilla JavaScript** (ES6+)  
- **No external dependencies or frameworks** required

---

## 📦 Getting Started

1. **Clone the repository**

```bash
git clone https://github.com/jayeshmanani/Web-Video-Player.git
cd Web-Video-Player
```

2. **Open the player**

Open `index.html` in your browser — no server setup needed.

3. **Load a video**

- **Local file:** Use the "Choose File" button  
- **Remote URL:** Paste a public video URL (e.g., `https://example.com/video.mp4`) and press Enter

---

## 🧩 Customization

- Change the **poster image** by editing the `<video>` tag’s `poster` attribute  
- Adjust **Tailwind colors** or UI layout directly in the HTML  
- Optional **quality switching**:

```javascript
const availableQualities = {
  "720p": "https://example.com/video_720.mp4",
  "1080p": "https://example.com/video_1080.mp4"
};
```

## ⚡ Browser Compatibility

Tested on:

- Chrome ✅  
- Firefox ✅  
- Edge ✅  
- Safari ✅  

---

## 🧠 License

**MIT License** — free to use, modify, and distribute.

[View on GitHub](https://github.com/jayeshmanani/Web-Video-Player)
