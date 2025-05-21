# cVent Webinar Invitation Template

![cVent Logo](assets/images/logos/cvent-logo.svg)

## Overview

This project is a responsive, modern webinar invitation template for cVent events. It features a clean, professional design with subtle animations and dark mode functionality, ensuring a great user experience across all devices.

## Features

- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Dark Mode Toggle**: User-friendly theme switching with persistent preferences
- **Modern Animations**: Subtle animations enhance the user experience without being distracting
- **Accessibility**: Designed with accessibility in mind, including proper contrast ratios and semantic HTML
- **Brand Consistency**: Maintains cVent's brand identity throughout the design

## Project Structure

```
cvent/
├── assets/
│   └── images/
│       └── logos/
│           ├── cvent-logo.svg
│           ├── header_logo_stroke.png
│           ├── wgyc-facebook-logo-gray.png
│           ├── wgyc-instagram-logo-gray.png
│           ├── wgyc-linkedin-logo-gray.png
│           ├── wgyc-x-twitter-gray.png
│           └── wgyc-youtube-logo-gray.png
├── pages/
│   └── webinar-header.css
├── index.html
└── README.md
```

## Technologies Used

- HTML5
- CSS3 (with CSS Variables for theming)
- JavaScript (Vanilla JS for animations and dark mode functionality)
- Intersection Observer API for lazy-loading animations

## Features

### Responsive Design

The template is fully responsive and adapts to different screen sizes:
- Desktop: Full layout with optimized spacing
- Tablet: Adjusted layout with preserved functionality
- Mobile: Streamlined design for smaller screens

### Dark Mode

The template includes a toggle for switching between light and dark modes:
- User preferences are saved in localStorage
- System preferences are detected and applied by default
- Smooth transitions between modes

### Animations

Subtle animations enhance the user experience:
- Fade-in effects for content sections
- Hover effects for interactive elements
- Decorative elements with subtle movements
- Intersection Observer for performance-optimized animations

## Getting Started

1. Clone the repository:
   ```
   git clone https://github.com/Xenonesis/cvent.git
   ```

2. Open `index.html` in your browser to view the template.

3. Customize the content in `index.html` to match your webinar details.

4. Modify styles in `pages/webinar-header.css` if needed.

## Customization

### Changing Colors

The template uses CSS variables for easy color customization. Edit the `:root` section in the CSS to change the color scheme:

```css
:root {
  --bg-color: #f5f5f5;
  --container-bg: white;
  --text-color: #333;
  --heading-color: #00507a;
  /* Additional color variables */
}
```

### Updating Content

Edit the HTML content in `index.html` to update:
- Webinar title and date
- Description and bullet points
- Call-to-action buttons
- Footer information

## Browser Support

The template is compatible with all modern browsers:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This project is proprietary and owned by cVent.

## Contact

For questions or support, please contact [itisaddy7@gmail.com].
