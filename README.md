# Live Streaming Viewer

A simple web application that allows users to watch live streams from multiple platforms (e.g., YouTube, Twitch, or custom RTMP streams) using **FFmpeg** to convert and serve the stream in **HLS (HTTP Live Streaming)** format. The app provides a user-friendly interface where users can easily paste stream URLs and watch content in real time.

## Features

- **Multi-Platform Support**: Watch live streams from various platforms like YouTube, Twitch, and custom RTMP streams.
- **FFmpeg Integration**: Uses FFmpeg to convert incoming streams into HLS format compatible with modern web browsers.
- **Simple Interface**: Clean, intuitive front-end where users can input stream URLs and start watching instantly.
- **Live Streaming**: Supports live stream playback in real-time.

---

## Requirements

Before you begin, ensure you have the following software installed:

### Software Dependencies

- **Node.js** (v14.x or higher) — [Download Node.js](https://nodejs.org/)
- **FFmpeg** (for stream processing) — [Install FFmpeg](https://ffmpeg.org/download.html)
- **yt-dlp** or **youtube-dl** (optional for YouTube stream fetching) — [Install yt-dlp](https://github.com/yt-dlp/yt-dlp)

### Install FFmpeg

- **Ubuntu**: `sudo apt-get install ffmpeg`
- **macOS (Homebrew)**: `brew install ffmpeg`
- **Windows**: [Download FFmpeg for Windows](https://ffmpeg.org/download.html) and add it to your PATH.

### Install yt-dlp (For YouTube)

yt-dlp is a fork of youtube-dl, which works better for extracting video URLs from YouTube:

```bash
pip install yt-dlp
