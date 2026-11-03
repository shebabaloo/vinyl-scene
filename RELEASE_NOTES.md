# Vinyl Scene release notes

## Vinyl Scene Beta 0.1.6 — November 2, 2026

### [Download Vinyl Scene Beta for Apple Silicon (7.4 MB)](https://github.com/shebabaloo/vinyl-scene/releases/download/v0.1.6-beta/Vinyl-Scene-Beta-0.1.6-build7-arm64.zip)

Requires an Apple Silicon Mac (M1 or newer) running macOS 14 Sonoma or later. Install steps
are in the [README](README.md#download-and-install).

### What's new since 0.1.0

- A simpler setup that asks only for the scene and the music source. Motion, color and
  more options live in the editor.
- Two scenes: the Listening Room and the Desk Loop. Building your own room may return in a
  future version.
- Color treatments shown as small records, and a spectrum strip for a fixed color.
- **Start at login** now works on first use.
- Live music only asks a player that is already running, so a Mac without Spotify is
  never asked "Where is Spotify?".
- The app is now named **Vinyl Scene Beta**, with its own preferences. It can sit beside
  0.1.0; run one at a time.

### Included

- Listening Room with a six-row live board and an idle welcome
- Desk Loop with a large animated record, a printed track card and coffee steam
- Preview mode plus optional Apple Music and Spotify now-playing support
- Still, Quietly alive and Expressive motion modes; macOS Reduce Motion switches to Still
- Follow-album or fixed-color behavior with four finishing treatments
- Display selection, desktop mode, Start at login and menu-bar recovery
- Energy-aware rendering: covered, sleeping and inactive scenes stop their animation clocks

### Compatibility

- Apple Silicon only
- macOS 14 Sonoma or later
- Bundle identifier: `com.shehzadmansuri.vinylscene.publicbeta`

### Unnotarized beta

This build is ad-hoc signed rather than signed with an Apple Developer ID, so macOS needs
a one-time **System Settings → Privacy & Security → Open Anyway** approval, described in
the README.

### Download verification

```bash
shasum -a 256 ~/Downloads/Vinyl-Scene-Beta-0.1.6-build7-arm64.zip
```

Expected SHA-256:

```text
5e129be1ea2f9fbe8532673663330ce95711f76a6cf053c919d1a732ffb87db2
```

## Vinyl Scene 0.1.0 friend beta — August 30, 2026

The first public friend beta, superseded by 0.1.6. It remains available on its
[release page](https://github.com/shebabaloo/vinyl-scene/releases/tag/v0.1.0-friend-beta)
as `Vinyl-Scene-0.1.0-friend-beta-arm64.zip`, SHA-256
`ed342a04b8dd7b5cdfc1a0041b41d02d15eca45504cdcdfa590c79828e611f1e`.
