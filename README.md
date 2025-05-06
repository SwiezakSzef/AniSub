# AniSub - AI-Powered Video Subtitle Translator

## 🚨NOTE: THIS THE PROGRAM IS IN POLISH🚨

![Python Version](https://img.shields.io/badge/python-3.7%2B-blue)
![License](https://img.shields.io/badge/license-MIT-green)

An AI-powered video translation tool with GUI, designed for anime fans but suitable for any video content. Translates audio to subtitles and burns them directly into video files.

**Key Features**:
- 🎥 Video-to-subtitle translation using OpenAI's Whisper
- 🌍 Multi-language support via DeepL API
- 🖌️ Burn subtitles directly into video or export SRT files
- 🎮 User-friendly GUI with progress tracking

## 📦 Installation

### Prerequisites
- Python 3.7+
- [FFmpeg](https://ffmpeg.org/)
- DeepL API Key (Free tier available)

### Setup
```bash
# Clone repository
git clone https://github.com/yourusername/AniSub.git
cd AniSub

# Install dependencies
pip install -r requirements.txt

# Create environment file
echo "DEEPL_API_KEY=your_api_key_here" > .env
```

## 🚀 Usage
Launch the application:

```bash

python main.py
```
GUI Interface Guide:

  Select Input File: Browse and choose your video file

  Language Selection: Choose source (e.g., Japanese) and target (e.g., Polish) languages

  Output Format: Choose between embedded subtitles or SRT file

  Start Processing: Click "Start" to begin translation

Interface Preview
## ⚙️ Configuration

Edit .env file to modify settings:
env
```
DEEPL_API_KEY=your_deepl_api_key
```
```
WHISPER_MODEL=medium  # Change model size (tiny, base, small, medium, large)
```

## 🌟 Features

  - Cross-platform support (Windows/macOS/Linux)

  - Real-time progress tracking

  - Error logging system

  - Multi-threaded processing

  - Support for multiple video formats (MP4, AVI, MKV)

  - Adjustable subtitle styling

## 🛠️ Technical Stack

  - Speech-to-Text: OpenAI Whisper

  - Translation: DeepL API

  - Video Processing: MoviePy

  - GUI: Tkinter

## 🚧 Roadmap

  - Add batch processing

  - Support for multiple translation APIs

  - Subtitle style customization

  - Automatic language detection

  - Video preview window

## 🤝 Contributing

Contributions welcome! Please follow these steps:

  - Fork the repository

  - Create your feature branch (git checkout -b feature/awesome-feature)

  - Commit your changes (git commit -m 'Add awesome feature')

  - Push to the branch (git push origin feature/awesome-feature)

  - Open a Pull Request

### 📄 License

This project is licensed under the MIT License - see LICENSE file for details
