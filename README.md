# Argeste - Family Fishing Tours

A multilingual website for a family-run tourism business offering guided fishing tours and outdoor adventures.

![Website Preview](https://github.com/user-attachments/assets/fca7b30d-b43c-4972-a74a-d0ffd1a1b41b)

## Features

### ✨ Multilingual Support
- **Three Languages**: English, Spanish (Español), and Italian (Italiano)
- **Language Persistence**: Selected language is saved in browser localStorage
- **Easy Switching**: One-click language selector in the navigation bar

### 🎣 Tour Showcase
Three fishing tour options beautifully presented:
1. **Half-Day Fishing** - Perfect for beginners and families (4 hours)
2. **Full-Day Adventure** - Complete day experience with lunch (8 hours)
3. **Sunset Fishing** - Romantic golden hour experience (3 hours)

Each tour includes:
- Duration details
- Equipment and amenities
- Clear pricing and booking call-to-action

### 📸 Image Gallery
- Engaging photo gallery showcasing fishing adventures
- Hover effects for interactive experience
- Responsive grid layout

### 👨‍👩‍👧‍👦 Family Story Section
- Highlights three generations of family fishing tradition
- Emphasizes sustainable practices and personalized experiences
- Clear call-to-action to join the adventure

### 📝 Contact & Booking Form
Simple, user-friendly contact form with:
- Name and email (required fields)
- Phone number (optional)
- Tour selection dropdown
- Date picker with validation (future dates only)
- Number of guests
- Additional information textarea
- Form validation with helpful error messages
- Success confirmation messages

### 📱 Responsive Design
- **Desktop**: Full layout with all features
- **Tablet**: Optimized layout for medium screens
- **Mobile**: Mobile-first design with hamburger menu

![Mobile View](https://github.com/user-attachments/assets/072453c5-d5f6-48a1-88cc-56114c2d2622)

### 🎨 Modern UI/UX
- Clean, professional design
- Smooth scrolling navigation
- Interactive hover effects
- Gradient backgrounds with SVG patterns
- Sticky navigation bar
- Scroll-based animations

## Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with CSS Grid and Flexbox
- **JavaScript (ES6+)**: Interactive features and multilingual support
- **No Dependencies**: Pure vanilla JavaScript - no frameworks required

## Getting Started

### Running Locally

1. Clone the repository:
```bash
git clone https://github.com/YarovayaLidia/argeste.git
cd argeste
```

2. Open `index.html` in your browser:
```bash
# Using Python
python3 -m http.server 8080

# Using Node.js
npx http-server

# Or simply open index.html in your browser
```

3. Visit `http://localhost:8080` in your web browser

### File Structure

```
argeste/
├── index.html          # Main HTML file
├── styles.css          # All styling
├── script.js           # Interactive features
├── translations.js     # Multilingual translations
└── README.md          # This file
```

## Customization

### Adding More Languages

Edit `translations.js` and add a new language object:

```javascript
const translations = {
    // ... existing languages
    fr: {
        'nav-home': 'Accueil',
        'nav-tours': 'Circuits',
        // ... add all translation keys
    }
};
```

Then add a language button in `index.html`:
```html
<button class="lang-btn" data-lang="fr">FR</button>
```

### Changing Colors

Edit the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #0077be;      /* Main brand color */
    --secondary-color: #00a8e8;    /* Secondary brand color */
    --accent-color: #ff6b35;       /* Call-to-action color */
    /* ... */
}
```

### Modifying Tour Information

Edit the tour sections in `index.html` and update corresponding translations in `translations.js`.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Features Checklist

- [x] Multilingual support (EN, ES, IT)
- [x] Responsive design (mobile, tablet, desktop)
- [x] Image gallery with hover effects
- [x] Contact form with validation
- [x] Tour showcase sections
- [x] Family story/about section
- [x] Clear calls-to-action throughout
- [x] Smooth scrolling navigation
- [x] Modern, engaging design
- [x] Mobile-friendly hamburger menu

## License

© 2024 Argeste Family Fishing Tours. All rights reserved.

## Contact

For inquiries about the fishing tours:
- **Phone**: +1 (555) 123-4567
- **Email**: info@argeste-tours.com
- **Location**: Marina Bay, Coastal Town
- **Hours**: 7:00 AM - 8:00 PM Daily
