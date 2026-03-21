# Modern Website

A beautiful, responsive website built with modern web technologies including HTML5, CSS (Tailwind), and JavaScript.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI**: Clean and professional design using Tailwind CSS
- **Interactive Elements**: Smooth scrolling, animations, and hover effects
- **Contact Form**: Functional contact form with validation
- **Navigation**: Sticky navigation with mobile menu support
- **Accessibility**: Keyboard navigation and focus management
- **Performance**: Optimized for fast loading and smooth interactions

## Project Structure

```
windsurf-project/
├── index.html          # Main HTML file
├── src/
│   ├── input.css       # Tailwind CSS input file
│   └── main.js         # JavaScript functionality
├── dist/
│   └── output.css      # Compiled CSS
├── package.json        # Project dependencies
├── tailwind.config.js  # Tailwind configuration
└── README.md          # This file
```

## Getting Started

### Option 1: Simple Python Server (Recommended)

1. Open your terminal/command prompt
2. Navigate to the project directory:
   ```bash
   cd windsurf-project
   ```
3. Start a local server:
   ```bash
   python -m http.server 8080
   ```
4. Open your browser and go to: `http://localhost:8080`

### Option 2: Using Node.js (if available)

1. Install dependencies:
   ```bash
   npm install
   ```
2. Build CSS:
   ```bash
   npm run build
   ```
3. Start development server:
   ```bash
   npm run serve
   ```

### Option 3: Direct File Access

You can also simply open `index.html` directly in your browser, but some features may not work correctly due to browser security restrictions.

## Technologies Used

- **HTML5**: Semantic markup and modern HTML features
- **Tailwind CSS**: Utility-first CSS framework for styling
- **Vanilla JavaScript**: Modern ES6+ JavaScript for interactivity
- **Google Fonts**: Inter font family for typography
- **SVG Icons**: Inline SVG icons for scalability

## Sections

The website includes the following sections:

1. **Navigation**: Sticky header with smooth scroll navigation
2. **Hero**: Eye-catching landing section with call-to-action
3. **About**: Information about the company/services
4. **Services**: Overview of offered services
5. **Contact**: Contact form with validation
6. **Footer**: Additional links and social media

## Customization

### Colors
The primary color scheme can be modified in `tailwind.config.js`:

```javascript
theme: {
  extend: {
    colors: {
      primary: {
        50: '#eff6ff',
        500: '#3b82f6',
        600: '#2563eb',
        700: '#1d4ed8',
      }
    }
  }
}
```

### Fonts
Font family is defined in `src/input.css` and can be changed by modifying the Google Fonts import.

### Content
All text content is in `index.html` and can be easily customized.

## Browser Support

This website supports all modern browsers:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Contributing

Feel free to modify and improve the website. If you add new features or fix bugs, please update this README accordingly.

## License

This project is open source and available under the MIT License.
