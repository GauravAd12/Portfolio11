# Adhikari Gaurav - Portfolio Website

A modern, clean, and professional 3D-animated portfolio website showcasing the skills and projects of Adhikari Gaurav, a software developer.

## Features

### 🎨 Design & Animation
- **3D Animated Background**: Floating geometric shapes with smooth animations
- **Parallax Scrolling**: Subtle parallax effects for enhanced user experience
- **3D Hover Effects**: Interactive project cards with 3D transformations
- **Responsive Design**: Fully responsive layout that works on all devices
- **Modern UI**: Clean, minimal design with professional color scheme
- **PWA Ready**: Installable app with offline cache via Service Worker
- **SEO Optimized**: Meta tags, Open Graph, robots.txt, sitemap.xml
- **UX Enhancements**: Scroll progress bar and back-to-top button

### 📱 Sections
- **Hero Section**: Name, title, and introduction with animated background
- **Profile Section**: Professional summary and background
- **Skills Section**: Organized by Frontend, Backend, and DevOps categories
- **Projects Section**: Showcase of key projects with technology stacks
- **Certifications & Education**: Academic and professional achievements
- **Contact Section**: Contact form and professional information
- **Footer**: Social links and copyright information

### 🛠️ Technologies Used
- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Styling**: Custom CSS with modern features (Grid, Flexbox, Animations)
- **Icons**: Font Awesome
- **Fonts**: Google Fonts (Inter)
- **Animations**: CSS3 Animations and Transitions

## Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No additional dependencies required

### Installation
1. Clone or download the repository
2. Open `index.html` in your web browser
3. That's it! The website is ready to use

### File Structure
```
portfolio/
├── index.html              # Main HTML file
├── styles.css              # CSS styles and animations
├── script.js               # JavaScript functionality
├── Adhikari_Gaurav_CV.pdf  # CV/Resume file
└── README.md               # This file
```

## Customization

### Personal Information
To customize the website with your own information:

1. **Update HTML** (`index.html`):
   - Change name, title, and description in the hero section
   - Update profile text in the profile section
   - Modify skills, projects, certifications, and education
   - Update contact information and social links

2. **Update CV** (`Adhikari_Gaurav_CV.pdf`):
   - Replace with your own CV/Resume PDF file
   - Update the filename in the HTML if needed

### Styling
To customize the appearance:

1. **Colors**: Modify the CSS custom properties in `styles.css`
2. **Fonts**: Change the Google Fonts import in `index.html`
3. **Animations**: Adjust animation durations and effects in `styles.css`

### Contact Form
The contact form supports two modes:

1. API mode: Set `window.CONTACT_ENDPOINT` to your API URL (POST JSON: `{ name, email, subject, message }`).
2. Fallback mode: If no endpoint or API fails, it opens your email client with a pre-filled `mailto:`.

Update recipient in `script.js` if needed.

Example (add before `script.js` or inline in a separate file):

```html
<script>
  window.CONTACT_ENDPOINT = '';
  // e.g. 'https://your-api.example.com/contact'
</script>
```

### PWA
Already configured:
- `manifest.json` with app metadata
- `sw.js` service worker with cache-first strategy
- Registration in `script.js`

To test locally, serve over HTTP(S):
- VS Code Live Server, Python `http.server`, or any static server.

### Deploy
You can deploy as static files to:
- GitHub Pages, Netlify, Vercel, Cloudflare Pages, Firebase Hosting

Make sure the following files are at the site root:
- `index.html`, `styles.css`, `script.js`, `manifest.json`, `sw.js`, `robots.txt`, `sitemap.xml`

#### GitHub Pages quick start
1. Commit and push to a public repo
2. In GitHub: Settings → Pages → Source: `main` / root
3. Wait for publish; verify PWA install and offline

## Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ⚠️ Internet Explorer (not supported)

## Performance Features

- **Optimized Animations**: Hardware-accelerated CSS animations
- **Throttled Scroll Events**: Smooth performance on all devices
- **Lazy Loading**: Elements animate in as they come into view
- **Responsive Images**: Optimized for different screen sizes

## License

This project is open source and available under the [MIT License](LICENSE).

## Contact

**Adhikari Gaurav**
- Phone: +977 9867909910
- LinkedIn: [linkedin.com/in/adhikari-gaurav-2bb018307](https://www.linkedin.com/in/adhikari-gaurav-2bb018307)
- GitHub: [github.com/GauravAd12/Adhikari-gaurav](https://github.com/GauravAd12/Adhikari-gaurav)

---

*Built with ❤️ using modern web technologies*
