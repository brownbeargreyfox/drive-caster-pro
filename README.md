# 🎬 Drive Caster Pro

**Finally! Cast videos from Google Drive to Chromecast**

[![PWA Ready](https://img.shields.io/badge/PWA-Ready-brightgreen)](https://web.dev/progressive-web-apps/)
[![Open Source](https://img.shields.io/badge/Open%20Source-MIT-blue)](LICENSE)
[![No Backend](https://img.shields.io/badge/Backend-None-lightgrey)](#architecture)

A Progressive Web App that solves the frustrating problem Google never fixed: casting videos from Google Drive mobile app to Chromecast.

## 🚀 **[Try It Live](https://yourusername.github.io/drive-caster-pro)**

## ✨ Features

- 🎤 **Voice Control** - "Play next", "Pause", "Volume up"
- 🔐 **Secure OAuth** - Your private files stay private
- 📁 **Smart Navigation** - Browse folders with breadcrumb navigation
- 🎵 **Queue Management** - Build playlists, auto-advance videos
- ⭐ **Folder Bookmarks** - Save favorites for instant access
- 📱 **PWA Ready** - Install like a native app, works offline
- 🎮 **Full Media Controls** - Play, pause, seek, volume control
- 🔍 **Search & Filter** - Find videos quickly across all folders

## 🎯 Why This Exists

Google Drive has **2+ billion users** but still no way to cast videos from the mobile app in 2025. This PWA fills that gap with:

- **No Backend Required** - Everything runs in your browser
- **No Data Collection** - Your files never leave your device  
- **No Subscriptions** - Free and open source forever
- **Better UX** - Faster and more intuitive than desktop workarounds

## 🛠️ Quick Setup

### 1. **Use the Live Demo**
Visit [the live app](https://yourusername.github.io/drive-caster-pro) and follow the setup wizard.

### 2. **Google OAuth Setup** (One-time, 5 minutes)
1. Go to [Google Cloud Console](https://console.developers.google.com)
2. Create new project → Enable **Google Drive API**
3. Create **OAuth 2.0 Client ID** (Web application)
4. Add authorized origins: `https://yourusername.github.io`
5. Copy Client ID into the app

### 3. **Start Casting!**
- Sign in with Google
- Browse your Drive videos
- Connect to Chromecast
- Tap "Cast" on any video

## 🏗️ Development

```bash
# Clone and run locally
git clone https://github.com/yourusername/drive-caster-pro.git
cd drive-caster-pro

# Start local server (required for OAuth)
python -m http.server 8000
# Visit: http://localhost:8000

# For OAuth testing, add to Google Console:
# http://localhost:8000
```

## 🏛️ Architecture

**Pure Client-Side PWA**
- **Frontend**: Vanilla JavaScript, modern CSS
- **APIs**: Google Drive API, Google Cast SDK
- **Storage**: Browser localStorage only
- **Hosting**: Static files (GitHub Pages, Netlify, etc.)

**No Backend Needed!** Everything runs in your browser for maximum privacy and simplicity.

## 🤝 Contributing

We welcome contributions! This project thrives on community input.

- 🐛 **[Report Bugs](https://github.com/yourusername/drive-caster-pro/issues)**
- 💡 **[Request Features](https://github.com/yourusername/drive-caster-pro/discussions)**
- 🔧 **[Submit Pull Requests](https://github.com/yourusername/drive-caster-pro/pulls)**

See our [Contributing Guide](CONTRIBUTING.md) for details.

## 📊 Browser Support

- ✅ **Chrome/Chromium** (recommended)
- ✅ **Firefox** 
- ✅ **Safari** (iOS 14.3+)
- ✅ **Edge**

**Note**: Chromecast requires Chrome or Chromium-based browsers.

## 🔒 Privacy & Security

- **Zero Data Collection** - We never see your files
- **Local Processing** - Everything runs in your browser
- **Secure OAuth** - Industry-standard Google authentication
- **No Tracking** - No analytics, cookies, or fingerprinting

## 📄 License

MIT License - see [LICENSE](LICENSE) file.

You're free to use, modify, and distribute this software. If you build something cool with it, we'd love to hear about it!

## 🙏 Acknowledgments

Built with weekend determination and community feedback. Special thanks to:

- **Google Cast SDK** - For making Chromecast integration possible
- **Google Drive API** - For secure file access
- **The Open Source Community** - For inspiration and support

---

## ⭐ **Star this repo if it saved you from getting up to use your computer!**

**Built by developers, for developers. Share the love!** 🚀