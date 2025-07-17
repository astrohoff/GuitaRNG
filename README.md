# 🎸 GuitaRNG - A guitar practice playlist manager

A cross-platform Flutter app for guitarists to manage a personal song catalog, attach backing tracks, and generate randomized practice playlists — with support for tempo and pitch control. Built for Android and Windows.

---

## ✨ Features

- 🎵 **Song Catalog**: Store songs you know with metadata (title, artist, tags, difficulty, notes)
- 🔊 **Attach Backing Tracks**: Link each song to a local audio file (MP3, FLAC, etc.)
- 🔀 **Randomized Playlist Generator**: Shuffle songs for varied practice sessions
- 🎚️ **Playback Controls**: Play, pause, skip, change pitch and tempo in real time
- 📁 **Local Storage**: All data stored on-device (no login required)

---

## 🚧 Project Status

> This project is in early development. Basic scaffolding is underway, with core functionality being implemented in stages.

---

## 📦 Built With

- [Flutter](https://flutter.dev/) — Cross-platform UI toolkit
- [`just_audio`](https://pub.dev/packages/just_audio) — Audio playback
- [`file_picker`](https://pub.dev/packages/file_picker) — Load local backing tracks
- [`hive`](https://pub.dev/packages/hive) or `drift` — Local data storage (to be decided)

---

## 🚀 Getting Started

To run this project locally:

```bash
# Clone the repo
git clone https://github.com/astrohoff/GuitaRNG.git
cd GuitaRNG

# Install dependencies
flutter pub get

# Run on your platform
flutter run -d windows  # or -d android
```
---

## 📄 License
This project is licensed under the MIT License.