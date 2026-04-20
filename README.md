# Gemini Chat Exporter

A Chrome extension that lets you export your Google Gemini conversations in multiple formats with one click.

![Chrome Extension](https://img.shields.io/badge/Chrome-Extension-4285F4?logo=googlechrome&logoColor=white)
![Manifest V3](https://img.shields.io/badge/Manifest-V3-blue)

## Features

- **One-click export** — Open a Gemini chat, click the extension, choose your format, done.
- **5 export formats:** JSON, Markdown, Plain Text, CSV, and PDF.
- **Full conversation capture** — Automatically scrolls to load your entire chat history, no matter how long.
- **Metadata included** — Optionally includes chat title, export date, and source URL.
- **Dark mode support** — Automatically matches your system theme.
- **Privacy-first** — Everything runs locally. Your chats never leave your browser.

## Installation

1. **[Download the latest release](https://github.com/Nkbros12k/gemini-chat-exporter/releases/latest)** and unzip it.
2. Open `chrome://extensions/` in Chrome.
3. Enable **Developer Mode** (toggle in the top-right corner).
4. Click **Load unpacked** and select the unzipped folder.
5. Pin the extension from the puzzle piece icon in your toolbar.

## Usage

1. Go to [gemini.google.com](https://gemini.google.com) and open any conversation.
2. Click the **Gemini Exporter** icon in your toolbar.
3. Choose your export format and options.
4. Click **Export Chat** — the file downloads automatically.

Long conversations may take 30-60 seconds to fully capture.

## How It Works

1. Open any conversation on Gemini.
2. Click the extension icon, pick your format, hit **Export Chat**.
3. The extension captures your full conversation — even long ones that need scrolling.
4. Your file downloads instantly. Nothing is sent to any server.

## Troubleshooting

| Problem | Solution |
|---------|----------|
| "No messages found" | Make sure a conversation is open (not the Gemini home page). Try refreshing the page. |
| Extension icon is grayed out | You're not on `gemini.google.com`. Navigate there first. |
| Missing older messages | Make sure "Capture entire conversation" is toggled on. |
| PDF looks basic | For richer formatting, export as Markdown and convert with a tool like Pandoc. |

## Feedback & Bug Reports

Found a bug or have a feature request? Open an [issue](https://github.com/Nkbros12k/gemini-chat-exporter/issues) and we'll look into it.

## Security & Privacy

This extension:
- Runs entirely in your browser.
- Does not collect, transmit, or store any data.
- Has no analytics, telemetry, or tracking.
- [VirusTotal scan](https://www.virustotal.com/gui/file/ed20a1e6a1c34a621a05e1cd550613e700e015c5ee99830a1ef70f604132b8e0?nocache=1) — clean, zero detections.

## License

This software is proprietary. All rights reserved. See [LICENSE](LICENSE) for details.

You may use this extension for personal use. Redistribution, modification, or commercial use of the source code is not permitted without written permission.
