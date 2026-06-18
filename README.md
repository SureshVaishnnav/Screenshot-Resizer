# 📱 Screenshot Resizer

A fast, free, browser-based tool to resize and optimize screenshots for **iOS App Store** and **Google Play Store**. No internet required after loading, 100% client-side processing, zero ads.

![Screenshot Resizer UI](https://raw.githubusercontent.com/SureshVaishnnav/Screenshot-Resizer/main/docs/screenshot.png)

## ✨ Features

- 📱 **Multiple Device Sizes** - iPhone, iPad, Android tablets
- 🎯 **Three Resize Modes**
  - **Fit**: Maintain aspect ratio with padding
  - **Fill**: Crop to fill (no padding)
  - **Stretch**: Exact dimensions
- 🚀 **Batch Processing** - Resize multiple images at once
- 💾 **High-Resolution Output** - PNG format, full quality
- 🎨 **Beautiful UI** - Modern, responsive design
- ✅ **No Server Uploads** - 100% client-side processing
- 🚫 **No Ads** - Completely ad-free
- 🌐 **Works Offline** - After initial load, no internet needed
- ⚡ **Fast** - Instant resizing (no server delays)

## 🚀 Quick Start

1. **Open the app**: [Screenshot Resizer](https://sureshvaishnnav.github.io/Screenshot-Resizer/)
2. **Drag & drop** your screenshots (or click to browse)
3. **Select target sizes** (Apple App Store, Google Play, or custom)
4. **Choose resize mode** (Fit, Fill, or Stretch)
5. **Click "Resize & Preview"**
6. **Right-click** any image → **Save Image As** to download

## 📦 Supported Sizes

### 🍎 Apple App Store
| Device | Dimensions |
|--------|-----------|
| iPhone 6.7" | 1290 × 2796 px |
| iPhone 6.5" | 1284 × 2778 px |
| iPhone 6.1" | 1179 × 2556 px |
| iPhone 5.5" | 1242 × 2208 px |
| iPad Pro 12.9" | 2048 × 2732 px |
| iPad Pro 11" | 1668 × 2388 px |

### 🔵 Google Play Store
| Device | Dimensions |
|--------|-----------|
| Phone | 1080 × 1920 px |
| 7" Tablet | 1200 × 1920 px |
| 10" Tablet | 1600 × 2560 px |

### 🎨 Custom Sizes
Add any custom dimensions you need!

## 🛠️ Local Setup

### Option 1: Direct File Opening (No Server Needed)
1. Clone the repo: 
   ```bash
   git clone https://github.com/SureshVaishnnav/Screenshot-Resizer.git
   cd Screenshot-Resizer
   ```
2. Open `index.html` in your browser (double-click or right-click → Open with)
3. That's it! Works completely offline

### Option 2: With Local Server
If you want to test with a local server:

**Python 3:**
```bash
python -m http.server 8000
# Visit: http://localhost:8000
```

**Python 2:**
```bash
python -m SimpleHTTPServer 8000
```

**Node.js (http-server):**
```bash
npx http-server
```

**PHP:**
```bash
php -S localhost:8000
```

## 🌐 Online Deployment

### GitHub Pages (Free & Easy)
1. Fork this repo
2. Go to Settings → Pages
3. Select `main` branch as source
4. Your app will be at: `https://YOUR-USERNAME.github.io/Screenshot-Resizer/`

### Netlify (Recommended)
1. Go to [netlify.com](https://netlify.com)
2. Connect GitHub repo
3. Auto-deploys on push
4. Get a live URL instantly

### Vercel
1. Go to [vercel.com](https://vercel.com)
2. Import GitHub repo
3. One-click deploy

## 🤝 Contributing

We'd love your contributions! Here's how:

### Ways to Contribute
- 🐛 Report bugs
- ✨ Suggest features (e.g., more device sizes, new resize modes)
- 📝 Improve documentation
- 🎨 Design improvements
- 🌐 Add more device sizes
- 🌍 Translate to other languages

### Getting Started

1. **Fork** the repo
2. **Create** a feature branch: `git checkout -b feature/your-feature`
3. **Make** your changes
4. **Test** in your browser
5. **Commit**: `git commit -m "Add feature: description"`
6. **Push**: `git push origin feature/your-feature`
7. **Open** a Pull Request

### Code Style
- Keep HTML clean and semantic
- Use CSS variables for theming
- Add comments for complex logic
- Test across different screen sizes and devices
- Ensure no console errors

## 💡 Ideas for Contributors

- [ ] Add more device sizes (Android, tablets)
- [ ] Add image optimization (compression)
- [ ] Add watermark support
- [ ] Batch download as ZIP
- [ ] Undo/Redo functionality
- [ ] Image preview grid
- [ ] Dark mode
- [ ] Localization (Hindi, Spanish, etc.)
- [ ] Export presets

## ☕ Support This Project

If this tool helps you, consider supporting its development:

**UPI (India):** `suresh.vaishnnav@ybl`

Or support via:
- [![Razorpay](https://img.shields.io/badge/Razorpay-1435c0?style=flat-square&logo=razorpay)](https://razorpay.me/sureshvaishnnav)
- [![GitHub Sponsors](https://img.shields.io/badge/GitHub%20Sponsors-EA4AAA?style=flat-square&logo=github)](https://github.com/sponsors/SureshVaishnnav)

## 📄 License

MIT License - Feel free to use, modify, and distribute

See [LICENSE](./LICENSE) for details

## 🙋 FAQ

**Q: Is my data secure?**
A: Yes! Everything happens locally in your browser. No data is sent to any server.

**Q: Do I need to create an account?**
A: No account needed. No login required.

**Q: Can I use it offline?**
A: Yes! After the page loads once, you can use it completely offline.

**Q: What image formats are supported?**
A: PNG, JPG, WebP, and most common image formats.

**Q: Can I resize videos?**
A: Currently only images are supported. Video support is on the roadmap.

**Q: Is there a file size limit?**
A: Limited by your browser's memory (typically 100MB+). Most screenshots are under 5MB.

## 🐛 Bug Reports

Found a bug? Please create an issue with:
- Browser and OS
- Steps to reproduce
- Expected vs actual behavior
- Screenshots if helpful

## 📱 Follow & Stay Updated

- ⭐ Star this repo for updates
- 👀 Watch for new features
- 🔔 Enable notifications

## 🙏 Credits

Made with ❤️ by [Suresh Vaishnnav](https://github.com/SureshVaishnnav)

---

**Have questions or suggestions?** [Open an issue](https://github.com/SureshVaishnnav/Screenshot-Resizer/issues) or [start a discussion](https://github.com/SureshVaishnnav/Screenshot-Resizer/discussions)!
