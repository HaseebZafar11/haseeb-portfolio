# Haseeb Zafar - Performance Marketer Portfolio

A professional portfolio website showcasing 6+ years of experience in digital marketing, performance marketing, and PPC optimization.

## Features

- **Responsive Design** - Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI** - Clean and professional interface with smooth animations
- **Sections Included**:
  - Hero section with call-to-action
  - About me with education details
  - Core skills with proficiency levels
  - Professional experience timeline
  - Key achievements and metrics
  - Contact information
  - Tools and technologies used

## Technologies Used

- HTML5
- CSS3 (with CSS Grid and Flexbox)
- Vanilla JavaScript
- GitHub Pages for hosting

## Getting Started

### Local Development

1. Clone this repository:
```bash
git clone https://github.com/yourusername/haseeb-portfolio.git
cd haseeb-portfolio
```

2. Open `index.html` in your web browser, or use a local server:
```bash
# Using Python 3
python -m http.server 8000

# Using Python 2
python -m SimpleHTTPServer 8000

# Using Node.js (if you have http-server installed)
http-server
```

3. Visit `http://localhost:8000` in your browser

### Deployment to GitHub Pages

1. Create a new repository on GitHub named `yourusername.github.io`

2. Push this portfolio code to the repository:
```bash
git remote add origin https://github.com/yourusername/yourusername.github.io.git
git branch -M main
git push -u origin main
```

3. Your portfolio will be live at `https://yourusername.github.io`

### Alternative: Deploy to a Custom Domain

If you want to use a custom domain:

1. Create a `CNAME` file in the repository root with your domain name
2. Configure your domain's DNS settings to point to GitHub Pages
3. Enable GitHub Pages in repository settings

## Customization

### Update Personal Information

Edit `index.html` to update:
- Name and title
- Contact information
- Experience details
- Skills and achievements
- Social media links

### Modify Colors

Edit `styles.css` to change the color scheme:
```css
:root {
    --primary-color: #8B3A3A;      /* Main color */
    --secondary-color: #FFD700;    /* Accent color */
    --text-dark: #333;
    --text-light: #666;
    --bg-light: #f5f5f5;
    --bg-white: #ffffff;
}
```

### Add New Sections

Follow the existing structure in `index.html` and add corresponding CSS in `styles.css`.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance

- Optimized for fast loading
- Minimal dependencies
- Responsive images
- Smooth animations

## File Structure

```
haseeb-portfolio/
├── index.html          # Main HTML file
├── styles.css          # Stylesheet
├── script.js           # JavaScript functionality
├── README.md           # This file
└── .gitignore          # Git ignore file
```

## Future Enhancements

- Add a blog section
- Implement contact form with backend
- Add case studies section
- Dark mode toggle
- Multi-language support

## License

This portfolio is open source and available for personal use.

## Contact

- **Email**: haseebzafar440@gmail.com
- **Phone**: 0324-5156131
- **Location**: Rawalpindi, Pakistan
- **LinkedIn**: [LinkedIn Profile](https://linkedin.com)

---

**Note**: This is a static website hosted on GitHub Pages. No backend or database is required.
