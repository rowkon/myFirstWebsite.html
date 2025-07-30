# Guide Ourji - Sustainable Living Blog Website

A beautiful, modern blog website dedicated to promoting sustainable and eco-friendly living practices. This website serves as a platform to guide, teach, and help people understand their environmental impact and adopt sustainable lifestyle choices.

## 🌱 About

**Domain:** guide.ourji.com

Guide Ourji is more than just a blog—it's a community-driven platform that believes the world is all about helping each other. Our mission is to:

- **Guide People**: Provide practical guidance on sustainable living practices
- **Teach & Educate**: Share knowledge about environmental impact and solutions
- **Help Others**: Build a community where everyone can contribute to sustainable living

## ✨ Features

### 🎨 Design & User Experience
- **Modern, Responsive Design**: Fully responsive layout that works on all devices
- **Eco-Friendly Color Palette**: Green-themed design reflecting environmental consciousness
- **Smooth Animations**: Engaging animations and transitions throughout the site
- **Intuitive Navigation**: Easy-to-use navigation with smooth scrolling

### 📱 Responsive & Mobile-First
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Touch-Friendly**: Optimized for touch interactions
- **Cross-Device Compatibility**: Consistent experience across desktop, tablet, and mobile

### 🚀 Interactive Features
- **Dynamic Navigation**: Active link highlighting and smooth scrolling
- **Animated Counters**: Impact statistics with animated counters
- **Form Handling**: Newsletter subscription and contact forms with validation
- **Notification System**: User feedback for form submissions
- **Scroll to Top**: Convenient scroll-to-top button
- **Lazy Loading**: Optimized image loading for better performance

### 📝 Content Sections
- **Hero Section**: Compelling introduction with call-to-action buttons
- **About Section**: Mission statement with three core values
- **Blog Section**: Featured and regular blog posts about sustainability
- **Impact Section**: Environmental impact statistics
- **Newsletter**: Email subscription for updates
- **Contact Section**: Contact form and information
- **Footer**: Links, social media, and additional resources

### 🔧 Technical Features
- **Semantic HTML5**: Proper document structure and accessibility
- **CSS Custom Properties**: Maintainable CSS with CSS variables
- **Modern JavaScript**: ES6+ features with proper event handling
- **Performance Optimized**: Debounced scroll events and optimized animations
- **SEO Ready**: Proper meta tags and semantic structure

## 📁 File Structure

```
├── index.html          # Main HTML file
├── style.css           # CSS styles with eco-friendly design
├── script.js           # JavaScript functionality
├── images/             # Image assets
│   ├── profile.jpg     # Blog post images
│   └── w.jpg          # Additional images
└── README.md          # Documentation
```

## 🎨 Color Palette

The website uses an eco-friendly color scheme:

- **Primary Green**: `#2d7016` - Deep forest green for primary elements
- **Light Green**: `#4a9028` - Vibrant green for hover states
- **Accent Green**: `#6fbf3a` - Bright green for highlights
- **Forest Green**: `#1a4d0a` - Dark green for footer and headers
- **Sage Green**: `#a8c090` - Soft green for borders and accents
- **Warm Beige**: `#f5f3f0` - Natural background color
- **Earth Tones**: Supporting browns and neutrals

## 🚀 Quick Start

1. **Clone or Download** the repository
2. **Open** `index.html` in your web browser
3. **That's it!** The website is ready to use

No build process or dependencies required - it's a pure HTML, CSS, and JavaScript website.

## 📱 Browser Support

- ✅ Chrome (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 🛠 Customization

### Adding New Blog Posts

1. Open `index.html`
2. Find the blog section (`<section id="blog" class="blog">`)
3. Add a new `<article class="blog-card">` with the following structure:

```html
<article class="blog-card">
    <div class="blog-image">
        <img src="path/to/image.jpg" alt="Your Blog Post">
        <div class="blog-category">Category</div>
    </div>
    <div class="blog-content">
        <h3>Your Blog Post Title</h3>
        <p>Brief description of your blog post...</p>
        <div class="blog-meta">
            <span class="date">
                <i class="fas fa-calendar"></i>
                Date
            </span>
            <span class="read-time">
                <i class="fas fa-clock"></i>
                X min read
            </span>
        </div>
        <a href="#" class="read-more">Read More</a>
    </div>
</article>
```

### Updating Contact Information

1. Open `index.html`
2. Find the contact section (`<section id="contact" class="contact">`)
3. Update email addresses and contact details

### Customizing Colors

1. Open `style.css`
2. Modify the CSS custom properties in the `:root` section
3. The entire color scheme will update automatically

### Adding New Sections

1. Add your new section in `index.html`
2. Add corresponding styles in `style.css`
3. Update navigation links if needed

## 🌟 Blog Post Categories

The website supports various sustainability topics:

- **Zero Waste**: Reducing household waste
- **Renewable Energy**: Solar power and clean energy
- **Sustainable Food**: Eco-friendly eating habits
- **Green Transportation**: Eco-friendly travel options
- **Conservation**: Water and resource conservation
- **Eco-Home**: Sustainable home improvements

## 📊 Impact Metrics

The website showcases environmental impact through statistics:

- People educated about sustainability
- CO2 emissions saved
- Guides and articles published
- Global reach and community size

## 🔧 Advanced Features

### Form Integration

The contact and newsletter forms are ready for backend integration:

```javascript
// Newsletter form handling
newsletterForm.addEventListener('submit', (e) => {
    e.preventDefault();
    // Add your backend integration here
    // Example: fetch('/api/newsletter', { method: 'POST', ... })
});
```

### Analytics Integration

Add Google Analytics or other tracking:

```html
<!-- Add to <head> section -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_TRACKING_ID"></script>
```

### SEO Optimization

The website includes:
- Semantic HTML structure
- Meta tags for social sharing
- Alt text for images
- Proper heading hierarchy

## 🤝 Contributing

To contribute to the Guide Ourji website:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📞 Support

For support or questions about the website:

- **Email**: hello@guide.ourji.com
- **Website**: guide.ourji.com

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🌍 Mission Statement

At Guide Ourji, we believe that small changes can make a big impact. Through education, community support, and practical guidance, we're building a more sustainable future together. Every visitor to our site is a step toward a greener, more conscious world.

---

**Built with ❤️ for a sustainable future 🌱**