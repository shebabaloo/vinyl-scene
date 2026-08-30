# Privacy

Vinyl Scene 0.1.0 is designed as a local macOS application.

## What the app reads

- If you opt into **Live music**, Vinyl Scene asks macOS for permission to read the
  currently playing title and artist from Apple Music or Spotify.
- Spotify may also provide an artwork URL. When available, Vinyl Scene fetches that image
  transiently to derive the scene palette.
- Display names and identifiers are read locally so you can choose which desktop receives
  the scene.

## What the app stores

- Scene, motion, color, display, startup, and onboarding preferences are stored locally in
  macOS user defaults.
- A locally imported Scene Pack stores only its validated final PNG plate and manifest in
  the user's Application Support folder.

## What the app does not do

- No account or sign-in
- No advertising
- No analytics or telemetry
- No developer-operated server
- No sale or sharing of personal data
- No upload of music history, preferences, Creator Kit references, or imported scenes

Preview mode does not contact Apple Music or Spotify. Live music can be disabled at any
time in the editor, and Automation access can be revoked in **System Settings → Privacy &
Security → Automation**.

The app's bundled privacy manifest declares no tracking or collected-data categories and
declares its local preferences use.
