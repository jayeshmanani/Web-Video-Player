🎬 Web Video Player

A lightweight custom HTML5 video player built using TailwindCSS and vanilla JavaScript — no frameworks or libraries required.
Supports local files, remote video URLs, playback controls, keyboard shortcuts, speed adjustments, custom progress/volume controls, and fullscreen.

🚀 Features

✅ Custom UI Controls

Play / Pause

Volume and Mute

Seek Bar with draggable thumb

Playback Speed (0.5x – 2.5x, adjustable by 0.1)

Fullscreen Toggle

Time Display (Current / Total Duration)

✅ Load Sources

Upload local video/audio files (.mp4, .webm, .ogg, .mp3, etc.)

Paste and play public video URLs

✅ Dynamic Playback Speed Menu

Click the speed button to select a playback rate between 0.5x and 2.5x

✅ Keyboard Shortcuts

Key	Action
Space	Play / Pause
F	Toggle Fullscreen
M	Mute / Unmute
→	Skip forward 5s
←	Skip backward 5s
[	Slow down playback (-0.1x)
]	Speed up playback (+0.1x)
=	Reset speed to 1.0x

✅ Other Features

Toast notifications for key actions (speed, mute, etc.)

Smooth progress animation (via requestAnimationFrame)

Responsive design (works well on both desktop and mobile)

Clean dark-themed Tailwind styling

Memory-safe file loading (blob revocation)

🧱 Tech Stack

HTML5 (video element + UI)

TailwindCSS (CDN version)

Vanilla JavaScript (ES6+)

No dependencies or frameworks are required.

📦 Getting Started
1️⃣ Clone the repository
git clone https://github.com/jayeshmanani/Web-Video-Player.git
cd web-video-player

2️⃣ Open the file

Simply open index.html in your browser — no server setup required!

3️⃣ Load a video

Upload a local file using the “Choose File” button

OR paste a public video URL (e.g. https://example.com/video.mp4) and press Enter


🧩 Customization

Change the default poster image by editing the <video> tag’s poster attribute.

Adjust Tailwind colors or UI layout directly in the HTML.

You can add quality switching by populating availableQualities with URLs.

Example:

availableQualities = {
  "720p": "https://example.com/video_720.mp4",
  "1080p": "https://example.com/video_1080.mp4"
};

⚡ Browser Compatibility

Tested on:

Chrome ✅

Firefox ✅

Edge ✅

Safari ✅

🧠 License

MIT License — free to use, modify, and distribute.