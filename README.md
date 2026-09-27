# TAWIR (v3.0.0)

A Conversational Agent for Pangasinan Language Preservation.

This project is forked from https://github.com/qdwkdq/TAWIR.

## Overview

TAWIR is a cross-platform Flutter application built to preserve, promote, and facilitate fluent communication in the Pangasinan language (Salitan Pangasinan). It connects to a high-performance backend serving a fine-tuned Pangasinan LLaMA 3.1 8B language model and native MMS-TTS Pangasinan speech synthesis.

## Features

- Native Pangasinan Generation: Calibrated system prompts and decoding parameters to ensure pure Pangasinan output with zero Tagalog bleed.
- Direct Translation Handling: Clear and concise translation responses formatted as "Say patalos to et [translation]" in Pangasinan without repeating or echoing foreign input terms.
- High-Performance Audio Synthesis: Native Pangasinan text-to-speech powered by facebook/mms-tts-pag.
- Cross-Platform Support: Compatible with Android, Windows, Web, macOS, Linux, and iOS.
- OpenAI-Compatible API: Fully integrated with custom inference endpoints supporting /v1/chat/completions and /v1/tts.

## Getting Started

### Prerequisites

- Flutter SDK (v3.11.0 or higher)
- Android SDK / Windows Build Tools (depending on target platform)

### Installation

1. Clone this repository:
```bash
git clone https://github.com/rnl-devdump/tawir-colab.git
cd tawir-colab
```

2. Install dependencies:
```bash
flutter pub get
```

3. Run the application:
```bash
flutter run
```

### Building Releases

- Android APK:
```bash
flutter build apk --release
```

- Windows Executable:
```bash
flutter build windows --release
```

- Web Production Bundle:
```bash
flutter build web --release
```

## Attribution & Acknowledgments

This repository is forked from https://github.com/qdwkdq/TAWIR. All original structure and core foundations are credited to the original authors and contributors.
