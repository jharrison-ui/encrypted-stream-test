# Esplayer android - open source IPTV player with support for encrypted streams

**Last updated:** 2026-09-07

Download the APK from the `esplayer_android` folder to install on Android.

- Main repository: [dbojan/esplayer](https://github.com/dbojan/esplayer)
- You can search the playlist and save the result as a new playlist.
- Place your playlist file at `Documents/esplayer.txt` on Android.

Example file `local_playlist_example.m3u`:

```m3u
#EXTM3U
#EXTINF:-1 tvg-id="TestChannel" tvg-name="Test Channel",Test Channel
#KODIPROP:inputstream.adaptive.license_type=clearkey
#KODIPROP:inputstream.adaptive.license_key=0123456789abcdef0123456789abcdef:0123456789abcdef0123456789abcdef
https://example.com/stream/manifest.mpd
```

# Esplayer desktop - open source IPTV player with support for encrypted streams

**Last updated:** 2026-09-07

Download the desktop build from the `esplayer_desktop` folder to install on Desktop.

- Place your playlist file in the same directory as the AppImage or executable.
- You can search the playlist and save the result as a new playlist.

## Changelog

- **2026-09-07** — fixes and new features
- **2026-03-28** — working on improving android tv ui
- **2026-03-22** — added support for subtitles, more settings, remote support (to test)

---

# Other players available

- **2026-06-17** — [AuthoIPTV](https://github.com/glitport/AuthoIPTV/) can play encrypted channels on PC (freeware, closed source).

### Feature requests and issues posted regarding ClearKey support:

#### Android (Open Source)
- [DangoPlayer #24](https://github.com/brunochanrio/DangoPlayer/issues/24)
- [open-tv #317](https://github.com/Fredolx/open-tv/issues/317)
- [M3UAndroid #371](https://github.com/oxyroid/M3UAndroid/issues/371)
- [Fermata #686](https://github.com/AndreyPavlenko/Fermata/issues/686)

#### Desktop / PC (Open Source)
- [IPTVnator #656](https://github.com/4gray/iptvnator/issues/656) — implemented, currently not working in v0.22.0 (expected in v0.23.0)
- [VLC #29465](https://code.videolan.org/videolan/vlc/-/issues/29465)
- [mpv #17063](https://github.com/mpv-player/mpv/issues/17063)

#### Android (Closed Source)
- **Televizo** — supports playback.
- **OTT Navigator** — can play these streams (closed source, no automatic updates).
- **Sparkle TV** — works intermittently (closed source, updates up to every 3 hours; current choice).

#### Desktop / PC (Closed Source / Other)
- No dedicated desktop PC application available yet (possibly Kodi).

---

# Encrypted streams files to test if your own app can decrypt clearkey videos:

**Last updated:** 2026-03-28

Binary test files are hosted on Google Drive (due to file size limits exceeding 25 MB):

- [Download test files](https://drive.google.com/drive/folders/171E1WYpe6Zb2JOSm_ZnVV77P7e6InS6w?usp=sharing)

---

# Changes, history, etc

## Encrypted streams history

- **2026-03-21** — added tests for user agent and referrer
- **2026-03-17** — added text to video
- **2026-03-15** — updated docs

## License

BSD 2-Clause — see [LICENSE](LICENSE).
