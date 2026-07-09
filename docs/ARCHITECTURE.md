# HitroCut Architecture

## Overview

HitroCut consists of six major components.

```
Premiere Pro

↓

Extension UI

↓

Audio Engine

↓

AI Engine

↓

Decision Engine

↓

Timeline Engine

↓

Premiere Timeline
```

---

## Components

### Extension UI

Responsible for:

- Settings
- Buttons
- Progress
- Review Screen

---

### Audio Engine

Responsible for:

- Export audio
- WAV conversion
- Audio preprocessing

---

### AI Engine

Responsible for:

- Connecting to AI providers
- Uploading audio
- Receiving edit suggestions

Supported providers

- OpenAI
- Gemini
- Claude

---

### Decision Engine

Responsible for:

- Validating AI response

- Confidence scores

- Safety checks

- Review generation

---

### Timeline Engine

Responsible for

- Razor cuts

- Ripple delete

- Crossfade

- J-Cut

- L-Cut

---

### Settings

Stores

- Provider

- API key

- Preferences
