# Portfolio Website

Personal portfolio website hosted on GitHub Pages at [selva.it.com](https://selva.it.com)

## Tech Stack

- HTML5, CSS3, JavaScript (ES6+)
- Bootstrap 4 (Grid & Components)
- jQuery + jQuery Easing
- Font Awesome Icons
- Canvas API (Particle Animation)

## Project Structure

```
selvathiruarul.github.io/
├── index.html                  # Main HTML file with all content
├── README.md                   # Project documentation
├── CNAME                       # Custom domain configuration (selva.it.com)
│
├── css/
│   ├── grayscale.css          # Main stylesheet
│   └── grayscale.min.css      # Minified version
│
├── js/
│   ├── grayscale.js           # Custom JavaScript (scroll, navbar)
│   └── grayscale.min.js       # Minified version
│
├── img/                        # Images and assets
│   ├── intro-bg.jpg           # Hero background
│   ├── downloads-bg.jpg       # Section backgrounds
│   └── *.jpg/png              # Project images
│
└── vendor/                     # Third-party libraries
    ├── bootstrap/
    │   ├── css/               # Bootstrap styles
    │   └── js/                # Bootstrap scripts
    ├── jquery/                # jQuery library
    ├── jquery-easing/         # Smooth scroll easing
    └── font-awesome/          # Icon library
```

## Key Features

### Animations
- **Particle Network**: Canvas-based animated background with connected particles
- **Counter Animation**: Stats count up when scrolled into view (Intersection Observer)
- **Smooth Scroll**: Custom easing for section navigation (600ms)
- **Hover Effects**: CSS transforms and transitions on cards

### Sections
1. Hero with particle animation
2. About (education, certifications)
3. Stats with animated counters
4. Professional experience timeline
5. Skills organized by category
6. Key achievements with impact metrics
7. Contact (LinkedIn/GitHub)

### Performance
- Particle animation pauses when tab inactive
- Responsive particle count based on screen size
- Lazy animation triggers via Intersection Observer
- Minified CSS/JS assets

## Local Development

```bash
# Start local server
python3 -m http.server 8000

# Visit in browser
http://localhost:8000
```

## Deployment

Automatically deployed via GitHub Pages when pushed to `master` branch.

Custom domain configured via CNAME file pointing to `selva.it.com`.

## Customization

### Colors
Primary accent color: `#42DCA3` (teal)
- Search and replace in `index.html` to change theme

### Animation Speed
- Scroll speed: `js/grayscale.js` line 12 (600ms)
- Particle speed: `index.html` particle animation section

### Stats
Edit `data-count` attributes in stat sections:
```html
<h3 class="stat-number" data-count="10">0</h3>
```

## Browser Support

Modern browsers with ES6+ support (Chrome, Firefox, Safari, Edge)

## Contact

- LinkedIn: [linkedin.com/in/selvamkt](https://www.linkedin.com/in/selvamkt/)
- GitHub: [github.com/selvathiruarul](https://github.com/selvathiruarul)
