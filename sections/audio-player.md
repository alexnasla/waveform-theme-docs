# Audio player

Inline audio demos with seekable waveform bars — play real product audio on any page.

> **Tip:** Each block is one track. Upload MP3s to Files and paste the URL; keep demos under 60 seconds for snappy loading.

**File:** `sections/audio-player.liquid` · Add anywhere via **Theme editor → Add section**.

## Settings

| Setting | Type | Default | Notes |
| --- | --- | --- | --- |
| Cover art | `image_picker` |  |  |
| Title | `text` | Nebula — Evolving Pad |  |
| Subtitle | `text` | Granular texture engine · demo reel |  |
| **Spacing & style** | | | |
| Top padding | `range` | 72 | 0–160 px. |
| Bottom padding | `range` | 72 | 0–160 px. |
| Section background | `select` | default | Options: Default (page background) / Subtle / Panel / Accent tint / Inverse (dark band). |
| Animate on scroll | `checkbox` | on | Fade/slide this section in. Requires Theme settings → Animations to be on. |

## Block: Track (`track`)

| Setting | Type | Default | Notes |
| --- | --- | --- | --- |
| Track name | `text` | Evolving Pad |  |
| Duration (optional) | `text` | 2:14 |  |
| Audio file URL | `url` |  | Upload your MP3 or WAV under Content → Files, open the file, copy its URL, and paste it here — the track length fills in automatically. No file yet? The waveform still animates as a silent visual demo. |

_Maximum blocks: 8_
