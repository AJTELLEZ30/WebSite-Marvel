
# 🦸‍♂️ Marvel Website

A comprehensive Marvel-themed static website featuring blog functionality, image galleries, subscription management, and educational content about the Marvel Cinematic Universe.

## 🚀 Features

- **🏠 Homepage**: Marvel content hub with hero sections, galleries, and subscription plans
- **📝 Blog System**: Article listings with categories, search, and comment functionality  
- **🖼️ Gallery**: Interactive image viewer with modal display
- **📞 Contact**: Contact form with Google Maps integration
- **ℹ️ About**: Stan Lee tribute and Marvel history
- **💰 Pricing**: Disney+ subscription plans

## 🛠️ Tech Stack

| Technology | Version | Purpose |
|------------|---------|---------|
| Bootstrap | v5.3.2 | CSS Framework |
| jQuery | 3.2.1 | DOM Manipulation |
| Font Awesome | 6.x | Icon System |
| EmailJS | 3.x | Email Integration | [1](#0-0) 

## 📁 Project Structure

```
MarvelWebsite/
├── index.html                 # Homepage
├── pages/
│   ├── blog.html             # Blog listing
│   ├── details.html          # Blog details
│   ├── gallery.html          # Image gallery
│   ├── contact.html          # Contact form
│   └── about.html            # About page
├── assets/
│   ├── css/main.css          # Compiled styles
│   ├── js/                   # JavaScript modules
│   └── images/               # Static assets
└── components/               # Reusable HTML components
```

## 🎯 Getting Started

### Prerequisites

- Modern web browser
- Local web server (for proper component loading)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Gaitan19/MarvelWebsite.git
cd MarvelWebsite
```

2. Serve the files using a local web server:
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve .
```

3. Open `http://localhost:8000` in your browser

## 🏗️ Architecture

The website uses a component-based architecture with dynamic content loading: [2](#0-1) [3](#0-2) 

### Dynamic Components

- **Header**: Navigation loaded via `header.js`
- **Footer**: Footer content loaded via `footer.js`  
- **Hero**: Dynamic hero sections via `heroes.js`
- **Modal**: Image gallery modals via `modal.js`

## 🎨 Styling System

The project implements Bootstrap v5.3.2 with custom CSS variables for theming: [4](#0-3) 

### Theme Support
- Light and dark theme compatibility
- Responsive design with mobile-first approach
- Custom Marvel-themed color palette

## 🔗 External Integrations

| Service | Purpose | Implementation |
|---------|---------|----------------|
| Marvel Fandom Wiki | External content links | Direct navigation |
| Disney+ | Subscription integration | Pricing page links |
| YouTube | Video content | MCU trailers |
| EmailJS | Contact forms | Newsletter signup | [5](#0-4) 

## 📱 Pages Overview

### Homepage (`index.html`)
- Marvel content hub with comprehensive sections
- Tabbed content for live streams and news
- Image gallery with modal viewing
- Subscription plans and FAQ

### Blog System (`pages/blog.html`, `pages/details.html`)
- Article listings with metadata
- Category filtering and search
- Comment system with reply functionality
- Author profiles and popular posts [6](#0-5) 

### Gallery (`pages/gallery.html`)
- Responsive image grid layout
- Modal image viewer
- Dynamic hero content [7](#0-6) 

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👨‍💻 Author

**Kenley Gaitan** - [GitHub Profile](https://github.com/Gaitan19)

## 🙏 Acknowledgments

- Marvel Comics for inspiration
- Bootstrap team for the framework
- Font Awesome for icons
- Stan Lee for creating the Marvel universe

---
