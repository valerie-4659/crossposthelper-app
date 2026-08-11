# Crosspost Helper

A local-first image library and cross-posting helper for artists.

Crosspost Helper keeps your AI image library organised on your own machine, helps you choose what to post next, and makes sure each image only goes to the networks you actually intended. It is built for manual posting, careful review, and quiet duplicate protection — no accounts, no cloud sync, nothing leaves your computer unless you send it.

**[Download the latest release](https://github.com/valerie-4659/crossposthelper-app/releases/latest)** · [itch.io page](https://valerie-4659.itch.io/crossposthelper) · [Wiki](https://github.com/valerie-4659/crossposthelper-app/wiki)

## What it does

- **Library** — scans your image folders and indexes them locally. Prompt metadata, dominant colour and perceptual hashes are read out of the files themselves.
- **Picker** — surfaces what to post next instead of making you scroll.
- **AI Post** — drafts a caption from the image, with separate controls for how explicit and how it sounds, and tells you what the settings will produce before you spend anything.
- **Duplicate protection** — remembers what already went where, per network.
- **Browser extension** — hands the image and text to the posting page; you press send.

## Install

Download the build for your platform from the [latest release](https://github.com/valerie-4659/crossposthelper-app/releases/latest).

| Platform | File |
|---|---|
| macOS | `.dmg` |
| Windows | `.exe` |
| Linux | `.AppImage` |

### The builds are unsigned

There is no Apple Developer ID and no Windows code-signing certificate behind these builds, so the operating system will warn you the first time you open one.

- **macOS** — Gatekeeper will refuse the first launch. Right-click the app → **Open**, then confirm. Or allow it under System Settings → Privacy & Security.
- **Windows** — SmartScreen shows a blue warning. **More info** → **Run anyway**.

This is what an unsigned build looks like; it is not a sign that anything is wrong with the download. If you would rather not take that on trust, the [itch.io app](https://itch.io/app) installs and updates it for you.

## Support

- **Something broken?** [Open an issue](https://github.com/valerie-4659/crossposthelper-app/issues) — include your platform, the app version from the sidebar, and what you did just before it went wrong.
- **How do I…?** The [Wiki](https://github.com/valerie-4659/crossposthelper-app/wiki) covers installation, FAQ and troubleshooting.

## Privacy

Everything stays on your machine: the image index, the post history and your settings all live in a local database. There is no account and no telemetry. The app reaches the network in exactly three cases — when you ask an AI provider for a caption using your own API key, when it checks this page for a newer version, and when you send a post.

## Source

This repository carries the releases, the wiki and the issue tracker. The source is not public.
