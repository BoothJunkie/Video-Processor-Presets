
# Booth Junkie Video Processor Presets

Welcome to the Booth Junkie collection of custom **REAPER Video Processor presets**. These tools were crafted to help voice actors, editors, and content creators enhance their video workflows with animated waveforms, timers, motion text, audiograms, and more — all within REAPER.

Many of these presets rely on **JSFX: video sample peeker**, which makes it possible to visualize audio data in real-time via shared memory. Others are standalone and require no additional setup.

---

## 🔧 Installation Instructions

To install these video processor presets in REAPER:

1. **Open REAPER**, then go to `Track FX` and add the **Video Processor** to a video track.

2. In the **Video Processor** window, click the **Preset dropdown** at the top and choose:
   - `Import preset...` to load individual `.txt` files.
   - Or use `Show REAPER resource path...` to open your REAPER resource folder.

3. For presets labeled **"Requires JSFX: video sample peeker"**:
   - Ensure that the **JS: video sample peeker** is added *before* the Video Processor in the FX chain.
   - You can find it by searching `video sample peeker` when adding an FX.

4. For some presets, adding another instance of Video Processor with the built in preset called `Combine: Chroma Key (RGB version) will let video tracks underneath this track show through green-screen style. 

---

### Audiogram: Horizontal Bars
Displays a series of vertical bars that animate with audio amplitude, simulating a podcast-style audiogram. Uses shared memory from the JSFX "video sample peeker" to draw smoothed, gain-adjusted levels across the screen.

**Requires:** JSFX: video sample peeker (must be placed directly before this effect)

---

### Audiogram: Frequency Bars
Analyzes incoming audio with an FFT and displays real-time vertical bars representing frequency magnitudes across the spectrum. Features options for smoothing, logarithmic scaling, and bar spacing.

**Requires:** JSFX: video sample peeker (must be placed directly before this effect)

---

### Audiogram: Spectrum Analyzer
Creates a scrolling spectrogram along with a live frequency analyzer bar. FFT-based, with options for smoothing, hue customization, logarithmic frequency scaling, and mono mix input.

**Requires:** JSFX: video sample peeker (must be placed directly before this effect)

---

### Circular Waveform Visualizer (Animating Downward)
Displays a circular ring of waveform bars that radiate outward from the center, animating based on audio amplitude. Each bar represents a sample and moves based on waveform energy. The visual effect is dynamic and pulse-like.

**Requires:** JSFX: video sample peeker (must be placed directly before this effect)

---

### Countdown Effect
Displays a customizable countdown timer with hours, minutes, and seconds. Supports flashing on completion, positioning, and font control. Can optionally ignore input and just overlay on a blank background.

**Requires:** No JSFX required

---

### Smoothed Waveform with Angle
Draws a smoothed waveform along an arbitrary angle (e.g., diagonal or vertical). Supports polar modes, adjustable gain, smoothing, and full control over positioning and color.

**Requires:** JSFX: video sample peeker (must be placed directly before this effect)

---

 ### Smoothed Waveform with Orientation and Polar Options
Draws a linear audio waveform with support for both horizontal and vertical orientation. Includes multiple polar modes (bilateral, positive-only, negative-only, centered) and uses smoothing and gain control to refine the shape.

**Requires:** JSFX: video sample peeker

---

### Text Flicker or Pulse
Animates a block of text with rhythmic or randomized flicker/pulse effects. Supports opacity and scale-based animation modes. Useful for attention-grabbing countdowns, alerts, or stylized captions.

**Does not require JSFX**

---

### Text Jitter or Weave Effect
Applies motion animation to a text block using jitter (random) or weave (smooth sinusoidal) movement. Useful for creating a “shaky” or stylized moving text. Includes adjustable frequency, direction, and amplitude.

**Does not require JSFX**

---

### Text Weave Effect
Simulates subtle projector-style shake using sine-based weave motion in vertical or XY directions. Designed for vintage or analog emulation. Timing is quantized for a stop-motion feel. Highly customizable amplitude, direction, and update rate.

**Does not require JSFX**

---

### Timer Overlay
Displays an on-screen timer starting from the item’s beginning. Configurable format includes optional hours, minutes, seconds, and fractional seconds. Supports adjustable font, size, position, and background. Great for tutorials and voiceover timing.

**Does not require JSFX**

----



