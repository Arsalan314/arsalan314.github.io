# Q Industries Landing Page

A clean, modern landing page for Q Industries featuring a showcase for the motor sQills app.

## Features

- **Clean, Modern Design**: Professional appearance with smooth animations
- **Responsive Layout**: Works perfectly on desktop, tablet, and mobile devices
- **Smooth Scrolling**: Navigation links smoothly scroll to sections
- **Interactive Elements**: Hover effects and scroll animations
- **Product Showcase**: Dedicated card for the motor sQills app

## Files Structure

```
Landing Page/
├── index.html          # Main HTML structure
├── styles.css          # CSS styling and responsive design
├── script.js           # JavaScript for interactions
└── README.md           # This file
```

## How to Use

1. **Open the landing page**: Simply open `index.html` in your web browser
2. **Add the screenshot**: Replace the placeholder in the motor sQills card with your actual screenshot
3. **Customize content**: Edit the text content in `index.html` to match your needs

## Adding the motor sQills Screenshot

To add your screenshot to the motor sQills card:

1. Place your screenshot image in the same folder as `index.html`
2. Open `index.html` and find the product card section (around line 40-50)
3. Replace the placeholder div with an actual image:

```html
<!-- Replace this: -->
<div class="placeholder-image">
    <span class="placeholder-text">motor sQills Screenshot</span>
    <span class="placeholder-subtext">Screenshot will be added here</span>
</div>

<!-- With this: -->
<img src="your-screenshot.jpg" alt="motor sQills App Screenshot" style="width: 100%; height: 100%; object-fit: cover;">
```

## Customization Options

### Colors
The main brand color is blue (`#2563eb`). You can change this in `styles.css` by updating:
- `.logo` color
- `.nav-link:hover` color
- `.cta-button` color
- `.product-link` color
- `.contact-button` background-color

### Fonts
The page uses Inter font from Google Fonts. You can change this by:
1. Updating the Google Fonts link in `index.html`
2. Changing the `font-family` in `styles.css`

### Content
Edit the text content in `index.html` to match your company's information:
- Hero section title and subtitle
- About section description
- Contact information
- Footer text

## Browser Compatibility

This landing page works in all modern browsers including:
- Chrome
- Firefox
- Safari
- Edge

## Performance

The page is optimized for fast loading with:
- Minimal external dependencies (only Google Fonts)
- Optimized CSS and JavaScript
- Responsive images
- Smooth animations

## License

This landing page template is free to use and modify for your projects. 