<p align="center">
  <img src="docs/icon.png" alt="Live CC" width="128">
</p>

<h1 align="center">Live CC</h1>

<p align="center">
  <b>YouTube, turned into a music player for Windows</b><br>
  lyrics that follow the song &middot; karaoke &middot; listening rooms
</p>

<p align="center">
  <a href="https://github.com/StivenDEP/livecc-releases/releases/download/installer/LiveCC-Setup.exe"><img alt="Download for Windows" src="https://img.shields.io/badge/Download-Windows%2010%20%2F%2011-FF0000?style=for-the-badge&logo=windows&logoColor=white"></a>
  &nbsp;
  <a href="https://github.com/StivenDEP/livecc-releases/issues/new/choose"><img alt="Send feedback" src="https://img.shields.io/badge/Feedback-Issues-555555?style=for-the-badge&logo=github&logoColor=white"></a>
</p>

---

## Description

**Live CC** opens YouTube in its own locked window and replaces the page with a clean music player: search, a real
queue, genres and playlists, with **no YouTube clutter**. A **floating lyrics bar** follows every song, a **karaoke**
mode removes the vocals and scores your singing, and **rooms** let a whole office hear the same song at the same moment.

It runs inside a browser you already trust:
- **Brave** (recommended): Brave blocks YouTube ads by itself.
- **Google Chrome** or **Microsoft Edge**: ads are muted and skipped, not blocked.

Everything you need ships in the installer: a portable Python runtime and the speech and vocal models. There is
nothing else to install.

---

## Features

### Music
- Search songs or **search by lyrics**; Home, Genres and your YouTube playlists (optional sign-in).
- Queue with **Played / Playing / Up next**, drag to reorder, one Shuffle switch, repeat.
- **Audio-only** mode by default, video one click away; crossfade, sleep timer, equalizer.
- Music filter: show **only music** (Off / Balanced / Strict).

### Lyrics
The bar picks the best source for every song and falls back automatically:

| Order | Source | Timing |
|:-:|---|---|
| 1 | YouTube subtitles | from YouTube |
| 2 | Synced lyrics (LRCLIB, syncedlyrics) | line by line |
| 3 | Web lyrics (Genius, LRCLIB, LyricsOnDemand) | timed to the audio |
| 4 | YouTube auto captions | from YouTube |
| 5 | Speech transcription (Whisper) | last resort only |

- Click a line to **translate** it (15 languages); **Ctrl+click** the line being sung to fix the timing.
- Floating over any window, docked inside the app, or off.

### Karaoke
- Vocal removal: a quick filter or **AI vocal removal**.
- Moods, effects and beat pulse; **PITCH** and **VOCAL** scores per line.
- Competitions with judges, also inside a room.

### Rooms (listen together)
| | |
|---|---|
| **Access** | Open (anyone joins) or Approval (the host lets each person in) |
| **Visibility** | Public (listed) or Private (8-character code) |
| **Together** | Shared queue with votes, reactions with sounds, push-to-talk mic, room karaoke |
| **Host** | The host's Live CC runs the room; *Pass host* moves it to another member |
| **Privacy** | End-to-end encrypted |

### Always up to date
- Live CC checks for updates **at launch, every hour and the moment one is published**. You see
  **NEW UPDATE**, the publisher's note, and choose **Update now** or **Later** (Settings > Updates keeps it for you).
- Every update is **signed**: each PC verifies the signature and every file and keeps a backup before installing.
- Lives in the **tray**: now playing, controls, volume, room sounds; optional start with Windows.

---

## Download

<p>
  <a href="https://github.com/StivenDEP/livecc-releases/releases/download/installer/LiveCC-Setup.exe"><img alt="Download LiveCC-Setup.exe" src="https://img.shields.io/badge/LiveCC--Setup.exe-Download-FF0000?style=for-the-badge&logo=windows&logoColor=white"></a>
</p>

1. Download **`LiveCC-Setup.exe`**.
2. Run it and click **Install**. No admin rights needed; it installs for your Windows user only.
3. Live CC opens by itself and updates itself from then on. If Brave is missing, it offers **Download Brave** or
   **Continue with** Chrome / Edge.

| Requirement | |
|---|---|
| System | Windows 10 or 11, 64-bit |
| Browser | Brave (recommended), Chrome or Edge |
| Disk | about 1.2 GB |
| Network | Internet (YouTube, lyrics, rooms, updates) |

> **Trouble?** Run `LiveCC.exe --check` in the install folder (`%LOCALAPPDATA%\Programs\LiveCC`). It lists
> what Live CC needs and what it found. Logs: `%LOCALAPPDATA%\LiveCC\host.log`.

Update history: [Releases](https://github.com/StivenDEP/livecc-releases/releases).

---

## Feedback

Found a bug or have an idea? **[Open a feedback issue](https://github.com/StivenDEP/livecc-releases/issues/new/choose)**.
Pick *Bug report* or *Idea* and the form asks for the details we need.
