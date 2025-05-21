# IFSTEM 2025 Conference Website

## Overview

This repository contains the official website for the "Innovations and Frontiers in Science, Technology Engineering and Materials: Bridging Science and Sustainability (IFSTEM 2025)" conference. The website is designed to provide information about the conference, showcase speakers, display the schedule, facilitate registration, and highlight sponsors.

![IFSTEM 2025 Conference Website](screenshot.png)

## Features

- **Responsive Design**: Fully responsive layout that works on all devices
- **Interactive Elements**: Animated UI components and interactive particles
- **Countdown Timer**: Live countdown to the conference date
- **Speaker Showcase**: Profiles of keynote speakers and presenters
- **Schedule Display**: Detailed conference agenda with session information
- **Registration Form**: User-friendly registration system
- **Venue Information**: Maps and details about the conference location
- **Sponsors Section**: Showcase of conference sponsors and partners
- **FAQ Section**: Answers to common questions
- **Gallery**: Photos from previous conferences
- **Sustainability Theme**: Green-focused design with falling leaves animation

## Technologies Used

- HTML5
- CSS3 (with custom animations and transitions)
- JavaScript (ES6+)
- [AOS](https://michalsnik.github.io/aos/) - Animate On Scroll library
- [particles.js](https://vincentgarreau.com/particles.js/) - Particle animation library

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/ifstem-2025-conference.git
   cd ifstem-2025-conference

2. Open the website locally:
  ```shellscript
  # If you have Python installed
  python -m http.server
  # OR if you have Node.js installed
  npx serve
  ```

3. Visit `http://localhost:8000` (or the port shown in your terminal) in your browser.

## File Structure

```plaintext
ifstem-2025-conference/
├── index.html              # Main HTML file
├── styles.css              # Main stylesheet
├── script.js               # JavaScript functionality
├── assets/                 # Static assets directory
│   ├── images/             # Images used throughout the site
│   ├── fonts/              # Custom fonts
│   └── icons/              # Icons and favicons
├── lib/                    # Third-party libraries
│   ├── aos/                # Animate On Scroll library
│   └── particles/          # Particles.js library
└── README.md               # This file
```

## Customization

### Changing Conference Details

1. Open `index.html` and update the conference information in the relevant sections.
2. To change the countdown date, modify the `conferenceDate` variable in `script.js`.


### Modifying the Theme

1. The color scheme can be adjusted in `styles.css` by changing the CSS variables in the `:root` selector.
2. To modify the falling leaves effect, adjust the particles configuration in the `particlesJS` function in `script.js`.


### Adding/Removing Sections

1. Each section is contained within a `<section>` tag with a unique ID.
2. To add a new section, copy an existing section structure and modify its content.
3. Remember to update the navigation links in the header if you add or remove sections.




## Browser Compatibility

The website is compatible with:

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)
- Mobile browsers (iOS Safari, Android Chrome)


## Accessibility

The website follows WCAG 2.1 guidelines for accessibility:

- Semantic HTML structure
- Proper contrast ratios
- Alt text for images
- Keyboard navigation support
- ARIA attributes where necessary


## Performance Optimization

- Images are optimized for web
- CSS and JavaScript are minified in production
- Lazy loading is implemented for images
- Animations are optimized for performance


## Contributing

1. Fork the repository
2. Create your feature branch: `git checkout -b feature/amazing-feature`
3. Commit your changes: `git commit -m 'Add some amazing feature'`
4. Push to the branch: `git push origin feature/amazing-feature`
5. Open a Pull Request


## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Credits

- Particle animation: [particles.js](https://vincentgarreau.com/particles.js/)
- Scroll animations: [AOS](https://michalsnik.github.io/aos/)
- Icons: [Font Awesome](https://fontawesome.com/)
- Fonts: [Google Fonts](https://fonts.google.com/)


## Contact

For any questions or inquiries about the website, please contact:

- Email: [conference@ifstem2025.org](mailto:conference@ifstem2025.org)
- Twitter: [@IFSTEM2025](https://twitter.com/IFSTEM2025)
