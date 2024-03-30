# Vune

A multiband music visualiser written in JavaScript, using Canvas and the Web Audio API.

## Feature Plan

- [ ] Set canvas size (square or full screen).
- [ ] Set primary background colour.
- [ ] Load an audio file.
- [ ] Show loading progress.
- [ ] Play, pause, stop, back (10s), forward (10s).
- [ ] Show audio file duration.
- [ ] Show current time.
- [ ] Show current track position.
- [ ] Alter position by scrubbing along track.
- [ ] Show/hide track controls on hover (desktop).
- [ ] Show/hide track controls with icon (mobile).
- [ ] Show/hide visualiser controls on hover (desktop).
- [ ] Show/hide visualiser controls with icon (mobile).
- [ ] The canvas is divided up by signal bands, four by default.
- [ ] These signal bands are spread out over the audio spectrum, logarithmically rather than linearly.
- [ ] The frequency response of each band can be controlled.
- [ ] The visuals of each band can overlap or occupy a restricted area of the canvas.
- [ ] The visuals default to a left-to-right arrangement but can be rotated.
- [ ] Each signal band can be visually transformed as follows:
  - [ ] Colour can be set.
  - [ ] Transparency can be set.
  - [ ] Signal can be visually sliced/chopped by halves/quarters/eighths etc.
  - [ ] Signal can be stretched/thinned.
  - [ ] Signal can be diffused into particles.
- [ ] The current visualisation state can be saved:
  - [ ] Into local browser storage.
  - [ ] As a downloadable json file.

