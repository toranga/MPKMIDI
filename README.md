# MPKMIDI

A browser-based synth and drum player for the **AKAI MPK mini**, built on the Web MIDI API. No install, no drivers, no DAW.

## Use it

**Live version:** https://toranga.github.io/MPKMIDI/ (open in Chrome or Edge)

1. Plug the MPK mini into your computer over USB.
2. Open `index.html` in **Chrome** or **Edge**. Safari doesn't support Web MIDI, and Firefox needs an add-on.
3. Click **Start**, then **Allow** MIDI access when the browser asks.

## Controls (MPK mini mk3 defaults)

| Control | What it does |
|---|---|
| Keys (channel 1) | Synth: saw lead, square, triangle, sine, or e-piano |
| Pads (channel 10, notes 36–51) | 16 synthesized drum sounds |
| Knobs K1–K8 (CC 70–77) | Filter, resonance, attack, release, detune, delay, synth volume, drum volume |
| Joystick X | Pitch bend |
| Joystick Y / CC1 | Vibrato |
| Sustain pedal (CC64) | Sustain |

## Sequencer

A one-bar 4/4 step sequencer (16 sixteenth-note steps) under the keyboard:

- **Notes grid**: 13 rows (one octave plus the top note). Pick the octave with *Notes octave*. Cells next to each other in a row play as one longer note.
- **Drums grid**: the 8 on-screen drums.
- Click or drag to draw, **Space** or the button to play/stop, set the tempo in BPM. The pattern is saved in the browser.

### Pads not making sound?

- Make sure the **CC** and **PROG CHANGE** buttons on the MPK are off, so the pads send notes.
- Click **Learn pads**, click a drum on screen, then hit a pad on your MPK. Repeat for each pad, then click **Done**. Your mapping is saved in the browser.
- If your keys use a channel other than 1, set **Keys channel** in the top bar.

The MIDI monitor panel shows every message the controller sends, which helps when mapping other models or custom presets.
