# 📱 Phone-amin

**A Musical Motion Instrument & Learning Tool for Mobile Devices**

Phone-amin transforms your smartphone into an interactive musical instrument that responds to your movements. Tilt, twist, and gesture to create music, learn songs, record loops, and feel vibrations!

![Phone-amin Demo](https://img.shields.io/badge/demo-live-brightgreen) ![Version](https://img.shields.io/badge/version-4.0-blue) ![License](https://img.shields.io/badge/license-MIT-lightgrey)

## ✨ Features

### 🎵 **Play Mode** - The Tilt Instrument
- **Motion-Controlled Pitch**: Tilt your device side-to-side to change musical pitch
- **Volume Control**: Tilt forward/back to adjust volume
- **Multiple Waveforms**: Choose between sine, triangle, sawtooth, and square waves
- **Scale Modes**: Play in chromatic, major, minor, or pentatonic scales
- **Real-time Visualizations**: See waveforms and pitch position
- **Gesture Detection**: Automatic gesture recognition (Tilt Left/Right, Phone Up/Down)

### 🎓 **Learn Mode** - Musical Training Assistant
- **Song Library**: 4 preset songs with varying difficulty
- **Pitch Detection**: Uses your microphone to detect played notes
- **Real-time Feedback**: Visual indicators for pitch accuracy
- **Progress Tracking**: Score and progress bars
- **Practice Mode**: Learn melodies by ear and motion

### 🔁 **Looper Mode** - Multi-Track Recorder
- **Dual-Track Recording**: Layer multiple musical phrases
- **Visual Waveforms**: See recordings as waveforms
- **Sync Playback**: Play tracks together in perfect timing
- **Export Loops**: Save your compositions as JSON files
- **Master Controls**: Record/play multiple tracks simultaneously

### 📳 **Haptic Feedback** - Touch & Feel
- **6 Vibration Patterns**: Tap, bump, vibrate, success, warning, rhythm
- **Automatic Feedback**: Vibrations for correct notes and actions
- **Gesture Response**: Haptic feedback for device movements
- **Metronome Pulses**: Tactile timing during loop playback

## 🚀 Quick Start

1. **Open** [Phone-amin](your-link-here) on your mobile device
2. **Tap** "Enable Sensors & Audio" (required for motion and sound)
3. **Choose** a mode from the tabs:
   - 🎵 **Play**: Tilt to create music freely
   - 🎓 **Learn**: Practice preset songs
   - 🔁 **Looper**: Record and layer musical phrases
4. **Tilt your device** to control pitch and volume
5. **Explore** settings to customize your experience

## 📱 Device Compatibility

### ✅ Supported
- **iOS 12+** (Safari)
- **Android 8+** (Chrome, Firefox)
- **Modern desktop browsers** (with orientation simulation)

### 🔧 Requirements
- **Accelerometer/Gyroscope** (for motion control)
- **Microphone** (for pitch detection in Learn mode)
- **Audio output** (speakers or headphones)
- **HTTPS connection** (for sensor access)
- **Vibration hardware** (for haptic feedback)

## 🎛️ Controls & Settings

### Basic Controls
- **Enable Sensors & Audio**: Initializes motion and sound
- **Start Playing**: Begins audio output
- **Mute/Unmute**: Toggles audio output
- **Test Tone**: Plays A440 reference tone

### Settings
- **Waveform**: Sine, triangle, sawtooth, square
- **Octave Range**: 2-4 octaves of pitch range
- **Scale Mode**: Chromatic, major, minor, pentatonic
- **Key**: Musical key (C, D, E, F, G, A)

### Learning Songs
1. **Select a song** from the presets
2. **Play Demo** to hear the melody
3. **Start Practice** and tilt to match notes
4. **Watch feedback** as you improve accuracy

### Looper Controls
- **Track Recording**: Individual track record/play/clear
- **Master Record**: Record both tracks simultaneously
- **Master Playback**: Play all tracks in sync
- **Clear All**: Reset all tracks
- **Export Loop**: Save composition to file

## 🎮 How It Works

### Motion Sensing
Phone-amin uses the Device Orientation API to detect:
- **Gamma**: Side-to-side tilt (controls pitch)
- **Beta**: Front-to-back tilt (controls volume)
- **Alpha**: Compass orientation (for gestures)

### Audio Engine
- **Web Audio API** for synthesis and processing
- **Custom oscillators** with multiple waveforms
- **Real-time pitch adjustment** based on tilt
- **LFO modulation** for vibrato effects

### Pitch Detection
- **Autocorrelation algorithm** for frequency analysis
- **Real-time microphone input** processing
- **Note quantization** to nearest semitone
- **Visual feedback** for accuracy

## 🛠️ Technical Details

### Architecture
- **Pure HTML/CSS/JavaScript** - No dependencies
- **Modular class structure** for easy maintenance
- **Responsive design** for all screen sizes
- **Progressive enhancement** for feature support

### APIs Used
- **Web Audio API** - Audio synthesis and processing
- **Device Orientation API** - Motion sensing
- **Vibration API** - Haptic feedback
- **Media Devices API** - Microphone access
- **Canvas API** - Visualizations

### Performance Optimizations
- **Throttled sensor updates** (60fps)
- **Efficient audio node management**
- **Memory-optimized looper storage**
- **Smooth animations** with requestAnimationFrame

## 📚 Learning Resources

### For Beginners
1. Start in **Play Mode** to get comfortable with tilt control
2. Try **different waveforms** to hear how they sound
3. Experiment with **scale modes** to stay in key
4. Practice **smooth motions** for musical phrasing

### For Musicians
1. Use **Looper Mode** to build complex compositions
2. Layer **different scales** and **keys** across tracks
3. Export loops for **further editing** in DAWs
4. Use as a **practice tool** for ear training

### For Educators
1. Great for teaching **pitch relationships**
2. Demonstrates **physical computing** concepts
3. Shows **math-music connections** (frequencies, ratios)
4. Engaging way to teach **music theory**

## 🔧 Troubleshooting

### Common Issues

| Problem | Solution |
|---------|----------|
| No sound | Tap "Enable Sensors & Audio", check device volume |
| Motion not working | Ensure device has gyroscope, reload page |
| Microphone access denied | Allow microphone permissions in browser settings |
| No vibration | Check device supports vibration, enable in settings |
| Audio crackling | Reduce other apps using audio, close background apps |

### Browser-Specific Notes
- **iOS Safari**: Requires user gesture to start audio
- **Chrome**: Best overall support
- **Firefox**: May need explicit permissions
- **Desktop**: Use device orientation simulation in DevTools

## 🚀 Future Roadmap

### Planned Features
- [ ] **More presets** - Additional songs and exercises
- [ ] **Custom scales** - User-defined scale patterns
- [ ] **Effects chain** - Reverb, delay, distortion
- [ ] **MIDI export** - Standard MIDI file output
- [ ] **Social features** - Share loops and scores
- [ ] **AR mode** - Visual music creation in AR

### Development Goals
- **Cross-platform compatibility**
- **Improved accessibility**
- **Educational content**
- **Community contributions**

## 🤝 Contributing

Want to improve Phone-amin? Here's how:

1. **Fork** the repository
2. **Create** a feature branch
3. **Make** your changes
4. **Test** on multiple devices
5. **Submit** a pull request

### Areas Needing Help
- **Additional songs** and exercises
- **UI/UX improvements**
- **Audio quality enhancements**
- **Documentation and tutorials**
- **Translation/localization**

## 📄 License

Phone-amin is released under the **MIT License**. See [LICENSE](LICENSE) for details.

### Third-Party Credits
- **Web Audio API** - W3C Standard
- **Device Orientation API** - W3C Standard
- **Vibration API** - W3C Standard
- Icons from **Emoji** set

## 🙏 Acknowledgments

- Inspired by **Theremin** and other motion-controlled instruments
- Built with **modern web technologies**
- Tested by **musicians and educators**
- Community feedback from **users worldwide**

---

**Made with ❤️ and JavaScript by [Your Name]**

*Turn your phone into an instrument. Learn music through motion. Create without limits.*
