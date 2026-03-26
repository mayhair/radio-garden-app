# 🌍 Radio Garden Desktop (Unofficial)

[![Version](https://img.shields.io/badge/version-1.1.4-green.svg)](https://github.com/mayhair/radio-garden-app/releases)
[![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20Linux-blue.svg)](https://github.com/mayhair/radio-garden-app/releases)
[![Discord](https://img.shields.io/badge/Discord-Rich%20Presence-7289DA.svg)](https://discord.com/)

An awesome, fun, and minimal desktop wrapper for [radio.garden](https://radio.garden). Originally created by **chillzaurus**, now maintained and fixed for Linux by **mayhair**.

Travel the globe and listen to thousands of live radio stations by simply rotating the Earth!

![Radio Garden Preview](icon.png)

## ✨ Features

- **🎮 Discord Rich Presence**: Show your friends what station and city you're vibing to in real-time.
- **⏲️ Sleep Timer**: Fall asleep to global tunes. Features a smooth volume fade-out before closing.
- **📊 Listening Stats**: Track your journey! See your "Top Countries," "Favorite Stations," and even your listening "Streak."
- **📂 Favorites Folders**: Organize your favorite stations into custom folders for easy access.
- **🚫 Ad-Blocker Built-in**: A cleaner experience with built-in blocking for common ad networks.
- **⌨️ Keyboard Shortcuts**:
  - `Space`: Play / Pause
  - `F`: Quick access to Favorites
  - `Ctrl + R`: Reload the stream
  - `↑ / ↓`: Browse favorites
- **⚓ Tray Integration**: Runs quietly in the background. Access recent stations and timers directly from the system tray.
- **🌓 Native Feel**: Support for Windows Mica/Vibrancy effects and Linux AppImage.

## 🐧 The "Linux Fix"

The upstream builds for Linux were unfortunately broken. This fork specifically addresses those issues, ensuring a smooth experience for Linux users with proper icon handling and pathing fixes. 

## 🚀 Installation

### Windows
1. Download the latest `.exe` from the [Releases](https://github.com/mayhair/radio-garden-app/releases) page.
2. Run the installer and enjoy!

### Linux
1. Download the `.AppImage` from the [Releases](https://github.com/mayhair/radio-garden-app/releases) page.
2. Make it executable: `chmod +x Radio-Garden-x.x.x.AppImage`
3. Run it!

## 🛠️ Development

Want to tweak it?

```bash
# Clone the repo
git clone https://github.com/mayhair/radio-garden-app.git

# Install dependencies
npm install

# Run in development mode
npm start

# Build for your current platform
npm run dist
```

## 📜 Credits & Disclaimer

- **Original Author**: [chillzaurus](https://github.com/chillzaurus)
- **Linux Maintenance**: [mayhair](https://github.com/mayhair)
- **Web Content**: All radio content and the core experience are powered by [Radio Garden](https://radio.garden).

*This is an independent, unofficial project and is not affiliated with, endorsed by, or associated with Radio Garden.*

---
<p align="center">Made with ❤️ for radio lovers everywhere.</p>
