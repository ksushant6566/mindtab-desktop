# MindTab for Mac

Public downloads for the MindTab desktop app. Grab the latest universal installer under [Releases](https://github.com/ksushant6566/mindtab-desktop/releases).

## Install

1. Download `MindTab-<version>-universal.dmg` (one build for Apple Silicon and Intel, macOS 13 Ventura or later).
2. Open the DMG and drag **MindTab** to Applications.
3. Launch MindTab and sign in with Google or email.

The app updates itself: new versions download in the background and install on restart.

## Verify your download

Each release ships a `SHA256SUMS.txt`. From the folder containing the DMG:

```sh
shasum -a 256 -c SHA256SUMS.txt
```

Releases are signed with a Developer ID certificate and notarized by Apple.

---

The application source is maintained separately in a private repository. This repository contains public release artifacts only.
