# VidSynth — Releases

> Official release downloads for VidSynth by KeyStack Studio LLC.

---

## Download

### Latest Release
Head to the [**Releases**](https://github.com/KeyStack-Studio/VidSynth-Releases/releases/latest) page to download the latest version of VidSynth.

| Platform | Status | Download |
|---|---|---|
| **Windows** | ✅ Available | [Download latest](https://github.com/KeyStack-Studio/VidSynth-Releases/releases/latest) |
| **Mac** | 🔜 Coming Soon | — |

**VidSynth is free to download and use.** Get your free license key at [vidsynth.xyz](https://vidsynth.xyz) — takes 30 seconds, no credit card required.

---

## What is VidSynth?

VidSynth is an AI-powered desktop application that transforms any video into a structured, professional PDF report in minutes.

Upload a local video file or paste a YouTube URL — VidSynth automatically:

- 🎙️ **Transcribes** the audio locally using Whisper (private, no API key required)
- 🤖 **Analyzes** the content using your choice of Claude, GPT-4o, or Gemini
- 📸 **Captures screenshots** at key moments, reviewed by AI for relevance
- 📄 **Generates a PDF report** containing:
  - Executive Summary
  - Key Points
  - Decisions Made
  - Action Items with owners
  - Detailed breakdown with embedded screenshots

Works with meetings, training videos, presentations, interviews, YouTube videos, and more.

---

## Installation

### Windows

1. Download `VidSynth-Setup-vX.X.X.exe` from the [latest release](https://github.com/KeyStack-Studio/VidSynth-Releases/releases/latest)
2. Run the installer
3. Follow the setup wizard
4. Launch VidSynth from your desktop shortcut
5. Enter your license key on first launch

> **Note:** Windows may show a SmartScreen warning on first run. Click **More info → Run anyway**. VidSynth is safe — the warning appears because the app is newly published and not yet widely distributed.

---

## Requirements

### System Requirements

| Component | Minimum | Recommended |
|---|---|---|
| OS | Windows 10 64-bit | Windows 11 64-bit |
| RAM | 4GB | 8GB+ |
| Storage | 2GB free | 5GB free |
| Internet | Required for AI analysis | Broadband |

### API Key Requirements

VidSynth requires an API key from at least one AI provider for analysis:

| Provider | Get API Key | Estimated Cost Per Video |
|---|---|---|
| **Anthropic Claude** (recommended) | [console.anthropic.com](https://console.anthropic.com) | ~$0.06–0.24 |
| **OpenAI GPT-4o** | [platform.openai.com](https://platform.openai.com) | ~$0.05–0.20 |
| **Google Gemini** | [aistudio.google.com](https://aistudio.google.com) | ~$0.01–0.05 |

> API usage costs are separate from your VidSynth license and billed directly by your chosen provider. Typical usage for a 17-minute video costs less than $0.25.

### Optional: Deepgram (Enhanced Transcription)
For speaker labels and higher accuracy transcription:
- Get a free API key at [console.deepgram.com](https://console.deepgram.com)
- Not required — Whisper local transcription works without any key

---

## Licensing

**VidSynth is free.** Get your license key in seconds and start using it immediately — no payment, no credit card, no trial period.

### How to Get Your Free License Key

1. Go to **[vidsynth.xyz](https://vidsynth.xyz)**
2. Click **Get Free License**
3. Enter your email — a free license key is generated instantly via Lemon Squeezy
4. Enter the key in VidSynth on first launch
5. You're in

### License Terms
- Free license activates on **one device**
- To move to a new machine: **Help → Deactivate This Device** then reactivate
- Free license includes all v1.x updates automatically
- Bring your own API key from Anthropic, OpenAI, or Google
- Optional: upgrade to a managed subscription — no personal API key needed

### Optional — Managed API Tier (WIP)
Don't want to manage your own API key? Subscribe to a managed plan:

| Plan | Price | Minutes/mo | Approx Videos |
|---|---|---|---|
| Starter | $9.99/mo | 250 min | ~17 videos |
| Pro | $19.99/mo | 600 min | ~35 videos |
| Business | $39.99/mo | 1,200 min | ~70 videos |
| Team | $79.99/mo | 2,500 min | ~147 videos |

Top-up credit packs also available for occasional use.

**[View all plans at vidsynth.xyz](https://vidsynth.xyz)**

---

## Updates

VidSynth checks for updates automatically on launch.

When an update is available you'll see a notification inside the app. Click to download and install — no manual steps needed.

You can also check manually: **Help → Check for Updates**

### Update Types
| Version Pattern | Update Type | Download Size |
|---|---|---|
| x.x.1, x.x.2 (patch) | Bug fixes | Small (~10-20MB) |
| x.1.0, x.2.0 (minor) | New features | Full installer |
| 2.0.0, 3.0.0 (major) | Major release | Full installer |

---

## Privacy

VidSynth is designed with privacy as a core principle:

- 🔒 **Audio transcription** via Whisper runs entirely on your machine — no audio ever leaves your device
- 📝 **Text transcript** is sent to your chosen AI provider for analysis
- 📸 **Screenshots** (if enabled) are sent to your AI provider for visual review — you can disable this in settings to keep all image data local
- 🚫 **No analytics** — VidSynth does not collect usage data or personal information
- 🔑 **API keys** stored locally on your machine only — never transmitted to KeyStack Studio

All data sent during analysis goes directly to your chosen AI provider (Anthropic, OpenAI, or Google) and is subject to their privacy policies.

---

## Support

| Issue | Contact |
|---|---|
| Bug reports | [Open an issue](https://github.com/KeyStack-Studio/VidSynth-Releases/issues) |
| License issues | trevor@keystackstudio.com |
| General questions | trevor@keystackstudio.com |
| Feature requests | [Open an issue](https://github.com/KeyStack-Studio/VidSynth-Releases/issues) |

**Response time:** Within 48 hours on business days.

---

## Changelog

Full release notes are available on the [Releases](https://github.com/KeyStack-Studio/VidSynth-Releases/releases) page.

### Recent Releases

#### v1.0.1
- Added automatic update notifications
- Added anonymous crash reporting via Sentry (opt-out available in Settings)
- Improved error messages throughout
- General stability improvements

#### v1.0.0
- Initial release
- Local video file upload
- YouTube URL support
- Whisper local transcription
- Deepgram cloud transcription with speaker labels
- Anthropic Claude, OpenAI GPT-4o, Google Gemini support
- AI screenshot capture and review
- PDF report generation
- Executive Summary, Key Points, Decisions, Action Items
- Detailed breakdown with embedded screenshots
- Content-aware analysis (meeting, training, presentation, interview)
- Lemon Squeezy license key activation
- Feature flags system
- Auto-update system

---

## Roadmap

| Feature | Status |
|---|---|
| Windows version | ✅ Available |
| Free license via Lemon Squeezy | ✅ Available |
| Mac version | 🔜 In development |
| Managed API (no personal key needed) | 📋 Planned |
| Google Meet native integration | 📋 Planned |
| Microsoft Teams native integration | 📋 Planned |
| Local AI model support (Ollama) | 📋 Planned |
| HTML report with video clips | 📋 Planned v2 |

Full roadmap: [vidsynth.xyz/roadmap](https://vidsynth.xyz/roadmap)

---

## About KeyStack Studio

VidSynth is built by **KeyStack Studio LLC**, an independent software studio based in California.

- 🌐 [keystackstudio.com](https://keystackstudio.com)
- 🎬 [vidsynth.xyz](https://vidsynth.xyz)
- 📊 [finlit.day](https://finlit.day)
- 🤖 [aioverlordsim.com](https://aioverlordsim.com)
- 💌 trevor@keystackstudio.com

---

*This repository contains release builds only. For bug reports and feature requests please [open an issue](https://github.com/KeyStack-Studio/VidSynth-Releases/issues).*

*© 2026 KeyStack Studio LLC. All rights reserved.*
