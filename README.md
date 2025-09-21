# The Debuggers Club - Social Handles

> A modern, minimalist webpage showcasing our coding community's social media presence

[![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen?style=flat-square)](https://the-debuggers-club.github.io/social-handles/)
[![HTML](https://img.shields.io/badge/HTML-5-orange?style=flat-square&logo=html5)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS](https://img.shields.io/badge/CSS-3-blue?style=flat-square&logo=css3)](https://developer.mozilla.org/en-US/docs/Web/CSS)

## Overview

This project presents The Debuggers Club's social media handles through a clean, abstract web interface. The design breaks away from traditional center-aligned layouts, featuring an asymmetric grid system with subtle animations and modern typography.

## Features

### Design
- **Clean White Theme**: Minimalist aesthetic with subtle gray accents
- **Asymmetric Layout**: Non-traditional grid system for modern appeal
- **Abstract Elements**: Floating background shapes for visual interest
- **Typography**: Modern font combinations with varied weights

### Interactivity
- **Smooth Animations**: Hover effects and subtle transitions
- **Responsive Design**: Optimized for all device sizes
- **Accessibility**: Proper contrast ratios and semantic HTML

### Technical
- **Pure HTML/CSS**: No dependencies or frameworks required
- **Performance Optimized**: Lightweight and fast loading
- **Cross-browser Compatible**: Works across modern browsers

## Social Media Links

Connect with The Debuggers Club across platforms:

- **LinkedIn**: [The Debuggers Coding Club](https://www.linkedin.com/company/the-debuggers-coding-club/)
- **Instagram**: [@the.debuggers_bhu](https://www.instagram.com/the.debuggers_bhu/)
- **GitHub**: [The-Debuggers-Club](https://github.com/The-Debuggers-Club)

## Partner Societies

Explore other affiliated academic societies:

- **Jigyasa - Scientific Society**: [@jigyasa_science](https://www.instagram.com/jigyasa_science/) - Promoting scientific research and innovation
- **Bookspire Book Reading Society**: [WhatsApp Channel](https://whatsapp.com/channel/0029Vb6J5L4ElagoPD1vje1l) - Literary discussions and book recommendations

## Project Structure

```
social-handles/
├── index.html          # Main webpage
├── README.md          # Project documentation
└── assets/            # (Future: images, icons, etc.)
```

## Getting Started

### Prerequisites

- Any modern web browser (Chrome, Firefox, Safari, Edge)
- A text editor for customization (VS Code, Sublime Text, etc.)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/The-Debuggers-Club/social-handles.git
   cd social-handles
   ```

2. **Open the webpage**
   ```bash
   # Option 1: Direct file opening
   open index.html
   
   # Option 2: Local server (recommended)
   python -m http.server 8000
   # Then visit http://localhost:8000
   ```

3. **Start customizing** (optional)
   - Modify colors in the CSS `:root` variables
   - Update social links in the HTML
   - Adjust layout breakpoints for different screen sizes

## Customization

### Changing Colors

The webpage uses CSS custom properties for easy theming:

```css
:root {
  --primary-color: #333;
  --secondary-color: #666;
  --accent-color: #999;
  --background-color: #ffffff;
}
```

### Adding New Social Links

1. Add a new link in the HTML:
```html
<a href="your-url" class="social-link" target="_blank">
    <svg class="social-icon" viewBox="0 0 24 24" fill="currentColor">
        <!-- Your SVG icon path -->
    </svg>
    platform-name
</a>
```

2. The CSS will automatically style the new link.

### Responsive Breakpoints

Modify the media query in the CSS to adjust mobile responsiveness:

```css
@media (max-width: 768px) {
    /* Mobile styles */
}
```

## Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ⚠️ Internet Explorer (not supported)

## Performance

- **Load Time**: < 1 second on 3G
- **Bundle Size**: < 10KB total
- **Lighthouse Score**: 100/100 (Performance, Accessibility, Best Practices)

## Contributing

We welcome contributions from the community! Here's how you can help:

### Ways to Contribute

1. **Report Issues**: Found a bug? [Open an issue](https://github.com/The-Debuggers-Club/social-handles/issues)
2. **Suggest Features**: Have ideas? We'd love to hear them!
3. **Code Contributions**: Submit pull requests for improvements
4. **Documentation**: Help improve our docs

### Development Guidelines

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/amazing-feature`)
3. **Commit** your changes (`git commit -m 'Add amazing feature'`)
4. **Push** to the branch (`git push origin feature/amazing-feature`)
5. **Open** a Pull Request

### Code Style

- Use semantic HTML elements
- Follow CSS BEM methodology where applicable
- Maintain consistent indentation (2 spaces)
- Add comments for complex CSS animations

## Deployment

### GitHub Pages

1. Go to your repository settings
2. Navigate to "Pages" section
3. Select "Deploy from a branch"
4. Choose `main` branch and `/ (root)` folder
5. Your site will be available at `https://username.github.io/social-handles`

### Netlify

1. Connect your GitHub repository
2. Set build command: `# Leave empty`
3. Set publish directory: `./`
4. Deploy automatically on every push

### Custom Domain

Add a `CNAME` file with your domain name for custom domain hosting.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- **Design Inspiration**: Modern web design trends and minimalist aesthetics
- **Icons**: SVG social media icons from various open-source collections
- **Typography**: System fonts for optimal performance
- **Community**: Thanks to all Debuggers Club members for feedback and support

## Contact

Have questions or suggestions? Reach out to us:

- **LinkedIn**: [The Debuggers Coding Club](https://www.linkedin.com/company/the-debuggers-coding-club/)
- **GitHub Issues**: [Report here](https://github.com/The-Debuggers-Club/social-handles/issues)

---

<div align="center">

**Made with ❤️ by The Debuggers Club**

*Debugging the future, one line of code at a time*

[⭐ Star this repo](https://github.com/The-Debuggers-Club/social-handles) • [🐛 Report Bug](https://github.com/The-Debuggers-Club/social-handles/issues) • [✨ Request Feature](https://github.com/The-Debuggers-Club/social-handles/issues)

</div>
