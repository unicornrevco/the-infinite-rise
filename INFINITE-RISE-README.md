# 🌟 The Infinite Rise
### An Ascending Fractal Sound Experience

> *"Where mathematics ascends into music — the world's first upward fractal audiovisual experience."*

---

## Concept

Most fractal videos zoom **inward** — descending endlessly into mathematical void, paired with falling, unsettling tones. **The Infinite Rise** inverts this entirely.

This project zooms **outward** from deep within a fractal, while procedurally generated sound **ascends** in pitch, harmony, and fullness — creating an experience of uplift, revelation, and infinite ascent.

**Potentially the first audiovisual work of its kind.**

---

## Features

- 🔭 **5 Fractal Types** — Mandelbrot, Burning Ship, Feather, Tricorn, Phoenix
- 🎵 **6 Sound Voices** — switchable live during playback
  - ✦ Angelic Choir
  - ♜ Cathedral Organ
  - ♪ Crystal Piano
  - ◎ Tibetan Bowls
  - 〜 Orchestral Strings
  - ◈ Ethereal Synth
- 🎨 **Per-fractal color palettes** that warm and brighten as you ascend
- ✨ **Rising particle system** — golden motes float upward during ascent
- 📊 **Live HUD** — zoom level, harmonic stage, ascent percentage, elapsed time
- ⚡ **Speed control** — 1×, 2×, 4× playback
- 🔄 **Live voice switching** — change sound mid-experience without stopping
- 🎮 **Pause / Restart** controls

---

## Usage

### Browser (Zero Install)
```
Open index.html in any modern browser (Chrome, Firefox, Safari, Edge)
Tap "Begin the Ascent" to unlock audio
Sit back and ascend
```

### For Museum / Display Installation
- Recommended: 90"+ display at 4K
- Browser: Chrome in fullscreen (`F11`)
- Audio: Connect to quality speaker system before opening
- Loop: Use the "Begin Again" button at completion
- Tablet demo: Works on iPad/Android tablet in landscape orientation

---

## Architecture

```
infinite-rise/
├── index.html          ← Complete self-contained app (no dependencies)
├── README.md           ← This file
├── LICENSE.md          ← IP License
├── PITCH.md            ← Pitch deck content
└── TIMESTAMP.md        ← Creation timestamp & provenance record
```

**No build tools. No npm. No frameworks.** Pure HTML5 + Canvas 2D + Web Audio API.

---

## Technical Stack

| Layer | Technology |
|-------|-----------|
| Fractal Rendering | HTML5 Canvas 2D, custom iteration engine |
| Audio Synthesis | Web Audio API (OscillatorNode, BiquadFilterNode, ConvolverNode) |
| Reverb | Algorithmically generated impulse response |
| Animation | requestAnimationFrame loop |
| Particles | Canvas 2D particle system |
| Fonts | Google Fonts (Cinzel Decorative, Cormorant Garamond) |

---

## Fractal Details

| Fractal | Formula | Audio Character | Visual Palette |
|---------|---------|----------------|----------------|
| Mandelbrot | z² + c | Warm, full harmonic | Indigo → Gold → White |
| Burning Ship | \|Re(z)\| + i\|Im(z)\|)² + c | Dramatic, intense | Deep Red → Orange → Gold |
| Feather | z³/\|z³\| + c | Melodic, many tones | Teal → Cyan → White |
| Tricorn | z̄² + c | Ethereal, mysterious | Purple → Violet → Rose |
| Phoenix | z² + c + p·prev | Organic, breathing | Emerald → Lime → Gold |

---

## Sound Voice Architecture

Each voice uses a different synthesis approach:

- **Choir** — Pure sine waves + vibrato LFO, staggered entry, long reverb
- **Organ** — Detuned sawtooth pairs per harmonic
- **Piano** — Triangle oscillators with fast attack, exponential decay, arpeggiated
- **Bowls** — Triple-detuned sines per note creating natural beating
- **Strings** — Filtered sawtooth + tremolo LFO
- **Synth** — Square wave + resonant lowpass filter + slow LFO sweep

All voices share a global reverb bus (algorithmically generated impulse response) and pitch-rise over the full ascent (~1 octave over the full journey).

---

## Roadmap / Future Development

- [ ] WebGL GPU rendering for real-time 4K quality
- [ ] MIDI output for live performance use
- [ ] Export to video (WebCodecs API)
- [ ] Julia set variants per fractal
- [ ] User-adjustable zoom start point (click to begin there)
- [ ] Binaural audio mode
- [ ] VR/WebXR immersive mode

---

## Timestamp & Provenance

See `TIMESTAMP.md` for full creation record establishing intellectual property origin.

---

## License

See `LICENSE.md` for full terms.

*© 2026 The Infinite Rise Project. All rights reserved.*
