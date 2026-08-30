# Vinyl Scene

The first public friend beta of Vinyl Scene, a tactile music-responsive desktop for macOS.

## Download and install

### [Download Vinyl Scene for Apple Silicon (18.9 MB)](https://github.com/shebabaloo/vinyl-scene/releases/download/v0.1.0-friend-beta/Vinyl-Scene-0.1.0-friend-beta-arm64.zip)

Requires an Apple Silicon Mac (M1 or newer) running macOS 14 Sonoma or later. Intel Macs
are not supported by this beta.

1. Click the download link above.
2. Double-click the ZIP, then move **Vinyl Scene.app** into your **Applications** folder.
3. Try to open Vinyl Scene once. macOS will warn that the developer cannot be verified.
4. Open **System Settings → Privacy & Security**, scroll to **Security**, and choose
   **Open Anyway** for Vinyl Scene.
5. Confirm **Open** when macOS asks again. If you enable live music, also approve the
   optional Automation prompt for Apple Music or Spotify.

In the **Assets** list below, the app is
`Vinyl-Scene-0.1.0-friend-beta-arm64.zip`. Do **not** download either automatically
generated **Source code** archive; those files do not contain the app.

## Included

- Standard Listening Room with a six-row live board and public idle welcome
- Shez's Listening Room as a visible personalization example with an idle quote deck
- Desk Loop with large animated record, lower-left track card, and top-down coffee steam
- Preview mode plus optional Apple Music and Spotify now-playing support
- Still, Quietly alive, and Expressive motion modes
- Follow-album or fixed-color behavior with four finishing treatments
- Display selection, desktop mode, login-item option, and menu-bar recovery
- Local Creator Kit export, validation, and import flow

## Compatibility

- Apple Silicon only
- macOS 14 Sonoma or later
- Bundle identifier: `com.shehzadmansuri.vinylscene`

## Important: unnotarized friend beta

This build is ad-hoc signed rather than signed with an Apple Developer ID. macOS therefore
requires the manual **System Settings → Privacy & Security → Open Anyway** flow described
in the repository README.

## Download verification

After downloading, run:

```bash
shasum -a 256 ~/Downloads/Vinyl-Scene-0.1.0-friend-beta-arm64.zip
```

Expected SHA-256:

```text
a2724ca3b10b2283a7761d54cefec0d5260b112d7115b7b8a9d9585acc6a67ff
```
