# SimpleDownloader & AIO Utilities

A collection of lightweight, powerful tools for downloading media and manipulating audio/video files.

## 📥 Tools Included

### 1. SimpleDownloader
A command-line tool to download video and audio from YouTube and SoundCloud.

**Features:**
- **Multi-Platform Support:** Downloads from YouTube and SoundCloud.
- **Format Selection:** Choose between `MP4` (Video) or `MP3` (Audio).
- **Smart Renaming:** Option to rename files immediately after download (supports spaces, no quotes needed).
- **Library Management:** Automatically copies downloaded files to your local music libraries (if configured).
- **Auto-Updates:** Checks for and installs updates automatically from this repository. (only downloader for now)

### 2. AIO (All-In-One) FFmpeg Utility
A versatile menu-driven tool for common audio and video operations using FFmpeg.

**Capabilities:**
- **Change Format:** Convert between various audio/video formats.
- **Change Speed:** Speed up or slow down media.
- **Change Volume:** Increase or decrease audio volume.
- **Extract Audio:** Strip audio tracks from video files.
- **Trim & Crop:** Cut specific sections or crop video dimensions.
- **Library Sync:** Quickly copy files to your configured music libraries.

---

## 🚀 Installation

### Standalone Executables (Recommended)
1. Download the latest `.exe` files from the [Releases](../../releases) page. (Preferably the .rar archive which includes everything you will need).
2. Place them in a folder of your choice.
3. **FFmpeg Requirement:**
   - Ensure ffmpeg is installed on your system or placed in a `./ffmpeg/bin` folder next to the executables.
   - If you downloaded the .rar file on your first install you got ffmpeg already included in there.

### Configuration
To configure the library function paste one library path per line like: G:/Youtube/Music
