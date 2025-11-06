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

## 🎙️ Voice Features

### Standard Browser Voices (Free)
- Works on all devices immediately
- Multiple voice options
- Adjustable speed and pitch
- Pause/resume controls

### Premium AI Voices (Optional)
- Get ultra-realistic voices with [ElevenLabs](https://elevenlabs.io/)
- Free tier: 10,000 characters/month
- Enter your API key in the app
- Fallback to browser voices if unavailable

## 🎯 Perfect For

- 📚 Reading eBooks and PDFs
- 📝 Listening to documents hands-free
- 🎓 Studying and taking notes
- 💼 Reviewing work documents
- 🚗 Listening while driving
- 🏃 Listening while exercising

## 🆓 Everything is FREE!

- ✅ All navigation features
- ✅ Document upload and processing
- ✅ Text-to-speech (browser voices)
- ✅ Bookmarks and progress tracking
- ✅ Dark mode
- ✅ Offline functionality
- ✅ No accounts or sign-ups required

**Optional Premium**: ElevenLabs for better voice quality (10k chars/month free)

## 🔒 Privacy

- All processing happens in your browser
- Documents never leave your device
- No tracking or analytics
- Bookmarks saved locally in your browser

## 💡 Tips

1. **For long documents**: Use the section dropdown to navigate quickly
2. **Save your place**: Bookmark before closing the app
3. **Adjust reading speed**: Use the speed slider for comfortable listening
4. **Dark mode**: Toggle for night reading
5. **Install the app**: Works offline and loads faster

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
