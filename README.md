# Professional Academic Portfolio

A modern, responsive academic portfolio website designed for graduate students and researchers. This portfolio showcases research, publications, teaching experience, and professional achievements with a clean, professional design.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Interactive Elements**: Smooth scrolling, hover effects, and scroll-triggered animations
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Professional Sections**: 
  - Hero section with introduction
  - About section with education and statistics
  - Research interests with icons
  - Publications list
  - Teaching experience
  - Professional timeline
  - Contact information with social links

## File Structure

```
academic-portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styling
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## Customization Guide

### Personal Information

1. **Name and Title**: Update the name and title in the navigation and hero section
2. **Contact Information**: Modify email, phone, location, and website in the contact section
3. **Social Links**: Update LinkedIn, Twitter, GitHub, and Google Scholar links

### Content Sections

#### About Section
- Update the personal description
- Modify education details (degrees, institutions, years)
- Adjust statistics (publications, citations, presentations, awards)

#### Research Section
- Replace research areas with your own interests
- Update icons using Font Awesome classes
- Modify descriptions to match your research focus

#### Publications
- Replace with your actual publications
- Update authors, journals, and citation counts
- Add more publications as needed

#### Teaching Experience
- Update course names, institutions, and semesters
- Modify course descriptions
- Adjust student counts and ratings

#### Professional Experience
- Replace with your work history
- Update job titles, organizations, and dates
- Modify job descriptions

### Styling Customization

#### Colors
The portfolio uses a blue-purple gradient theme. To change colors:

1. **Primary Colors**: Update `#3498db` (blue) and `#667eea` (purple) in `styles.css`
2. **Background Colors**: Modify `#f8f9fa` for section backgrounds
3. **Text Colors**: Update `#2c3e50` for headings and `#666` for body text

#### Fonts
- The portfolio uses Inter font from Google Fonts
- To change fonts, update the Google Fonts link in `index.html`

### Adding New Sections

To add a new section:

1. Add the HTML structure in `index.html`
2. Add corresponding CSS in `styles.css`
3. Update navigation menu if needed
4. Add any JavaScript functionality in `script.js`

## Browser Compatibility

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers

## Performance Features

- Optimized CSS with efficient selectors
- Minimal JavaScript for smooth performance
- Responsive images and icons
- Smooth scrolling and animations
- Loading screen for better user experience

## SEO Optimization

The portfolio includes:
- Semantic HTML structure
- Meta tags for viewport and character encoding
- Descriptive title and headings
- Alt text for images (when added)

## Deployment

### Local Development
1. Download all files to a folder
2. Open `index.html` in a web browser
3. For live development, use a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   ```

### Web Hosting
Upload the files to any web hosting service:
- GitHub Pages
- Netlify
- Vercel
- Traditional web hosting

## Customization Tips

### Adding a Profile Photo
1. Replace the placeholder icon in the hero section
2. Add your photo with proper sizing (300x300px recommended)
3. Update the CSS for the profile image

### Adding More Publications
1. Copy the publication item structure
2. Update the publication number
3. Add your publication details

### Modifying the Timeline
1. Add or remove timeline items
2. Update dates and descriptions
3. The timeline automatically adjusts for odd/even positioning

### Adding Animations
The portfolio includes scroll-triggered animations. To add more:
1. Add the `animate-in` class to elements
2. Update the JavaScript observer to watch new elements

## Support

For customization help or bug reports:
1. Check the browser console for JavaScript errors
2. Validate HTML and CSS
3. Test on different devices and browsers

## License

This portfolio template is free to use and modify for personal and academic purposes.

## Credits

- Font Awesome for icons
- Google Fonts for typography
- Inter font family
- CSS Grid and Flexbox for layout
- Modern CSS features for animations and effects

---

**Note**: Remember to replace all placeholder content with your actual information before deploying your portfolio.

