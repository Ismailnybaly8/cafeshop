# The Cozy Cup - Cafe Website

A modern, responsive cafe website built with HTML, CSS, and JavaScript. This website showcases a fictional cafe called "The Cozy Cup" with a professional design and interactive features.

## Features

### 🎨 Design & Layout
- **Modern Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Beautiful Color Scheme**: Warm brown tones (#8B4513, #D2691E) creating a cozy coffee house atmosphere
- **Smooth Animations**: Scroll-triggered animations, typing effects, and interactive elements
- **Professional Typography**: Using Google Fonts (Poppins) for clean, readable text

### 📱 Interactive Elements
- **Mobile-First Navigation**: Hamburger menu for mobile devices
- **Smooth Scrolling**: Navigation links smoothly scroll to sections
- **Menu Categories**: Interactive menu filtering (Coffee, Tea, Food, Desserts)
- **Contact Form**: Functional contact form with validation
- **Newsletter Signup**: Email subscription with success notifications
- **Loading Animation**: Coffee-themed page loader

### 🍽️ Sections Included
1. **Hero Section**: Eye-catching welcome banner with call-to-action buttons
2. **About Section**: Cafe story and features (100% Organic, Made with Love, Award Winning)
3. **Menu Section**: Complete menu with categories and pricing
4. **Gallery Section**: Image placeholders for cafe photos
5. **Contact Section**: Contact information and contact form
6. **Footer**: Social links, quick navigation, and newsletter signup

### 🎮 Special Features
- Easter egg: Try the Konami Code (↑↑↓↓←→←→BA) for a fun surprise!
- Notification System: Success/error messages for form submissions
- Auto-hiding Navigation: Navbar hides when scrolling down, shows when scrolling up
- Progressive Enhancement: Works without JavaScript, enhanced with it

## File Structure

```
cafeshop/
├── index.html          # Main HTML file
├── styles.css          # Complete CSS styling
├── script.js           # JavaScript functionality
└── README.md           # This documentation
```

## How to Use

### Option 1: Direct File Opening
1. Navigate to the `cafeshop` folder
2. Double-click `index.html` to open in your default browser

### Option 2: Local Server (Recommended)
For the best experience and to avoid CORS issues:

```bash
# Using Python 3
cd cafeshop
python -m http.server 8000

# Using Python 2
cd cafeshop
python -m SimpleHTTPServer 8000

# Using Node.js (if you have it installed)
npx http-server cafeshop
```

Then open `http://localhost:8000` in your browser.

## Browser Compatibility

- ✅ Chrome (Latest)
- ✅ Firefox (Latest)
- ✅ Safari (Latest)
- ✅ Edge (Latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## Technologies Used

- **HTML5**: Semantic markup with accessibility considerations
- **CSS3**: 
  - Flexbox and CSS Grid for layouts
  - CSS animations and transitions
  - CSS custom properties (variables)
  - Responsive design with media queries
- **JavaScript (ES6+)**:
  - Modern JavaScript features
  - DOM manipulation
  - Event handling
  - Form validation
  - Intersection Observer API for scroll animations

## Customization

### Changing Colors
The main colors can be changed in `styles.css`:
```css
:root {
  --primary-color: #8B4513;    /* Main brown */
  --secondary-color: #D2691E;  /* Light brown */
  --background-color: #f5f3f0; /* Light background */
}
```

### Updating Content
- **Cafe Name**: Change "The Cozy Cup" throughout `index.html`
- **Menu Items**: Update the menu section with your actual offerings
- **Contact Information**: Modify the contact section with real details
- **Images**: Replace placeholder divs with actual images

### Adding Real Images
1. Create an `images` folder in the cafeshop directory
2. Add your images (recommended sizes):
   - Hero background: 1920x1080px
   - About section: 400x300px
   - Gallery items: 300x250px each
3. Update image paths in `index.html`

## Performance Features

- **Optimized Loading**: Minimal external dependencies
- **Efficient Animations**: Uses CSS transforms for smooth performance
- **Lazy Loading Ready**: Structure supports image lazy loading
- **Progressive Enhancement**: Core functionality works without JavaScript

## Accessibility

- Semantic HTML structure
- Proper heading hierarchy
- Alt text support for images
- Keyboard navigation support
- High contrast color ratios
- Responsive text sizing

## Future Enhancements

Potential additions you could implement:
- Real image gallery with lightbox
- Online ordering system
- Location map integration
- Social media feed integration
- Customer reviews section
- Blog/news section
- Event calendar
- Multi-language support

## License

This is a template project created for educational purposes. Feel free to use and modify for your own cafe or business.

---

**Created with ❤️ for cafe owners who want a professional online presence**
