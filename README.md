# Online System Audio Recorder

A free, browser-based tool to record PC system audio directly in your browser. No downloads, no installs — just hit record and save what you hear as an MP3 file.

##Features

- **System Audio Recording** - Captures what you hear through speakers/headphones
- **No Installation Required** - Works directly in your browser
- **MP3 Export** - Download recordings as high-quality MP3 files
- **Real-time Timer** - See recording duration as you record
- **Audio Playback** - Review recordings before downloading
- **Custom Filenames** - Choose your own filename or use auto-generated
- **Collapsible Instructions** - Clean interface with help when needed

## Quick Start

1. **Open the file**: Double-click `audio_recorder.html` or open it in your browser
2. **Allow permissions**: Grant audio capture permissions when prompted
3. **Start recording**: Click "🔴 Start Recording"
4. **Share audio**: In the browser dialog, select "Share audio" and choose your screen/window
5. **Stop recording**: Click "⏹️ Stop Recording" when done
6. **Download**: Click "💾 Download as MP3" to save your file

## How It Works

### Method 1: Screen Sharing (Recommended)
- Uses `getDisplayMedia()` API to capture system audio
- Works best in Chrome and Edge browsers
- Requires screen sharing permission (audio is captured, not video)

### Method 2: Stereo Mix (Windows Fallback)
- Enables "Stereo Mix" in Windows audio settings
- Captures system audio through virtual audio device
- Works when screen sharing method fails

## Requirements

- **Browser**: Chrome, Edge, Firefox, or Safari (Chrome/Edge recommended)
- **OS**: Windows, Mac, or Linux
- **Audio**: System audio output (speakers/headphones)

## Setup for Stereo Mix (Windows)

If the screen sharing method doesn't work:

1. Right-click the sound icon in your system tray
2. Select "Open Sound settings"
3. Click "More sound settings"
4. Go to "Recording" tab
5. Right-click in empty area and select "Show Disabled Devices"
6. Enable "Stereo Mix" and set as default
7. Refresh the page and try recording again

## File Structure

```
audio_recorder/
├── audio_recorder.html    # Main application file
├── README.md             # This file
├── LICENSE               # MIT License
└── .gitignore           # Git ignore file
```

## Browser Compatibility

| Browser | Status | Notes |
|---------|--------|-------|
| Chrome | ✅ Full Support | Best experience |
| Edge | ✅ Full Support | Works great |
| Firefox | ⚠️ Limited | May need Stereo Mix |
| Safari | ⚠️ Limited | Mac users |

## Use Cases

- **Music Recording** - Capture songs from streaming services
- **Podcast Recording** - Record audio from webinars or calls
- **Game Audio** - Save gaming soundtracks or clips
- **Video Audio** - Extract audio from online videos
- **System Sounds** - Record notifications or alerts

## Privacy & Security

- **No server uploads** - Everything happens locally in your browser
- **No data collection** - We don't track or store your recordings
- **Open source** - Review the code yourself
- **Offline capable** - Works without internet after first load

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

### Development Setup

1. Fork the repository
2. Clone your fork: `git clone https://github.com/yourusername/audio-recorder.git`
3. Make your changes
4. Test thoroughly in different browsers
5. Submit a pull request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Built with vanilla JavaScript and HTML5 APIs
- Uses [LAME.js](https://github.com/zhuker/lamejs) for MP3 encoding
- Inspired by the need for simple, portable audio recording tools

## Support

If you find this tool helpful, consider:
-  Starring this repository
-  Reporting bugs or issues
-  Suggesting new features
-  [Buy me a coffee](https://coff.ee/pfuentes)

---

**Made with ❤️ for the open source community** 
