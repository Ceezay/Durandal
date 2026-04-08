<div align="center">
<img src="icon.png" width="250"/>

# DURANDAL

DURANDAL is a Windows desktop media downloader. Paste a URL from YouTube, Spotify, Instagram, TikTok, X, Discord, or Steam and download it in seconds — no browser extensions, no accounts required for most content.

Downloads are organised by platform into categories — MEDIA, SOCIAL, GAMING, and CREATIVE — each with format and quality controls. The home screen features a URL queue that auto-detects the platform, a recent downloads list, and per-platform download stats.

> *"I am DURANDAL."*

Download the latest release from the [Releases](https://github.com/Ceezay/Durandal/releases) page.

---

## Features

### Home Screen
- **URL Queue** — paste any supported URL and DURANDAL detects the platform automatically, downloads to the correct folder
- **Recent Downloads** — quick access to your last 15 downloads with open-folder button
- **Stats** — total and per-platform download counters

### MEDIA
- **YouTube** — MP4 or MP3, quality up to 4K, FPS options, playlist support, clip trimming
- **Spotify** — MP3 via YouTube Music matching, embedded metadata and artwork, adjustable bitrate
- **GIF → MP4** — convert any local GIF to MP4 with scale and FPS options

### SOCIAL
- **Instagram** — download posts and reels (session cookie support for private content)
- **TikTok** — MP4 or MP3 with quality options
- **X (Twitter)** — video downloads, native GIF grab, X to GIF converter
- **Discord & Tenor** — download CDN attachments, Tenor GIF support

### GAMING
- **Steam** — download profile avatars (static and animated), auto-detects animated WebM

### CREATIVE
- **Art Grab** — pull full-resolution artwork from YouTube or Spotify URLs
- **Avatar Cropper** — crop images or GIFs to standard avatar sizes with live preview

---

## Getting Started

1. Download the latest release from the [Releases](https://github.com/Ceezay/Durandal/releases) page
2. Extract the folder anywhere — it's fully portable
3. Run `DURANDAL.exe` — no installation required

On first launch it will set itself up automatically. No Python, no FFmpeg, no manual setup.

---

## Portable

DURANDAL is fully portable. The entire folder can be placed anywhere — your Desktop, a USB drive, a secondary drive. Keep all files in the folder together and run the exe from there.

App data (settings, cookies, history) is stored separately in `%APPDATA%\DURANDAL` and is not affected by moving the app folder.

---

## Requirements

- Windows 10 or 11
- Internet connection on first launch (for setup)

---

## Updates

DURANDAL checks for new releases automatically on every launch. A popup will appear when a new version is available.

Manual check: **Settings → Updates → Check for Update**

---

## Feedback & Suggestions

Found a bug? Got a feature request? Head over to [Discussions](https://github.com/Ceezay/Durandal/discussions).

---

## Credits

**Designed & built by CJ**

| | |
|---|---|
| **X** | [@BLAZlNGAMBER](https://x.com/BLAZlNGAMBER) |
| **YouTube** | [@BlazingAmber](https://www.youtube.com/@BlazingAmber) |
| **Steam** | [BlazingAmber](https://steamcommunity.com/id/BlazingAmber/) |

### Powered by

- [yt-dlp](https://github.com/yt-dlp/yt-dlp)
- [spotdl](https://github.com/spotDL/spotify-downloader)
- [FFmpeg](https://ffmpeg.org/)
- [Pillow](https://python-pillow.org/)
- [customtkinter](https://github.com/TomSchimansky/CustomTkinter)
- [mutagen](https://mutagen.readthedocs.io/)
- [certifi](https://github.com/certifi/python-certifi)
