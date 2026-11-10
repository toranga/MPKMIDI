# MPKMIDI

A browser-based synth and drum player for the **AKAI MPK mini**, built on the Web MIDI API. No install, no drivers, no DAW.

## Use it

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

The MIDI monitor panel shows every message the controller sends, which helps when mapping other models or custom presets.
