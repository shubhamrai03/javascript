# Corporate Connect Series - Bootstrap 5 Design

This project recreates the "Corporate Connect Series" design using Bootstrap 5 with a responsive image gallery layout.

## Features

- **Responsive Grid Layout**: Uses Bootstrap 5's grid system for perfect responsiveness
- **Image Gallery**: 6 corporate event images arranged in a 3x2 grid on desktop
- **Hover Effects**: Smooth hover animations with scale and shadow effects
- **Lightbox Feature**: Click on any image to view it in a larger modal
- **Mobile Optimized**: Responsive design that adapts to all screen sizes
- **Loading Animations**: Staggered fade-in animations for images
- **Professional Styling**: Clean, modern design matching corporate aesthetics

## File Structure

```
/workspace/
├── index.html          # Main HTML file
├── style.css          # Custom CSS styles
└── README.md          # This file
```

## Responsive Breakpoints

- **Desktop (lg)**: 3 columns (col-lg-4)
- **Tablet (md)**: 2 columns (col-md-6)  
- **Mobile (sm/xs)**: 1 column (col-12)

## Technologies Used

- Bootstrap 5.3.2 (CSS Framework)
- Vanilla JavaScript (Lightbox functionality)
- CSS3 (Custom animations and styling)
- HTML5 (Semantic markup)

## Usage

1. Open `index.html` in a web browser
2. The page will load with the Corporate Connect Series gallery
3. Click on any image to view it in lightbox mode
4. Resize the browser window to test responsive behavior

## Customization

### Adding New Images
Replace the Unsplash URLs in `index.html` with your own image URLs:

```html
<img src="your-image-url.jpg" alt="Your Alt Text" class="img-fluid rounded shadow-sm">
```

### Modifying Colors
Edit the CSS variables in `style.css`:

```css
/* Header color */
h2 { color: #2c3e50; }

/* Background color */
body { background-color: #f8f9fa; }
```

### Adjusting Grid Layout
Modify Bootstrap classes in HTML:
- `col-lg-4` for desktop columns
- `col-md-6` for tablet columns  
- `col-12` for mobile columns

## Browser Compatibility

- Chrome 60+
- Firefox 60+
- Safari 12+
- Edge 79+

## Performance Features

- Optimized image loading with fade-in animations
- CSS transforms for smooth hover effects
- Efficient grid system using CSS Flexbox
- Minimal JavaScript footprint