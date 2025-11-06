# 📱 AI Document Reader Pro - Mobile App

A free, offline-capable document reader with AI analysis and text-to-speech. Works as a web app or installable mobile app!

## ✨ Features

- 📄 **Upload Documents**: PDF, TXT, DOCX support
- 🤖 **AI Analysis**: Automatic document summarization
- 🎙️ **Text-to-Speech**: Read documents aloud with voice controls
- 📖 **Navigation**: Jump between sections, bookmark positions
- 📊 **Progress Tracking**: Visual progress bar with time estimates
- 🔖 **Bookmarks**: Save and return to specific sections
- 🌙 **Dark Mode**: Easy on the eyes
- 📱 **Works Offline**: Once installed, works without internet (for local files)
- 🆓 **100% Free**: No API keys required for basic features

## 🚀 How to Use on Your Phone

### Option 1: As a Web App (Easiest!)

1. **Open the file in your phone's browser**:
   - Upload `index.html` to a web hosting service (GitHub Pages, Netlify, etc.)
   - OR use Python's simple HTTP server:
     ```bash
     python3 -m http.server 8000
     ```
   - Then visit `http://your-computer-ip:8000` on your phone

2. **Use it directly** - it works perfectly in mobile browsers!

### Option 2: Install as an App (Recommended!)

1. **Open the web app** in your mobile browser (Chrome/Safari)

2. **Install the app**:
   - **Android (Chrome)**:
     - Tap the "Install App" button when it appears, OR
     - Tap the menu (⋮) → "Add to Home screen"

   - **iPhone (Safari)**:
     - Tap the Share button (□↑)
     - Scroll down and tap "Add to Home Screen"
     - Tap "Add"

3. **Open from your home screen** - it now works like a native app!

## 📖 Navigation Features

### Reading Controls
- **⏮️ Start**: Jump to beginning
- **⏪ -30s**: Go back one section
- **🔖 Bookmark**: Save current position
- **⏩ +30s**: Skip forward one section
- **⏭️ End**: Jump to end

### Section Navigation
- Use the dropdown menu to jump to any section
- Progress bar shows your current position
- Time remaining estimates your reading time

### Bookmarks
- Click the bookmark button to save your current position
- View all bookmarks in the bookmarks section
- Click a bookmark to jump back to that section
- Delete bookmarks you no longer need

## 🎙️ Voice Features & TTS Providers

Choose from **5 different voice providers** - all with FREE tiers!

### 🔊 Browser Voices (Default - 100% Free)
- ✅ Works immediately, no setup
- ✅ Multiple voices available
- ✅ Adjustable speed, pitch, and volume
- ✅ Works completely offline
- ⚠️ Quality varies by device

### 🔵 Google Cloud Text-to-Speech
- ✅ **FREE: 1-4 million characters/month!**
- ✅ Premium: $4 per 1M characters
- ✅ WaveNet & Neural2 ultra-realistic voices
- ✅ 220+ voices in 40+ languages
- 📚 Sign up: [Google Cloud Console](https://cloud.google.com/text-to-speech)

### 🔷 Microsoft Azure Speech
- ✅ **FREE: 500,000 characters/month**
- ✅ Premium: $15 per 1M characters
- ✅ Neural voices with emotions
- ✅ 400+ voices in 140+ languages
- ✅ Custom voice training available (paid)
- 📚 Sign up: [Azure Portal](https://azure.microsoft.com/services/cognitive-services/text-to-speech/)

### 🎭 Play.ht
- ✅ **FREE: 12,500 characters trial**
- ✅ Personal: $19/month (100k words)
- ✅ Professional: $39/month (500k words)
- 🎤 **Voice Cloning: $59/month+**
- ✅ Ultra-realistic AI voices
- ✅ 800+ voices in 60+ languages
- 📚 Sign up: [Play.ht](https://play.ht/)

### 🎤 Resemble.ai (BEST for Voice Cloning!)
- ✅ **FREE: Basic plan available**
- ✅ Pro: ~$20/month
- 🎤 **Voice Cloning INCLUDED in FREE tier!**
- ✅ Clone your voice with just 25 sentences
- ✅ Real-time voice synthesis
- ✅ Emotion control
- 📚 Sign up: [Resemble.ai](https://www.resemble.ai/)

## 🎯 Perfect For

- 📚 Reading eBooks and PDFs
- 📝 Listening to documents hands-free
- 🎓 Studying and taking notes
- 💼 Reviewing work documents
- 🚗 Listening while driving
- 🏃 Listening while exercising

## 🆓 What's FREE

### Core Features (Always Free)
- ✅ All navigation features (skip, jump, bookmarks)
- ✅ Document upload and processing (PDF, TXT, DOCX)
- ✅ Text-to-speech with browser voices
- ✅ Modern voice controls (speed, pitch, volume)
- ✅ Bookmarks and progress tracking
- ✅ Dark mode & responsive design
- ✅ Offline functionality (PWA)
- ✅ No accounts or sign-ups required

### Voice Providers with Generous FREE Tiers
- 🔊 **Browser Voices**: Unlimited, forever free
- 🔵 **Google Cloud TTS**: 1-4M characters/month FREE
- 🔷 **Azure Speech**: 500k characters/month FREE
- 🎭 **Play.ht**: 12.5k characters trial FREE
- 🎤 **Resemble.ai**: Basic plan FREE with voice cloning!

## 🔒 Privacy

- All processing happens in your browser
- Documents never leave your device
- No tracking or analytics
- Bookmarks saved locally in your browser

## 🎤 Voice Cloning - Hear Yourself Reading!

Want the app to read documents in **YOUR own voice**? Here's how:

### Option 1: Resemble.ai (RECOMMENDED - FREE!)
1. **Sign up** for free at [Resemble.ai](https://www.resemble.ai/)
2. **Record your voice**: Read 25 sentences (takes ~10 minutes)
3. **Get your API key** from the dashboard
4. **Enter it in the app** under "Resemble.ai" tab
5. **Done!** The app now reads in YOUR voice

### Option 2: Play.ht (Premium)
1. **Sign up** at [Play.ht](https://play.ht/)
2. **Upgrade** to Creator plan ($59/month)
3. **Upload voice samples** (1-2 minutes of audio)
4. **Get API key** and voice ID
5. **Configure** in the app

### Option 3: Azure Custom Neural Voice (Enterprise)
1. **Sign up** for Azure Speech Service
2. **Apply** for Custom Neural Voice access
3. **Record training data** (professional recording needed)
4. **Train model** (can take hours)
5. **Use in app** with your custom voice ID

**Best for personal use**: Resemble.ai offers FREE voice cloning!

## 💡 Tips

1. **For long documents**: Use the section dropdown to navigate quickly
2. **Save your place**: Bookmark before closing the app
3. **Adjust reading speed**: Use the speed slider for comfortable listening
4. **Volume control**: Adjust volume without leaving the app
5. **Dark mode**: Toggle for night reading
6. **Install the app**: Works offline and loads faster
7. **Voice cloning**: Try Resemble.ai for free to hear yourself!

## 🛠️ Technical Details

- Built with vanilla JavaScript (no frameworks needed)
- Progressive Web App (PWA) with service worker
- Works offline after first visit
- Local storage for bookmarks and settings
- PDF.js for PDF reading
- Mammoth.js for DOCX support
- Web Speech API for text-to-speech

## 📱 System Requirements

- **Mobile**: iOS 11.3+, Android 5.0+ (Chrome)
- **Desktop**: Any modern browser
- **Internet**: Only needed for initial load and AI summaries

## 🐛 Troubleshooting

**App won't install?**
- Make sure you're using Chrome (Android) or Safari (iPhone)
- Check that you're accessing via HTTPS or localhost

**Voice not working?**
- Check that your device volume is up
- Make sure you granted microphone permissions
- Try a different voice from the dropdown

**Progress not saving?**
- Make sure cookies/local storage is enabled
- Don't use private/incognito mode

**AI summary not working?**
- This uses free Hugging Face models which may take time to load
- Fallback to basic text analysis if unavailable
- Internet connection required for AI features

## 📄 License

Free to use for personal purposes!

---

Made with ❤️ for mobile reading on the go!
