<div align="center">
<img src="icon.png" width="250"/>

# DURANDAL

DURANDAL is a personal media downloader I made for myself for Windows with a dark GUI inspired by Bungie's *Marathon*. No sketchy sites, no bloat — just a clean tool built around the things that actually matter.

Windows SmartScreen may flag this app as unrecognised. This is normal for unsigned software distributed outside the Microsoft Store. Click "More info" → "Run anyway" to launch it.

> *"I am DURANDAL."*

Download the latest release from the [Releases](https://github.com/Ceezay/Durandal/releases) page.

---

## Features

### YouTube
- Download videos as **MP4** or audio as **MP3**
- Quality selection up to 4K, FPS options (Any / 60 / 30)
- Full playlist support
- Clip trimming with start/end time controls

### Spotify
- Download tracks as **MP3** via YouTube Music matching
- Metadata and album artwork embedded automatically
- Adjustable bitrate

### X (Twitter)
- Download videos in quality tiers
- Grab native X GIFs directly
- Convert X videos to animated GIF with speed, FPS, width, and colour controls

### Art Grab
- Pull album and track artwork from YouTube or Spotify URLs
- Export at full resolution

### GIF → MP4
- Convert any local GIF file to MP4
- Scale and FPS options

### Discord & Tenor
- Download attachments directly from Discord CDN links
- Tenor GIF support (requires free API key from [tenor.com/developer](https://tenor.com/developer))

### Avatar Cropper
- Crop images or GIFs to standard avatar sizes (128 / 256 / 512 / 1024 px)
- Live canvas preview with draggable crop overlay
- Quality filters and GIF playback

---

## Getting Started

1. Download the latest `DURANDAL.rar` from the [Releases](https://github.com/Ceezay/Durandal/releases) page
2. Extract somewhere safe and run Durandal — no installation required
3. On first launch it will set itself up automatically
4. Desktop shortcut will be automatically generated upon first boot.

That's it. No Python, no FFmpeg, no manual setup. Everything is handled on first run.

---

## Requirements

- Windows 10 or 11
- An internet connection on first launch (for setup and downloading)

---

## First Launch

On first run DURANDAL will:
- Install all required Python libraries automatically
- Download FFmpeg if not already on your system
- Create a desktop shortcut

All app data is stored in `%APPDATA%\DURANDAL`.

---

## Updates

DURANDAL checks for new releases automatically on every launch. When a new version is available you will see a popup with a link to the release page.

You can also manually check via **Settings → Updates → Check for Update**.

---

## Feedback & Suggestions

Found a bug? Got a feature request? Head over to [Discussions](https://github.com/Ceezay/Durandal/discussions) and drop it there.

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
