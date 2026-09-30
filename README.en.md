# MushHub

🇲🇽 [Leer en español](README.md)

**Streaming assistant for Windows**: control OBS with your voice, prepare titles for Twitch, Kick and YouTube, bring the chat from all your platforms together and find the best clips of your stream with local AI.

> 📥 **[Download the latest version](https://github.com/Mushingames/MushHub-Descargas/releases/latest)** (installer for 64-bit Windows 10/11)

![MushHub summary](docs/resumen.png)

## What it does

- 🎙️ **Voice commands** for OBS: scenes, clips, Replay Buffer, recording and microphone, without touching the keyboard. For now, voice commands are in Spanish ("Asistente, clip", "Asistente, cambia a Lobby").
- 🤖 **MushAI (local AI, free and private)**: understands free-form phrases and helps you get your stream ready. It runs on your PC; no accounts or paid APIs needed.
- ✂️ **AI clips**: listens to your recording, looks at when chat blew up and where you marked moments, and suggests the best clips with a title. You can ask for "a funny moment" or "a good play".
- 📱 **Vertical clips**: crop gameplay and webcam for TikTok/Shorts, with automatic subtitles.
- 💬 **Unified chat** from Twitch, Kick, YouTube and TikTok, with emotes (7TV, BTTV, FFZ) and read-aloud.
- 📝 **Titles and categories** for Twitch, Kick and YouTube, always with a preview and your confirmation.
- 🌐 **English and Spanish interface** (Settings → System → Idioma / Language). In English, clip folders use English names.

| AI clips | Voice commands |
|---|---|
| ![Clips](docs/clips.png) | ![Voice](docs/voz.png) |

## Requirements

- 64-bit Windows 10 or 11.
- [OBS Studio](https://obsproject.com/) 28 or newer, with the WebSocket server turned on (Tools → WebSocket Server Settings).
- For the local AI: a graphics card with 8 GB or more is recommended (it also works without one, just slower). With a graphics card, MushAI listens to one hour of stream in 2-3 minutes.

## Installing

1. Download `MushHub-…-Setup-…-x64.exe` from [Releases](https://github.com/Mushingames/MushHub-Descargas/releases/latest).
2. Open it. The installer is not code-signed, so Windows may show **"Windows protected your PC"**: click **More info → Run anyway**.
3. Follow MushHub's first-run setup (folders, OBS and your platforms).

MushHub lets you know when a new version is out.

## Privacy

Your recordings, clips, chat and settings stay **on your PC**. Accounts are connected through each platform's official authorization (MushHub never sees your passwords) and access is stored encrypted by Windows. MushHub does not sell or share your data.

## Questions or bugs?

Write to **contacto.mushhub@gmail.com**. If something fails, attach the file `%LOCALAPPDATA%\MushHub\data\logs\mushhub.log`.

## Support the project

If MushHub helps your streams, you can support its development:

[![Support on Ko-fi](https://img.shields.io/badge/Ko--fi-Support%20MushHub-29abe0?logo=ko-fi&logoColor=white)](https://ko-fi.com/mushingames)

---

MushHub is an independent project by [MushInGames](https://twitch.tv/mushingames) and is not affiliated with Twitch, Kick, YouTube, TikTok or OBS. Use is subject to the license included in the installer.
