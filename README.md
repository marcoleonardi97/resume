# Marco Leonardi - Portfolio Website

[![Live Demo](https://img.shields.io/badge/demo-live-brightgreen)](https://marcoleonardi97.github.io/hello/)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

A modern, space-themed portfolio website showcasing my work at the intersection of astrophysics and business.

## 🌟 Features

- **Modern Design**: Dark theme with gradient accents inspired by nebulae and galaxies
- **Smooth Animations**: Subtle scroll animations and interactive hover effects
- **Fully Responsive**: Optimized for desktop, tablet, and mobile devices
- **Performance Optimized**: Fast loading with minimal dependencies
- **Accessible**: Semantic HTML and ARIA labels for screen readers

## 🚀 Live Demo

Visit the live site: [marcoleonardi97.github.io/hello](https://marcoleonardi97.github.io/hello/)

## 📋 Sections

- **Hero**: Eye-catching introduction with animated background
- **About**: Brief overview of my background in astrophysics and business
- **Experience**: Detailed work history including research and business roles
- **Education**: Academic background spanning three institutions across Europe
- **Skills**: Technical and soft skills organized by category
- **Contact**: Easy ways to get in touch

## 🛠️ Technologies

- **HTML5**: Semantic markup
- **CSS3**: Custom styles with modern features (Grid, Flexbox, Animations)
- **JavaScript**: Vanilla JS for smooth scrolling and scroll animations
- **Font Awesome**: Icon library
- **Google Fonts**: Space Grotesk and Inter typefaces

## 📦 Setup & Deployment

### Local Development

1. Clone the repository:
```bash
git clone https://github.com/marcoleonardi97/hello.git
cd hello
```

2. Open `index.html` in your browser:
```bash
# On macOS
open index.html

# On Linux
xdg-open index.html

# On Windows
start index.html
```

Or use a local server:
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000

# Node.js (with http-server)
npx http-server
```

3. Visit `http://localhost:8000` in your browser

### GitHub Pages Deployment

This site is automatically deployed via GitHub Pages:

1. Push changes to the `main` branch
2. GitHub Pages will automatically build and deploy
3. Visit your site at `https://[username].github.io/[repository-name]`

To enable GitHub Pages:
1. Go to repository Settings → Pages
2. Select source branch (usually `main`)
3. Select folder (`/root` or `/docs`)
4. Save and wait for deployment

## 🎨 Customization

### Colors

The color scheme is defined in CSS variables at the top of the `<style>` section:

```css
:root {
    --primary: #667eea;      /* Primary purple */
    --secondary: #764ba2;    /* Secondary purple */
    --accent: #f093fb;       /* Pink accent */
    --dark: #0f172a;         /* Background dark */
    --dark-alt: #1e293b;     /* Alternate dark */
    --text: #e2e8f0;         /* Main text */
    --text-muted: #94a3b8;   /* Muted text */
}
```

### Content

Edit the HTML directly to update:
- Personal information
- Work experience
- Education details
- Skills and technologies
- Contact information

### CV Download Link

Update the CV download link in the hero section:
```html
<a href="YOUR_CV_LINK_HERE" class="btn-rounded-white">Download CV</a>
```

## 📱 Responsive Design

The site is fully responsive with breakpoints at:
- **Mobile**: < 768px
- **Tablet**: 768px - 1024px
- **Desktop**: > 1024px

## ⚡ Performance

- No external JavaScript libraries required
- Minimal CSS (all inline for faster loading)
- Optimized animations using CSS transforms
- Lazy loading images (if added)

## 🤝 Contributing

While this is a personal portfolio, suggestions and improvements are welcome!

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/improvement`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 📬 Contact

Marco Leonardi
- Email: m.leonardi.2@umail.leidenuniv.nl
- Location: Leiden, Netherlands
- GitHub: [@marcoleonardi97](https://github.com/marcoleonardi97)

## 🙏 Acknowledgments

- Design inspiration from modern portfolio templates
- Font Awesome for icons
- Google Fonts for typography
- The open-source community

---

⭐ If you found this portfolio template helpful, please consider giving it a star!
