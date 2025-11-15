# Circles UI Kit - Modern SASS Component Library

> **A professional, modern UI style guide showcasing SASS best practices and modular CSS architecture**

[![Live Demo](https://img.shields.io/badge/demo-live-brightgreen)](https://brianwalkerdev.github.io/modern-web-page-sass)
[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Built with SASS](https://img.shields.io/badge/built%20with-SASS-ff69b4.svg)](https://sass-lang.com/)

![Circles UI Kit Preview](images/thumbnail.png)

## 🎯 Overview

Circles UI Kit is a comprehensive, production-ready style guide that demonstrates professional web design patterns and SASS architecture. Built by [Brian Walker](https://brianwalker.dev), this project showcases clean code, component-based styling, and responsive design principles perfect for modern web applications.

**Live Demo:** [https://brianwalkerdev.github.io/modern-web-page-sass](https://brianwalkerdev.github.io/modern-web-page-sass)

## ✨ Features

### Design Components
- **Typography System** - Beautiful, scalable type hierarchy with Lato font family
- **Button Variants** - Five distinct button styles (default, success, error, warning, info) with hover effects
- **Form Elements** - Accessible, styled form inputs with hidden labels and modern design
- **Image Styling** - Avatar circles and framed images with consistent styling
- **Responsive Grid** - Flexible 12-column grid system with media query breakpoints

### Technical Features
- 📦 Modular SCSS architecture with partials and imports
- 🎨 SASS variables for easy theming and customization
- 🔧 Mixins for reusable style patterns
- 📱 Mobile-first responsive design
- ♿ Accessibility-focused HTML with ARIA labels
- 🚀 Optimized build process with compressed CSS output
- 🎭 Smooth transitions and hover effects
- 🔍 SEO-optimized meta tags and semantic HTML

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| **HTML5** | Semantic markup structure |
| **SASS/SCSS** | Advanced CSS preprocessing |
| **CSS3** | Modern styling and animations |
| **Node.js** | Build tool runtime |
| **npm** | Package management |
| **Google Fonts** | Lato font family |

## 📁 Project Structure

```
modern-web-page-sass/
├── scss/                      # SASS source files
│   ├── base/                  # Base styles and resets
│   │   ├── _normalize.scss    # CSS normalization
│   │   ├── _typography.scss   # Type styles and hierarchy
│   │   └── _index.scss        # Base imports
│   ├── components/            # UI components
│   │   ├── _buttons.scss      # Button styles
│   │   ├── _forms.scss        # Form element styles
│   │   ├── _images.scss       # Image styling
│   │   ├── _navigation.scss   # Navigation components
│   │   ├── _grid.scss         # Grid system
│   │   ├── _media-queries.scss # Responsive breakpoints
│   │   └── _index.scss        # Component imports
│   ├── utilities/             # Utilities and helpers
│   │   ├── _variables.scss    # SASS variables
│   │   ├── _mixins.scss       # Reusable mixins
│   │   └── _index.scss        # Utility imports
│   └── styles.scss            # Main SASS entry point
├── css/                       # Compiled CSS output
│   └── styles.css             # Production stylesheet
├── images/                    # Image assets
│   ├── logo.png               # UI Kit logo
│   ├── avatar.png             # Avatar example
│   ├── image.png              # Sample image
│   └── thumbnail.png          # Project preview
├── index.html                 # Main HTML file
├── package.json               # npm configuration
├── .gitignore                 # Git ignore rules
└── README.md                  # This file
```

## 🚀 Installation

### Prerequisites
- Node.js (v14 or higher)
- npm (comes with Node.js)

### Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/brianwalkerdev/modern-web-page-sass.git
   cd modern-web-page-sass
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Build the CSS**
   ```bash
   npm run build
   ```

4. **Start development** (optional - watch for changes)
   ```bash
   npm run watch
   ```

5. **Open in browser**
   - Open `index.html` in your preferred browser
   - Or use a local server like Live Server in VS Code

## 📖 Usage

### Building for Production
Compile and minify SASS to compressed CSS:
```bash
npm run build
```

### Development Mode
Watch for SASS changes and auto-compile:
```bash
npm run watch
```

### Development Build
Compile SASS without compression (for debugging):
```bash
npm run build:dev
```

### Customizing Styles

#### Modify Colors
Edit `scss/utilities/_variables.scss`:
```scss
$button-default: #51ddfc;
$button-success: #63cc82;
$button-error: #e4757a;
// Add your custom colors...
```

#### Add New Components
1. Create a new file in `scss/components/`
2. Import it in `scss/components/_index.scss`
3. Run `npm run build` to compile

#### Adjust Breakpoints
Modify media queries in `scss/utilities/_variables.scss`:
```scss
$brk-narrow: '(min-width: 768px)';
$brk-wide: '(min-width: 1024px)';
```

## 🎨 Component Usage Examples

### Buttons
```html
<button class="btn default">Default Button</button>
<button class="btn success">Success Button</button>
<button class="btn error">Error Button</button>
```

### Grid System
```html
<div class="row">
  <div class="col-6">Half width</div>
  <div class="col-6">Half width</div>
</div>
```

### Form Elements
```html
<form class="form">
  <input class="input" type="text" placeholder="Username">
  <button class="btn default" type="submit">Submit</button>
</form>
```

## 🗺️ Roadmap

- [x] Core component library
- [x] Responsive grid system
- [x] Professional documentation
- [x] SEO optimization
- [ ] Dark mode theme toggle
- [ ] Additional button variants
- [ ] Advanced form components (select, radio, checkbox)
- [ ] JavaScript interactivity
- [ ] Animation library
- [ ] Component documentation site

## 🤝 Contributing

Contributions are welcome! This project is open for improvements and new features.

### How to Contribute

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### Contribution Guidelines
- Follow existing code style and structure
- Use meaningful commit messages
- Test your changes across browsers
- Update documentation as needed
- Ensure SASS compiles without errors

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Author

**Brian Walker**

- Website: [brianwalker.dev](https://brianwalker.dev)
- Email: contact@brianwalker.dev
- GitHub: [@brianwalkerdev](https://github.com/brianwalkerdev)
- Portfolio: Professional full-stack developer specializing in modern web technologies

## 🙏 Acknowledgements

- **[SASS](https://sass-lang.com/)** - Powerful CSS preprocessor
- **[Normalize.css](https://necolas.github.io/normalize.css/)** - CSS reset foundation
- **[Google Fonts](https://fonts.google.com/)** - Lato font family
- **Treehouse** - Original project inspiration from Techdegree program

---

<div align="center">

**⭐ Star this repository if you find it helpful!**

Built with ❤️ by [Brian Walker](https://brianwalker.dev) | [View More Projects](https://github.com/brianwalkerdev)

</div>
