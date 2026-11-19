🎬 Video Compressor

<p align="center">
  A lightweight video compression project powered by <strong>FFmpeg</strong> and <strong>Docker</strong>.
</p><p align="center">
  <img src="https://img.shields.io/badge/Status-In%20Development-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/FFmpeg-Powered-green?style=for-the-badge&logo=ffmpeg" />
  <img src="https://img.shields.io/badge/Docker-Enabled-blue?style=for-the-badge&logo=docker" />
</p>---

📌 About The Project

Video Compressor is an experimental project designed to reduce video file sizes while maintaining acceptable visual quality.

The project uses FFmpeg to convert videos to lower resolutions, such as 360p, with the H.264 video codec.

The long-term goal is to develop a Telegram bot that allows users to compress videos easily and receive the processed files.

✨ Features

- 🎥 Video compression using FFmpeg
- 📉 Resolution reduction (e.g. 720p / 1080p to 360p)
- ⚙️ H.264 video encoding
- 🐳 Docker-based environment
- 🔄 Automated testing with GitHub Actions
- 📦 Compressed video output as a workflow artifact

🛠️ Technologies

Technology| Purpose
FFmpeg| Video processing and compression
Docker| Containerization
Alpine Linux| Lightweight base operating system
GitHub Actions| Automated workflows and testing

🚧 Project Status

Currently under development.

The current version focuses on testing and improving the video compression process.

Planned Features

- [ ] Telegram Bot integration
- [ ] Automated video processing
- [ ] Cloud-based deployment
- [ ] Video upload and download system
- [ ] Queue management for multiple requests

📂 Project Structure

video-compressor/
├── .github/
│   └── workflows/
│       └── compress.yml
├── Dockerfile
└── README.md

⚠️ Note

This is an experimental project and is not intended for production use yet.

---

<p align="center">
  <sub>Built with ❤️ using FFmpeg and Docker</sub>
</p>
