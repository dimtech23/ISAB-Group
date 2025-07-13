# ISAB Group - Professional Home Care & Consulting Website

A professional, responsive static website for ISAB Group, combining home care services and business consulting. Built with HTML, CSS, and JavaScript.

## 🌟 Features

- **Responsive Design**: Mobile-first approach with clean, modern UI
- **Professional Branding**: Teal, white, and gray color palette
- **Dual Service Focus**: Home care services and business consulting
- **Interactive Elements**: Smooth animations, form validation, and mobile navigation
- **Accessibility**: WCAG compliant with proper focus states and alt text
- **Performance Optimized**: Lazy loading, optimized images, and efficient CSS

## 📁 Project Structure

```
groupisb/
├── index.html              # Homepage
├── services.html           # Services page
├── about.html              # About Us page
├── contact.html            # Contact page
├── css/
│   └── style.css          # Main stylesheet
├── js/
│   └── script.js          # JavaScript functionality
├── images/
│   └── README.md          # Image requirements guide
└── README.md              # This file
```

## 🚀 Getting Started

### Prerequisites

- A modern web browser
- Basic understanding of HTML/CSS/JavaScript (for customization)

### Installation

1. **Clone or Download** the project files to your local machine
2. **Add Images**: Place required images in the `images/` folder (see `images/README.md` for details)
3. **Open**: Open `index.html` in your web browser

### Local Development

For local development, you can use any of these methods:

#### Method 1: Direct File Opening
```bash
# Simply open index.html in your browser
open index.html
```

#### Method 2: Using Python (if installed)
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

#### Method 3: Using Node.js (if installed)
```bash
# Install a simple HTTP server
npm install -g http-server

# Run the server
http-server
```

Then visit `http://localhost:8000` in your browser.

## 🎨 Customization

### Colors
The website uses CSS custom properties for easy color customization. Edit the `:root` section in `css/style.css`:

```css
:root {
    --primary-color: #008080;      /* Main teal color */
    --primary-dark: #006666;       /* Darker teal */
    --primary-light: #00a3a3;      /* Lighter teal */
    --secondary-color: #f8f9fa;    /* Light gray background */
    --text-dark: #2c3e50;          /* Dark text */
    --text-light: #6c757d;         /* Light text */
    /* ... other colors */
}
```

### Content
- **Text Content**: Edit the HTML files directly
- **Images**: Replace images in the `images/` folder
- **Contact Information**: Update phone, email, and address in all HTML files
- **Social Media**: Update social media links in the footer

### Forms
The contact form is currently set up for demonstration. To make it functional:

1. **Formspree** (Recommended for static sites):
   ```html
   <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
   ```

2. **Netlify Forms** (if hosting on Netlify):
   ```html
   <form name="contact" netlify>
   ```

3. **Custom Backend**: Modify the form action to point to your server

## 📱 Pages Overview

### Homepage (`index.html`)
- Hero section with dual CTAs
- Service highlights
- Consulting teaser
- Testimonials
- Final call-to-action sections

### Services (`services.html`)
- Detailed care service descriptions
- Consulting package pricing
- Service statistics
- Call-to-action sections

### About Us (`about.html`)
- Mission and values
- Brand story
- Team member profiles
- Company statistics
- Philosophy statement

### Contact (`contact.html`)
- Contact information cards
- Contact form
- Interactive map
- FAQ preview
- Emergency contact information

## 🔧 Technical Details

### CSS Features
- CSS Grid and Flexbox for layouts
- CSS Custom Properties for theming
- Smooth transitions and animations
- Mobile-first responsive design
- Hover effects and interactive states

### JavaScript Features
- Mobile navigation toggle
- Smooth scrolling
- Form validation
- FAQ accordion functionality
- Intersection Observer for animations
- Back-to-top button
- Notification system

### Browser Support
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Internet Explorer 11+ (with some limitations)

## 📸 Required Images

See `images/README.md` for a complete list of required images and specifications.

### Quick Image Checklist
- [ ] `logo.png` - Company logo
- [ ] `favicon.ico` - Website favicon
- [ ] `hero-image.jpg` - Hero section image
- [ ] `consulting.jpg` - Consulting services image
- [ ] Service images (4 total)
- [ ] Team member photos (4 total)
- [ ] Testimonial photos (3 total)
- [ ] About page images (2 total)

## 🚀 Deployment

### Static Hosting Options

1. **Netlify** (Recommended)
   - Drag and drop the folder to Netlify
   - Automatic HTTPS and CDN
   - Form handling included

2. **GitHub Pages**
   - Push to GitHub repository
   - Enable GitHub Pages in settings

3. **Vercel**
   - Connect GitHub repository
   - Automatic deployments

4. **Traditional Web Hosting**
   - Upload files via FTP
   - Ensure proper file permissions

### SEO Optimization

The website includes:
- Proper meta tags
- Semantic HTML structure
- Alt text for images
- Clean URL structure
- Fast loading times

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📄 License

This project is created for ISAB Group. Please ensure you have the right to use any images or content included.

## 📞 Support

For questions or support:
- Email: groupisab@gmail.com
- Phone: (608) 239-1627 / (608) 335-6752

## 🔄 Updates

### Version 1.0.0
- Initial website launch
- Responsive design
- Contact form functionality
- SEO optimization
- Accessibility compliance

---

**Built with ❤️ for ISAB Group** 