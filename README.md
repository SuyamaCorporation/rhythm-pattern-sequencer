# 8-Step Drum Rhythm Sequencer

Toggle beats on four drum tracks, set BPM, and play patterns using Web Audio API synthesis.

## Features
- Four synthesized drum tracks: Kick (oscillator sweep), Snare (bandpass noise), Hi-Hat (highpass noise), Clap (layered noise bursts)
- 8-step or 16-step grid toggle; animated playhead highlights the current step
- BPM slider from 60–200 with real-time adjustment during playback
- Four built-in presets: Basic Rock, Bossa Nova, 4-on-Floor, Hip-Hop
- Save and load named patterns to localStorage with delete support

## Usage
Toggle step buttons on any track to activate beats. Adjust BPM with the slider. Click Play to start the sequencer — the playhead animates across the grid. Switch to 16-step mode for finer rhythms. Load a preset to start with a ready-made pattern. Save your pattern with a custom name to recall it later.
