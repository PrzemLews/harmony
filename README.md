# Harmony Game

A browser game for learning music theory by playing chords. Quaver, a little eighth note, runs along a treble staff. Play the right chord on your MIDI keyboard to open each gate in Quaver's path.

## How to play

- **Gates** carry a chord symbol (C, Am, F…). Play that chord before Quaver reaches the gate. Any octave and any inversion counts. Miss it and Quaver loses a life.
- **Notes on the staff** sit at their real treble-clef positions. Play the matching note and Quaver jumps to catch it.
- **Wrong chord?** The game tells you what you played and what the gate wanted.
- **Levels:** Key of C, All major, Major + minor. The game speeds up as you clear gates.
- **Hints** show chord tones (e.g. F · A · C) and note names. Turn them off to practise reading.

## Controls

- **MIDI keyboard:** plug it in, then press the MIDI button or Play.
- **Computer keys:** `A` to `;` are white keys, `W E T Y U O P` are black keys, `Z` / `X` shift the octave.
- **On-screen piano:** click or tap keys. Multi-touch works for chords.

## Running it

Open `index.html` in **Chrome or Edge**. No build step or server needed.

### MIDI troubleshooting

- Safari and Firefox (without an add-on) don't support Web MIDI.
- Chrome asks for MIDI permission the first time. If you missed the prompt, allow MIDI devices in the site settings and reload.
- On Windows, close any DAW (e.g. Ableton) that is using the controller, or disable its input there.
- The MIDI pill in the header turns green and shows your device name once it's connected.

## Status

Prototype 1. Next open question: how the keyboard should steer the character (pitch → height, low/high → left/right, or bass note picks a lane).
