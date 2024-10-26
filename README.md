# SightXR Chrome Extension

Forked from https://github.com/rNeomy/reader-view.

## Features

- Strips away clutter like buttons, background images, and changes the page's text size, contrast, and layout for better readability.
- Send text content to a SightXR instance.

## Install

1. Download latest release from https://github.com/Kineviz/sightxr-chrome-extension/releases.
2. Unzip the release.
3. In your browser, visit the URL `chrome://extensions/`
4. Enable "Developer mode". (it's a toggle in the top right corner)
5. Click "Load unpacked". (button in top left)
6. Select folder containing file "manifest.json".
7. Pin the SightXR Chrome Extension by clicking the Extensions button in the URL Bar and then clicking the Pin button.

## Usage

First we point it at our SightXR Instance.

1. Right click on the SightXR Chrome Extension icon.
2. Click "Options"
3. Set Base URL to your SightXR API url, which is typically at port 8000: `https://my-instance.net:8000` (change to match yours. e.g. `https://my-instance.tail93a2.ts.net:8000`)
4. Set API Key.
5. Scroll down, then click `Save Options`

Now we can push a web page to our SightXR Instance.

1. Navigate to an article and click the SightXR Chrome Extension button.
2. Click the lavender "Send to SightXR" button in the left sidebar.
