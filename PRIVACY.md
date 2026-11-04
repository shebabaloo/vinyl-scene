# Privacy

The Vinyl Scene 0.1.8 beta is designed as a local macOS application.

## What the app reads

- If you opt into **Live music**, Vinyl Scene asks macOS for permission to read the
  currently playing title and artist from Apple Music or Spotify. It only asks a player
  that is already running.
- Spotify may also provide an artwork URL. When available, Vinyl Scene fetches that image
  transiently to derive the scene palette.
- Display names and identifiers are read locally so you can choose which desktop receives
  the scene.

## What the app stores

- Scene, motion, color, display, startup, and onboarding preferences are stored locally in
  macOS user defaults.

## What the app does not do

- No account or sign-in
- No advertising
- No analytics or telemetry
- No developer-operated server
- No sale or sharing of personal data
- No upload of music history or preferences

Preview mode does not contact Apple Music or Spotify. Live music can be disabled at any
time in the editor, and Automation access can be revoked in **System Settings → Privacy &
Security → Automation**.

The app's bundled privacy manifest declares no tracking or collected-data categories and
declares its local preferences use.
