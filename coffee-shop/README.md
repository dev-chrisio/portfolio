# Brew & Bean - Minimalist Coffee Shop Website

A modern, responsive static website for a minimalist coffee shop built with HTML, CSS, and React. Featuring a clean design with a sophisticated color palette and smooth animations.

## 🎨 Design Features

- **Minimalist Aesthetic**: Clean lines, ample whitespace, and elegant typography
- **Responsive Design**: Fully optimized for desktop, tablet, and mobile devices
- **Modern Color Scheme**:
  - Primary: `#FFFFFF` (White)
  - Secondary: `#071952` (Deep Navy Blue)
  - Accent: `#088395` (Teal)
- **Smooth Animations**: Subtle transitions and hover effects
- **High-Quality Images**: Professional coffee shop imagery
- **Accessibility**: WCAG compliant with reduced motion support

## 📁 Project Structure

```
coffee-shop/
├── index.html          # Main HTML file with embedded styles
├── styles.css          # Comprehensive CSS stylesheet
└── README.md           # Project documentation
```

## 🚀 Features

### Navigation
- Fixed navigation bar with smooth scrolling
- Logo and menu links
- Hover effects with accent color

### Hero Section
- Full-screen hero with gradient background
- Animated background image overlay
- Call-to-action button
- Smooth fade-in animation

### About Section
- Two-column layout (text + image)
- Responsive grid that stacks on mobile
- Hover effects on images

### Menu Section
- Grid layout showcasing 6 coffee items
- Item cards with descriptions and prices
- Hover animations with shadow effects
- Responsive auto-fit grid

### Contact Section
- Location, hours, and contact information
- Three-column card layout
- Hover effects on contact cards

### Footer
- Copyright information
- Dark background with white text

## 💻 Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Advanced styling with animations and media queries
- **React**: JavaScript library (CDN included)
- **Tailwind CSS**: Utility-first CSS framework (CDN included)
- **Unsplash**: High-quality stock images

## 📱 Responsive Breakpoints

- **Desktop**: 1024px and above
- **Tablet**: 768px - 1023px
- **Mobile**: Below 768px
- **Small Mobile**: Below 480px

## 🎯 How to Use

### Option 1: Direct File Access
1. Download or clone the repository
2. Open `coffee-shop/index.html` in your web browser
3. No build process or dependencies required

### Option 2: GitHub Pages
1. Push the files to your GitHub repository
2. Enable GitHub Pages in repository settings
3. Access the website via the provided GitHub Pages URL

### Option 3: Local Server
```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (http-server)
npx http-server

# Using PHP
php -S localhost:8000
```

Then navigate to `http://localhost:8000/coffee-shop/`

## 🎨 Customization

### Change Colors
Edit the CSS variables in `styles.css` or the `<style>` tag in `index.html`:

```css
:root {
    --primary: #FFFFFF;      /* Main background */
    --secondary: #071952;    /* Text and headers */
    --accent: #088395;       /* Buttons and highlights */
}
```

### Update Content
- **Business Name**: Replace "Brew & Bean" throughout the HTML
- **Menu Items**: Edit the menu section with your offerings
- **Contact Info**: Update location, hours, and contact details
- **Images**: Replace image URLs with your own

### Modify Typography
Change font sizes, weights, and letter-spacing in the CSS:

```css
.hero h1 {
    font-size: 4rem;           /* Adjust size */
    font-weight: 300;          /* Adjust weight */
    letter-spacing: 2px;       /* Adjust spacing */
}
```

### Add New Sections
Copy the section structure and customize:

```html
<section id="new-section" class="section">
    <h2 class="section-title">Section Title</h2>
    <!-- Your content here -->
</section>
```

## 🔧 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## ♿ Accessibility

- Semantic HTML structure
- Proper heading hierarchy
- Color contrast ratios meet WCAG AA standards
- Reduced motion support for animations
- Keyboard navigation support

## 📊 Performance

- Lightweight HTML/CSS (no build process needed)
- Optimized images from Unsplash
- Minimal JavaScript dependencies
- Fast load times
- Mobile-first responsive design

## 📝 License

This project is open source and available for personal and commercial use.

## 🤝 Contributing

Feel free to fork, modify, and improve this template for your own coffee shop or business.

## 📧 Contact

For questions or suggestions, please reach out to the project maintainer.

---

**Created with ❤️ for coffee lovers and minimalist design enthusiasts**

Last Updated: April 28, 2026