# VoiceForge Summary

**VoiceForge** is a free, browser-based **Hindi & English Text-to-Speech (TTS) Studio** with a clean, modern UI. Here are the key features:

## Core Capabilities
- **Multiple TTS Providers**:
  - **Sarvam AI** (bulbul:v3) — Premium Hindi/Indian languages via API
  - **IndicF5** — Local/Colab-hosted model with voice cloning support
  - **Puter.js** — Free English TTS (no API key needed)
  - **Browser TTS** — Native OS voices

- **Playback Controls**: Play, pause, stop, speed adjustment (0.5× to 2.0×), progress tracking
- **Live Segment Display**: Text breaks into sentences; each segment highlights during playback; click any to jump

## Input & Output
- **Text Input**: Support for Hindi & English with character counter (100k char free limit)
- **Download Modal**: Export audio in WAV, MP3, FLAC, or OPUS format
- **Voice Selector**: 7 Sarvam voices (Suhani, Anushka, Abhilash, etc.) + configurable browser/Puter voices

## Technical Highlights
- **Dark/Light Theme** toggle with persistent localStorage
- **Responsive Design**: Mobile-friendly (breaks below 600px)
- **Provider Persistence**: Saves API keys & server URLs in browser storage
- **Reference Audio Upload**: For IndicF5 voice cloning
- **dwani-server Detection**: Auto-detects dwani-ai/tts-indic-server vs original IndicF5

## UI Components
- Sticky navbar with status indicator
- Cards for API config, playback controls, text input, live playback, and download modal
- Tailwind CSS + custom CSS variables for theming
- Toast notifications for user feedback

**Designed for Indian language TTS enthusiasts** — no installation needed, runs entirely in browser.
