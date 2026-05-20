# DexCanvas - Dexterous Manipulation Research

🤖 A modern, responsive website showcasing research in dexterous manipulation and robotics.

## 📋 Overview

DexCanvas is a research initiative focused on advancing the state-of-the-art in dexterous manipulation. This repository contains the GitHub Pages website that showcases our research, publications, and object datasets.

## 🚀 Quick Start

### Local Development

1. Clone this repository:
```bash
git clone https://github.com/yourusername/dexCanvas.git
cd dexCanvas
```

2. Open `index.html` in your browser:
```bash
# On Linux (Manjaro)
xdg-open index.html

# Or use a simple HTTP server
python -m http.server 8000
# Then visit http://localhost:8000
```

### Deploy to GitHub Pages

1. Push this repository to GitHub
2. Go to your repository settings
3. Navigate to **Pages** section
4. Under **Source**, select the `main` branch
5. Click **Save**
6. Your site will be available at `https://yourusername.github.io/dexCanvas/`

## 📁 Project Structure

```
dexCanvas/
├── index.html          # Main homepage
├── styles.css          # Stylesheet with modern design
├── script.js           # Interactive features and animations
├── README.md           # This file
├── LICENSE             # License file
└── thesis/             # Research materials and assets
    ├── iclr2026/       # ICLR 2026 submission materials
    │   ├── media/      # Media assets
    │   └── objects/    # 3D object images
    ├── dexterous_manipulation_sota_2025.md
    └── literature_review_dexcanvas.md
```

## ✨ Features

- 🎨 **Modern Design**: Clean, professional interface with smooth animations
- 📱 **Responsive**: Works seamlessly on desktop, tablet, and mobile devices
- 🖼️ **Object Gallery**: Interactive display of manipulation objects from research
- 📚 **Research Section**: Organized display of papers and essays
- 🌙 **Smooth Navigation**: Smooth scrolling and intuitive menu
- ⚡ **Fast Loading**: Optimized assets and lazy loading for images

## 🎨 Customization

### Changing Colors

Edit the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #2563eb;      /* Main brand color */
    --secondary-color: #7c3aed;    /* Accent color */
    --dark-bg: #0f172a;            /* Dark background */
    /* ... more variables */
}
```

### Adding More Objects

1. Add your object images to `thesis/iclr2026/objects/`
2. Update the objects gallery in `index.html`:

```html
<div class="object-item">
    <img src="thesis/iclr2026/objects/your-object.png" alt="Your Object">
    <div class="object-label">Your Object</div>
</div>
```

### Adding Research Papers

Add new essay cards in the `#essays` section:

```html
<div class="essay-card">
    <div class="essay-meta">
        <span class="essay-tag">Your Tag</span>
        <span class="essay-date">2025</span>
    </div>
    <h3>Paper Title</h3>
    <p>Description of your paper...</p>
    <a href="link-to-paper.md" class="essay-link">Read More →</a>
</div>
```

## 🔧 Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with CSS Grid and Flexbox
- **JavaScript**: Vanilla JS for interactions
- **Google Fonts**: Inter font family
- **SVG Icons**: Inline SVG for crisp icons

## 📝 License

This project is licensed under the terms specified in the LICENSE file.

## 🤝 Contributing

Contributions are welcome! Feel free to:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 🌟 Acknowledgments

- Research supported by [Your Institution/Grant]
- Object models from the ICLR 2026 submission dataset
- Inspired by modern web design principles

---

**Built with passion for advancing robotics research** 🚀
