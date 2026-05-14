# CosineDJ

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

A simple, browser-based drum machine built with [Tone.js](https://tonejs.github.io/). Create 8-step patterns for three synthesized drum sounds and apply real-time audio effects.

## Demo

Try the live demo: **[https://code4fukui.github.io/cosine-dj/](https://code4fukui.github.io/cosine-dj/)**


![Screenshot of the CosineDJ interface, showing the 3x8 pattern grid, play/stop buttons, and sliders for low-pass and distortion filters.](https://user-images.githubusercontent.com/1645839/229331985-71501728-660c-4809-9403-16298e82676b.png)


## Features

*   **Pattern Sequencer**: Program 8-step sequences across three tracks: Kick, Hihat, and Snare.
*   **Synthesized Sounds**: All drum sounds are generated in real-time using Tone.js synthesizers (`MembraneSynth`, `MetalSynth`, `NoiseSynth`).
*   **Real-Time Effects**: Manipulate the sound with an adjustable low-pass filter and a distortion effect.
*   **Automatic Modulation**: Enable automatic, periodic modulation of the filter and distortion parameters using a cosine wave—the feature that gives CosineDJ its name.

## Usage

1.  **Set the Pattern**: Click the checkboxes in the 3x8 grid to program your beat.
    *   **Top row**: Kick
    *   **Middle row**: Hihat
    *   **Bottom row**: Snare
2.  **Start Playback**: Click the `play` button. The pattern grid will be locked during playback.
3.  **Adjust Effects**: Use the sliders to change the low-pass filter cutoff frequency and the amount of distortion.
4.  **Enable Auto-Modulation**: Check the `filter auto` box to have the filter and distortion parameters change automatically over time.
5.  **Stop Playback**: Click the `stop` button. This will halt the audio and unlock the pattern grid for editing.

## License

MIT License - see [LICENSE](LICENSE).