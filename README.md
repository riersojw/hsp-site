# HSP Sound Services Website

A modern, responsive website for HSP Sound Services - showcasing audio and DJ services with a sleek, professional design.

## Features

- **Modern Design**: Clean, dark theme with cyan accents
- **Fully Responsive**: Optimized for mobile, tablet, and desktop devices
- **Animated Elements**: 
  - Animated waveform graphics
  - Scroll animations for service cards
  - Parallax hero section
  - Smooth transitions and hover effects
- **Mobile-Friendly Navigation**: Hamburger menu for mobile devices
- **GitHub Pages Ready**: Static HTML/CSS/JavaScript setup

## File Structure

```
hsp-site/
├── index.html          # Main HTML file
├── styles.css          # All styling and responsive design
├── script.js           # Interactive functionality
├── README.md           # This file
└── resources/          # Images and assets
    ├── headphones.png  # Logo image
    └── stage.jpg       # Hero background image
```

## Deployment to GitHub Pages

### Option 1: Deploy from Main Branch

1. **Initialize Git Repository** (if not already done):
   ```bash
   git init
   git add .
   git commit -m "Initial commit: HSP website"
   ```

2. **Create a GitHub Repository**:
   - Go to [GitHub](https://github.com)
   - Click "New Repository"
   - Name it `hsp-site` (or your preferred name)
   - Don't initialize with README (you already have one)

3. **Push to GitHub**:
   ```bash
   git remote add origin https://github.com/YOUR-USERNAME/hsp-site.git
   git branch -M main
   git push -u origin main
   ```

4. **Enable GitHub Pages**:
   - Go to your repository on GitHub
   - Click "Settings"
   - Scroll to "Pages" in the left sidebar
   - Under "Source", select "main" branch
   - Select "/ (root)" folder
   - Click "Save"

5. **Access Your Site**:
   - Your site will be available at: `https://YOUR-USERNAME.github.io/hsp-site/`
   - Note: It may take a few minutes for the site to become available

### Option 2: Custom Domain (Optional)

If you want to use `yourdomain.com` instead of `github.io`:

1. Add a `CNAME` file to your repository with your domain name
2. Configure your domain's DNS settings (A records or CNAME)
3. Update GitHub Pages settings with your custom domain

## Local Development

To view the website locally:

1. **Simple Method**: Open `index.html` directly in your browser

2. **With Live Server** (recommended for development):
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Or using Node.js
   npx serve
   ```
   Then open `http://localhost:8000` in your browser

## Customization

### Update Content

- **Logo**: Replace `resources/headphones.png` with your logo
- **Background**: Replace `resources/stage.jpg` with your preferred image
- **Text**: Edit `index.html` to update service descriptions, titles, etc.
- **Colors**: Modify CSS variables in `styles.css`:
  ```css
  :root {
      --primary-color: #00bcd4;  /* Cyan accent color */
      --primary-hover: #00acc1;  /* Hover state */
      /* ... other colors ... */
  }
  ```

### Add More Sections

To add additional sections (e.g., testimonials, gallery, contact form):

1. Add the HTML in `index.html`
2. Add corresponding styles in `styles.css`
3. Add any interactive functionality in `script.js`

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with CSS Grid, Flexbox, animations
- **JavaScript (ES6+)**: Interactive features and scroll animations
- **SVG**: Scalable icons for services

## Future Enhancements

Consider adding:
- Contact form with email integration
- Photo/video gallery
- Client testimonials section
- Music player or audio samples
- Blog or news section
- Social media integration

## License

This project is open source and available for modification and use.

## Support

For issues or questions, please open an issue on the GitHub repository.
