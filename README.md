# Spoiler Guard for YouTube

A Chrome extension that blurs or hides potential spoilers and hints in YouTube comments and chat replays. It combines a shared blocklist with personal rules to help protect a first-time viewing experience.

[Install from the Chrome Web Store](https://chromewebstore.google.com/detail/filikhhcifickcnnihlahniajlhbokbl) · [Official website](https://spoiler.gussuriworks.com/) · [GitHub Releases](https://github.com/gussuri/spoiler-guard-extension/releases/latest)

For normal use, install Spoiler Guard from the Chrome Web Store, the official installation method for regular users with automatic updates. GitHub release ZIPs are provided for testing and verification only.

## Features

- Blur or hide ordinary YouTube comments and chat replays
- Automatically retrieve shared blocklists for supported videos
- Add personal blocking rules, such as keywords
- Show why an item was hidden and temporarily reveal it
- Curator features to help create and share lists
- Japanese and English UI

## Installation

### Chrome Web Store

[Add the extension from the Chrome Web Store](https://chromewebstore.google.com/detail/filikhhcifickcnnihlahniajlhbokbl). Updates are delivered automatically.

### Manual installation for testing

Manual installation is intended for testing and verification. For normal use, install the extension from the Chrome Web Store to receive automatic updates.

GitHub Releases provide release history and ZIP packages for testing and verification. Use the <code>spoiler-guard-vX.Y.Z.zip</code> attached to the [latest GitHub Release](https://github.com/gussuri/spoiler-guard-extension/releases/latest).

1. Download and extract the ZIP file.
2. Open <code>chrome://extensions/</code> in Chrome.
3. Enable **Developer mode**.
4. Select **Load unpacked**.
5. Choose the extracted <code>spoiler-guard-vX.Y.Z</code> folder.

## Supported environment and scope

- Designed for desktop Chromium-based browsers.
- Check the supported works and videos for shared blocklists on the [official website](https://spoiler.gussuriworks.com/).
- Personal rules can be used even for videos without a shared list.
- Mobile YouTube is not supported.

## Permissions and privacy

| Permission / endpoint | Purpose |
| --- | --- |
| <code>storage</code> | Store settings and personal rules in the browser |
| <code>tabs</code> | Integrate with open YouTube videos and open the settings screen or official website |
| <code>youtube.com</code> | Inspect comments and chat replays on screen and control their display |
| <code>spoiler.gussuriworks.com</code> | Retrieve shared blocklists for supported videos |

Normal blocking is performed locally in the browser. Viewed comment text, author names, and watch history are not automatically sent. Data that users save or submit through list creation and sharing features is handled according to the [official website's privacy notice](https://spoiler.gussuriworks.com/privacy/).

## Limitations

- It cannot completely prevent all spoilers.
- Ordinary comments may be hidden depending on the context.
- Changes to YouTube's page structure may temporarily break the extension.
- This is not an official YouTube or Google extension.

## Contact

Please use [GitHub Issues](https://github.com/gussuri/spoiler-guard-extension/issues) for bug reports and feature requests. For supported videos and shared lists, also check the [official website](https://spoiler.gussuriworks.com/).

## About this repository

This repository is used to distribute ZIP packages for testing and verification and to publish public release information. Development and verification repositories, evaluation data, experimental code, and local secrets are not published here.

This repository is not distributed under an open-source license. No rights to copy, modify, or redistribute its contents are granted except where explicitly permitted.
