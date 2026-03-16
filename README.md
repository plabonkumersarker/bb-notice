# BB Notice Finder

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-brightgreen)](https://plabonkumersarker.github.io/bb-notice)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Visitor Count](https://img.shields.io/badge/dynamic/json?color=success&label=visitors&query=value&url=https%3A%2F%2Fcountapi.mileshilliard.com%2Fapi%2Fv1%2Fget%2Fbb-notice-finder-visitors-v1)](https://plabonkumersarker.github.io/bb-notice)

> **High-quality PDF retrieval system for Bangladesh Bank and Combined Banks (BSCS) recruitment archives**

A sophisticated, mobile-first web application that generates official PDF links for Bangladesh Bank recruitment notices. Simply enter the publication date, notice type (BB/BSCS), and notice number to instantly access archived recruitment circulars.

![Screenshot](screenshot.png)

## ✨ Features

- **Instant PDF Link Generation** — Create official Bangladesh Bank notice URLs in seconds
- **Mobile-Optimized Design** — Fully responsive interface optimized for Android and iOS devices
- **Dual Notice Support** — Handles both BB (Bangladesh Bank) and BSCS (Combined Banks) notices
- **Smart Validation** — Real-time form validation with helpful error messages
- **One-Click Actions** — Open PDFs directly or copy URLs to clipboard
- **Visitor Analytics** — Live visitor counter to track tool usage
- **Elegant UI/UX** — Sophisticated institutional design with forest green and gold accents
- **Zero Backend Required** — Pure client-side application, no server needed

## 🚀 Live Demo

**🌐 [https://plabonkumersarker.github.io/bb-notice](https://plabonkumersarker.github.io/bb-notice)**

## 📱 Mobile Preview

| Android | iOS |
|---------|-----|
| ![Android](android-preview.png) | ![iOS](ios-preview.png) |

## 🛠️ URL Construction Schema

The tool follows Bangladesh Bank's official URL pattern:

| Type | Format | Example |
|------|--------|---------|
| **BSCS** | `https://erecruitment.bb.org.bd/career/YYYYMMDD_bscs_NoticeNo.pdf` | `20250722_bscs_78.pdf` |
| **BB** | `https://erecruitment.bb.org.bd/career/YYYYMMDD_bb_NoticeNo.pdf` | `20260315_bb_23.pdf` |

## 📋 How to Use

1. **Select Publication Date** — Choose the exact date when the notice was published
2. **Select Institution Type** — Choose between BB (Bangladesh Bank) or BSCS (Combined Banks)
3. **Enter Notice Number** — Input the sequential notice identifier (e.g., 78, 23, 105)
4. **Generate Link** — Click to create the official PDF URL
5. **Access PDF** — Either open directly in browser or copy the URL

## 💻 Local Development

### Prerequisites
- Any modern web browser
- Git (for cloning)

### Setup

```bash
# Clone the repository
git clone https://github.com/plabonkumersarker/bb-notice.git

# Navigate to project directory
cd bb-notice

# Open index.html in your browser
# On macOS:
open index.html

# On Linux:
xdg-open index.html

# On Windows:
start index.html
```

### Project Structure

```
bb-notice/
├── index.html          # Main application file
├── README.md           # Project documentation
├── LICENSE             # MIT License
└── .github/
    └── workflows/
        └── static.yml  # GitHub Pages deployment workflow
```

## 🚀 Deployment

This project is configured for **GitHub Pages** deployment:

1. Push code to `main` branch
2. GitHub Actions automatically deploys to Pages
3. Site available at `https://plabonkumersarker.github.io/bb-notice`

### Manual Deployment

To deploy to your own GitHub Pages:

1. Fork this repository
2. Go to **Settings** → **Pages**
3. Select **Source**: Deploy from a branch
4. Choose **Branch**: `main` / `root`
5. Your site will be available at `https://yourusername.github.io/bb-notice`

## 🎨 Design Philosophy

- **Color Palette**: Deep forest green (`#0a1f13`) and antique gold (`#c9a227`) — reflecting both banking prestige and Bangladesh's natural heritage
- **Typography**: Crimson Text (serif) for headings, Space Grotesk (geometric sans) for UI elements
- **Texture**: Subtle paper grain and watermark effects suggesting official documents
- **Mobile-First**: Optimized for 320px+ screens with responsive breakpoints at 480px

## 🔧 Technical Details

- **Pure HTML/CSS/JS** — No frameworks, no build step required
- **CountAPI Integration** — Anonymous visitor counting with session deduplication
- **CSS Grid & Flexbox** — Modern layout techniques
- **CSS Custom Properties** — Easy theming and maintenance
- **Accessibility**: WCAG 2.1 AA compliant color contrast and touch targets

## 📝 Changelog

### v1.0.0 (2024)
- ✨ Initial release
- 📱 Mobile-responsive design
- 🔗 PDF link generation for BB/BSCS notices
- 📊 Visitor counter implementation
- 🎨 Institutional UI design

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Bangladesh Bank** — For maintaining the official erecruitment portal
- **CountAPI** — For providing free visitor analytics
- **Google Fonts** — Crimson Text and Space Grotesk typefaces

## 📞 Contact

**Plabon Kumer Sarker**
- Website: [plabonkumersarker.github.io/profile](https://plabonkumersarker.github.io/profile)
- GitHub: [@plabonkumersarker](https://github.com/plabonkumersarker)

---

<p align="center">
  <sub>Built with ❤️ for Bangladesh Bank job seekers</sub>
</p>
