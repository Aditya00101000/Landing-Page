# Landing-Page

# Modern Web Styling and Interaction Library

A modern and advanced CSS and JavaScript library that provides beautiful styling, animations, and interactive features for web applications.

## Features

### CSS Features
- 🎨 Modern color scheme with CSS variables
- 📱 Fully responsive design
- 🎭 Smooth transitions and animations
- 🃏 Card components with hover effects
- 🔘 Modern button styles
- 🧭 Sticky navigation
- 📊 Grid layout system
- 📝 Form styling
- 🎯 Custom scrollbar
- 🌓 Dark mode support
- 📖 Modern typography

### JavaScript Features
- 🚀 Smooth scroll functionality
- 👁️ Intersection Observer for scroll animations
- 🌓 Theme toggle with local storage
- ✅ Form validation
- ⚡ Performance optimizations (debounce and throttle)
- 🧭 Navigation scroll effects
- 📱 Responsive navigation handling
- 🌓 Dark mode detection and persistence

## Installation

1. Include the CSS file in your HTML:
```html
<link rel="stylesheet" href="styles.css">
```

2. Add the JavaScript file at the end of your body tag:
```html
<script src="script.js"></script>
```

## Usage

### CSS Classes

#### Layout
- `.container` - Main content container
- `.grid` - Grid layout system
- `.card` - Card component

#### Navigation
- `.nav` - Navigation container
- `.nav-list` - Navigation list
- `.nav-link` - Navigation links

#### Buttons and Forms
- `.btn` - Button style
- `.form-group` - Form group container
- `.input` - Input field style

#### Animations
- `.animate` - Add fade-in animation
- `.scroll-effect` - Add scroll-based animations

### JavaScript Features

#### Theme Toggle
Add a button with class `theme-toggle` to enable dark mode:
```html
<button class="theme-toggle">Toggle Theme</button>
```

#### Form Validation
Add the `validateForm` function to your form submit event:
```javascript
form.addEventListener('submit', (e) => {
    e.preventDefault();
    if (validateForm(form)) {
        // Process form
    }
});
```

#### Scroll Animations
Add the `animate` class to elements you want to animate on scroll:
```html
<div class="animate">
    This will fade in when scrolled into view
</div>
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Performance

The library includes performance optimizations:
- Debounced functions for expensive operations
- Throttled scroll events
- Efficient DOM queries
- Optimized animations using CSS transforms

## Contributing

Feel free to submit issues and enhancement requests!

## License

MIT License - feel free to use this in your projects!

## Author

Your Name

---

Made with ❤️ for modern web development 
