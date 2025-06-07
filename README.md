# Accessible Design Co

This project features a responsive, accessible website for Accessible Design Co.

## Features

- Responsive navigation menu with a hamburger icon for mobile devices
- Hamburger menu is pure CSS (no JavaScript required)
- Navigation menu slides in from the right on mobile and can be toggled open/closed
- "Get in Touch" button and hero section content are aligned to the left for improved layout and accessibility
- Accessible color contrast and semantic HTML

## Usage

1. Open `index.html` in your browser.
2. On mobile or small screens, click the hamburger icon (top right) to open or close the navigation menu.
3. The "Get in Touch" button is positioned on the left side of the hero section.

## Customization

- To change the hero background, update the `background` property in `.hero` in `css/style.css`.
- To adjust navigation links, edit the `<ul class="nav-links">` in `index.html`.

## Accessibility

- Uses semantic HTML elements and ARIA attributes.
- High color contrast for readability.
- Keyboard and screen reader friendly navigation.

---

# Accessible Design Co.

## Overview
Accessible Design Co. is a fictitious company dedicated to creating inclusive and accessible web designs. This project showcases a responsive multi-section webpage that highlights the company's mission, services, and contact information. The webpage is built with semantic HTML, ensuring that it is accessible to all users, including those using assistive technologies.

## Project Structure
The project consists of the following files:

- **index.html**: Contains the semantic HTML structure for the webpage, including sections for the header, main content (hero, about us, services, and contact form), and footer. The navigation bar is implemented with appropriate ARIA roles for accessibility.
  
- **css/style.css**: Contains the CSS styles for the webpage. It implements responsive design using Flexbox for the navigation bar and CSS Grid for the services section. Media queries are included to adjust the layout and font sizes for different screen sizes. The styles ensure sufficient color contrast and include focus states for interactive elements.

- **js/main.js**: Intended for any JavaScript functionality needed for the webpage, such as form validation or dynamic content updates. It can also include event listeners for interactive elements.

## Setup Instructions
1. Clone the repository to your local machine.
2. Open the `index.html` file in your preferred web browser to view the webpage.
3. For development, you can modify the CSS in `css/style.css` and the JavaScript in `js/main.js` as needed.

## Design and Development Notes
- The design prioritizes accessibility, ensuring that all interactive elements are keyboard navigable and screen reader friendly.
- The layout is responsive, adapting to various screen sizes using Flexbox and CSS Grid.
- Color contrast has been carefully considered to enhance readability and accessibility for users with visual impairments.
- Focus states are implemented for all interactive elements to improve navigation for keyboard users.

## Future Improvements
- Implement additional JavaScript functionality for enhanced user interaction.
- Expand the services section with more detailed descriptions and visuals.
- Consider adding a blog or resources section to provide valuable content to users.