# Video Processor Presets

This folder contains custom **Video Processor Presets** for REAPER, developed to enhance audio-driven visual workflows, especially for voiceover demos, podcasts, and other longform content. These presets integrate with REAPER’s built-in Video Processor and offer creative, audio-reactive text and timing tools.

These presets are part of the **Booth Junkie Tools** ReaPack collection.

---

## Installation via ReaPack

If you're using [ReaPack](https://www.reapack.com/):

1. In REAPER, go to `Extensions > ReaPack > Import repositories`.
2. Paste the URL to the Booth Junkie Tools index:

https://github.com/YOUR_USERNAME/YOUR_REPO/raw/main/index.xml


3. Hit OK, then synchronize via `Extensions > ReaPack > Synchronize packages`.

The presets in this folder will appear in REAPER’s **Video Processor** effect under the names listed below.

---

## Text Presets Presets

| Preset Name             | Description                                                                 |
|-------------------------|-----------------------------------------------------------------------------|
| `Text Flicker or Pulse` | Random or regular text flickering of text, simulating a glitchy backlight. |
| `Text Jitter or Weave`  | Configurable weave or High-frequency jitter for glitchy or energetic text effects.                |
| `Text Weave Effect`     | Gently oscillating text for meditative or ambient content. Inspired by film projector weave                |
| `Countdown Effect`      | Adds a visual countdown timer, flashes 00:00 when countdown finishes.            |
| `Timer Overlay`         | Adds a visual  timer synced to the length of the item.            |

#Visualization PResets                                                             |

| Preset Name               | Description                                                                |
|---------------------------|----------------------------------------------------------------------------|
| `Audiogram: Horizontal Bars` | Displays a smoothed, real-time waveform using horizontal vertical bars. Requires `JS: video sample peeker`. |

---

## Usage

1. Add a video track containing your audio or video.
2. Click the FX button on the track.
3. Add the **Video Processor** plugin.
4. Click the `Presets` dropdown and choose the desired preset (e.g., `Pulse Text`).
5. Adjust parameters in the FX chain to control behavior, color, animation speed, etc.

For audio-reactive presets (like `Pulse Text`), ensure you insert the JSFX:
- `JS: video sample peeker`
...**before** the Video Processor in the FX chain.

---

## Requirements

- REAPER v6.0 or later
- REAPER stock plugin: `JS: video sample peeker` (required for audio-reactive effects)

---

## License

These presets are provided under the MIT License. See the main repository’s `LICENSE` file for details.

---

## Credits

Developed by [Booth Junkie](https://www.youtube.com/@BoothJunkie)  
Contributions welcome via GitHub pull request.
