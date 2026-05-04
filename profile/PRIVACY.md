# Privacy Policy

**Last updated:** May 4, 2026

Moss Apps software is developed by **Ultra Electronica** ("we", "us", or "our"). This Privacy Policy explains how our applications handle data and user privacy. By using any of our applications, you agree to the terms described here.

Privacy is a core principle, not an afterthought. Every Moss app is built to keep your data on your device, under your control.

---

## Flick Player

### Data Collection

Flick Player does not collect, store, or transmit personal data. No name, email, phone number, location, device identifiers, usage analytics, advertising IDs, or crash reports ever leave your device.

### Local Data

Everything Flick Player generates or uses is stored locally:

- Music library metadata (ID3 tags, Vorbis comments) extracted from your files
- Play history (recently played tracks, play counts)
- User-created playlists
- Equalizer presets and settings
- App preferences (theme, playback settings)
- Last.fm scrobbling credentials (stored via Flutter Secure Storage)

None of this data leaves your device unless you explicitly opt into an integration listed below.

### Camera and Photos

Flick Player requests camera and photo library access solely for the **Flick Replay** feature, which generates listening recap posters.

- **Camera access** — used only when you choose to take a photo for a custom poster background
- **Photo library access** — used only when you select an existing photo as a poster background or when saving generated recap images to your gallery
- No photos or camera images are uploaded, transmitted, or stored off-device
- These features are opt-in; denying camera/photo permissions does not affect core playback, library management, or equalizer functionality

### Storage Permissions

Storage access is required to:

- Scan and read music files from your local storage
- Read audio metadata (tags, album art, lyrics)
- Import/export equalizer presets
- Save recap images to your gallery

No files are uploaded or transmitted externally.

### USB Device Access

Flick Player accesses USB Audio Class 2.0 (UAC 2.0) devices (external DACs/AMPs) for bit-perfect audio playback. USB device enumeration happens locally. No device information is transmitted externally.

### Third-Party Integrations

**Last.fm Scrobbling** (opt-in):

- Your Last.fm username and password are stored securely on-device
- Play data (artist, track, album, timestamp) is sent only to Last.fm for scrobbling
- We do not receive, store, or process scrobble data

**Album Art Import**:

- The App queries public APIs (MusicBrainz/Cover Art Archive, iTunes, Deezer) to find matching album art based on local metadata
- Downloaded images are cached locally
- No personal data is sent to these services

**In-App Updates**:

- Play Store updates use the Google Play In-App Update API, governed by Google's privacy policies
- Patch notes are fetched from the GitHub Releases API; no personal data is sent

### Internet Access

Flick Player uses the internet only for fetching album art, Last.fm scrobbling (if enabled), checking for updates, and fetching patch notes. No personal data is transmitted during these operations beyond what each feature requires.

---

## Locker

### Data Collection

Locker does not collect, store, transmit, or share any personal information. No name, email, phone number, usage analytics, telemetry, crash diagnostics, advertising identifiers, location data, device identifiers, contacts, messages, call logs, browsing history, or app usage data ever leaves your device.

### Camera Access

Locker requests camera permission only when you choose to scan a QR code or capture a photo for your vault. Camera access is never used in the background. No photos or video are transmitted to any server. All captured media is stored locally and encrypted on your device.

### Media & Files

Files you import into Locker are encrypted using AES-256 and stored locally. We do not:

- Upload your files to any cloud or server
- Scan or analyze your files
- Share your files with any third party
- Access your files without your explicit action

Your vault key never leaves your device.

### Storage Permission

Locker requires storage permission to read files you want to vault and to save encrypted files to your device. This permission is used only when you explicitly choose to import or export files.

### Biometric Authentication

If you enable fingerprint or face unlock, biometric data is handled entirely by your device operating system. Locker only receives a success/failure signal — it never stores or accesses your biometric data.

### Local Backups

If you create a local backup, the backup file is saved to a location you choose on your device. Locker does not upload backups anywhere. You are responsible for securing your backup files.

### Third-Party Services

Locker does not integrate with any third-party analytics, advertising, or tracking services. The only external connections are:

- Play Store update check (optional, triggered by you)
- Donation link to Ko-fi (optional, opened in your browser)

Neither transmits personal data from Locker.

---

## Moss Ecosystem Integration

Flick Player and Locker are part of the Moss ecosystem. Flick Player can receive playback handoffs from Locker:

- Playback intents contain only song file paths and metadata needed for playback
- No personal data is exchanged between apps
- The integration is entirely local on your device

---

## Moss Web

The Moss Web landing page and informational site does not use tracking cookies, analytics scripts, or fingerprinting. No visitor data is collected.

---

## Children's Privacy

Our applications do not collect any information from anyone, regardless of age. Since no data is collected at all, there is no risk of personal information being gathered from minors.

---

## Changes to This Policy

We may update this Privacy Policy from time to time. Changes will be reflected in the "Last updated" date at the top of this document and noted in the relevant app's release notes. We encourage you to review this policy periodically.

---

## Contact

For privacy-related questions or concerns:

- **GitHub**: [github.com/moss-apps](https://github.com/moss-apps)
- **Email**: [Your contact email]

---

*Moss Apps software is open-source under the MIT License. You can review the source code to verify the claims made in this Privacy Policy.*
