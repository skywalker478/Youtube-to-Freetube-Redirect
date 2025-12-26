# Youtube to Freetube Redirect

Redirects YouTube links to your local FreeTube instance for private, ad-free viewing.

![Firefox Extension](https://img.shields.io/badge/Firefox-FF7139?style=flat&logo=firefoxhttps://img.shields.io/amo/v/youtube-to-freetube-redirect.svg?colorhttps://addons.mozilla.org/firefox/addon/youtube-to-freetube-redirect

- Automatically redirects `youtube.com` to FreeTube
- Works on all YouTube pages (watch, search, channel, etc.)
- Privacy-focused—no telemetry or data collection
- Lightweight (minimal permissions)

## Installation

### Step 1: Install FreeTube
Download and install [FreeTube](https://freetubeapp.io/) for your platform:

| Platform | Download |
|----------|----------|
| [Windows](https://github.com/FreeTubeApp/FreeTube/releases/latest/download/FreeTube-Windows-x64.zip) | `.zip` |
| [macOS](https://github.com/FreeTubeApp/FreeTube/releases/latest/download/FreeTube-macOS-x64.zip) | `.zip` |
| [Linux AppImage](https://github.com/FreeTubeApp/FreeTube/releases/latest/download/FreeTube-linux-x86_64.0.17.0.AppImage) | `.AppImage` |
| [Flatpak](https://flathub.org/apps/io.freetubeapp.FreeTube) | `flatpak install flathub io.freetubeapp.FreeTube` |

### Step 2: Install Extension

**Option A: Firefox Add-ons Store (Recommended)**
<a href="https://addons.mozilla.org/firefox/addon/youtube-to-freetube-redirect/"><img src="https://img.shields.io/badge/Install%20from%20AMO-orange?style=flat&logo=firefox&logoColor=white" alt="Get it from Firefox Add-ons"></a>

**Option B: Manual Install (Latest)**
1. Download `.xpi` from [Releases](https://github.com/YOURUSERNAME/youtube_to_freetube_redirect/releases)
2. Firefox → `about:addons` → Drag & drop `.xpi` → "Add"

## Configuration

No setup required! Configure FreeTube port in Firefox settings if different from default (usually `1080` or `1084`).

## Screenshots

![Before/After redirect](screenshots/redirect-demoTube Setup

Ensure FreeTube external API is enabled:
```
Settings → Advanced → External Player → Enable API (port 1080)
```

## Development

```bash
# Install dependencies
npm install -g web-ext

# Run locally for testing
web-ext run

# Build & sign for distribution
web-ext sign --channel=unlisted
```

## License

MIT © [Your Name](https://github.com/skywalker478)
