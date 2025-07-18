# 🤫 ShhNote Frontend

Modern, compact frontend for secure private note sharing with real-time collaboration.

## ✨ Features

- **🎨 Compact Design**: Small, efficient UI that works on all devices
- **🔒 Passcode Protection**: Optional password protection for notes
- **⚡ Real-time Sync**: Live collaboration with multiple users
- **📱 Mobile Optimized**: Touch-friendly compact interface
- **🌙 Dark/Light Theme**: Automatic theme switching
- **🔊 Text-to-Speech**: Built-in read-aloud functionality
- **📤 Export**: Download notes as text files
- **🔗 Easy Sharing**: QR codes and shareable links
- **⌨️ Keyboard Shortcuts**: Power user features
- **🌐 PWA Ready**: Install as a native app

## 🚀 Quick Start

1. **Install dependencies**
   ```bash
   cd frontend
   npm install
   ```

2. **Start development server**
   ```bash
   npm run dev
   ```

3. **Open in browser**
   ```
   http://localhost:3000
   ```

## 🔧 Configuration

The frontend connects to the backend API at `http://localhost:5500/api/v1`. 

To change the API endpoint, edit `app.js`:

```javascript
const CONFIG = {
    API_BASE_URL: 'http://localhost:5500/api/v1',
    SOCKET_URL: 'http://localhost:5500'
};
```

## 📱 Compact Design Features

- **Minimal Header**: 48px height with essential controls
- **Compact Buttons**: Small, touch-friendly interface elements
- **Efficient Spacing**: Optimized padding and margins
- **Mobile-First**: Designed for small screens first
- **Clean Typography**: Readable text at small sizes
- **Smart Modals**: Compact dialogs that don't overwhelm

## 🎯 User Experience

- **Intuitive**: Anyone can use it immediately
- **Fast**: Optimized for quick loading and interaction
- **Accessible**: Keyboard navigation and screen reader support
- **Responsive**: Works perfectly on all screen sizes
- **Offline**: PWA capabilities for offline access

## 🚀 Deployment

### Static Hosting (Recommended)

Deploy to any static hosting service:

- **Vercel**: Connect GitHub repo
- **Netlify**: Drag and drop build folder
- **GitHub Pages**: Enable in repository settings
- **Cloudflare Pages**: Connect repository

### Build for Production

```bash
npm run build
```

## 📊 SEO Optimization

- Complete meta tags for social sharing
- Structured data (JSON-LD)
- Sitemap and robots.txt
- Performance optimized
- Ready for `shh.letnote.in` domain

## 🔒 Security

- Content Security Policy headers
- XSS protection
- CSRF protection
- Input validation
- Secure headers

## 📱 PWA Features

- Installable on mobile devices
- Offline support with service worker
- Native app-like experience
- Push notifications ready

## ⌨️ Keyboard Shortcuts

- `Ctrl/Cmd + E`: Toggle edit mode
- `Ctrl/Cmd + S`: Auto-save (prevents browser save)
- `Escape`: Close modals

## 🎨 Theming

The app supports dark and light themes with CSS custom properties. Themes are automatically saved to localStorage.

## 📞 Support

- 🐛 Issues: Create GitHub issue
- 📧 Email: support@shh.letnote.in
- 📖 Docs: See main README.md

---

Built with ❤️ for secure, compact note sharing