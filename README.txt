Jim's Steak & Spaghetti House Website Redesign
=============================================

Project Overview
This project is a modernized and responsive redesign of the classic website for Jim's Steak & Spaghetti House, a family-owned restaurant established in 1938. The goal of the redesign was to maintain the traditional look and feel of the original website while implementing a clean, responsive, and user-friendly layout using modern HTML5, CSS3, and JavaScript.

## Features
1. Responsive Design:
   - The website uses a responsive layout that adapts seamlessly across desktop, tablet, and mobile devices.
   - Flexbox and media queries ensure the content is well-organized and readable on all screen sizes.

2. Navigation:
   - A modern, consistent navigation bar is included across all pages.
   - A hamburger menu is displayed on mobile devices for easy access to the navigation links.

3. Featured Dishes Sectio:
   - A visually appealing showcase of Jim's signature dishes (Spaghetti, Ribeye Steak, Homemade Pie) is included on the menu page.
   - The featured dishes section is hidden on tablet and mobile devices to optimize layout and load times.

4. Full Menu Page:
   - The menu page includes detailed sections for appetizers, main dishes, sandwiches, salads, dinners, desserts, and to-go items.
   - Each menu section is clearly organized with anchor links for easy navigation.

5. Contact Us Page:
   - A contact form is provided for users to easily get in touch with the restaurant.
   - The form includes input fields for name, email, and message, along with validation for required fields.
   - The page also features contact information and images that showcase the restaurant experience.

6. JavaScript Interactivity:
   - A JavaScript script handles the mobile menu toggle for a smooth user experience on small screens.

## Technologies Used
- **HTML5**: Provides the basic structure and semantic layout of the website.
- **CSS3**: Handles the visual styling, layout, and responsive design.
- **JavaScript**: Adds interactivity, such as the mobile hamburger menu toggle.

## File Structure
JimSpaghetti/
├── index.html
├── menu.html
├── about.html
├── contact.html
├── css/
│   └── styles.css
├── script.js
│  
└── assets/
    ├── images/

File Descriptions
-----------------
- index.html: The homepage with a welcome message, introduction, and embedded YouTube video.
- menu.html: The menu page showcasing popular dishes in a responsive grid layout.
- about.html: The about page with information about the restaurant’s history.
- contact.html: The contact page with a form for user inquiries.
- styles.css: The main CSS file containing all styling, layout rules, and responsive design elements.
- script.js: The JavaScript file handling the toggle functionality for the hamburger menu.
- assets/: Contains images and fonts used in the project.


How to View the Project
-----------------------
1. Open in Browser:
   Navigate to the project folder and open index.html in your preferred web browser.
2. VS Code Live Server:
   Start a live server inside VS Code.

Responsive Design
-----------------
The website uses media queries to adapt its layout for different screen sizes:
- Mobile (0-768px): The navigation bar collapses into a hamburger menu. The content is adjusted for a narrow view, with text and images scaling appropriately.
- Tablet (769px-1024px): The layout becomes more spacious, with increased text size and adjusted margins.
- Desktop (1025px and up): The site uses a full-width layout, maximizing the use of screen space while maintaining readability.

Challenges and Solutions
------------------------
- Challenge: Ensuring the YouTube video and text content were properly centered across all devices.
  Solution: Used Flexbox centering techniques and applied responsive styling with media queries to ensure consistent alignment.

- Challenge: Maintaining the look and feel of the original site while modernizing the codebase.
  Solution: Carefully chose a color scheme and typography that reflect the classic design, while applying modern HTML and CSS practices.

- Challenge: Ensuring the YouTube video and text content were properly centered across all devices.
  Solution: Used Flexbox centering techniques and applied responsive styling with media queries to ensure consistent alignment.

Future Enhancements
-------------------
- SEO Optimization: Add meta tags and improve content for better search engine ranking.
- Interactive Features: Consider adding a photo gallery or customer reviews section.

Credits
-------
- Design and Development: Benjamin Daccione, Jaeden Wells, Antwan Roberts
- Images: Provided by Jim's Steak & Spaghetti House (placeholder images used in development).
- Fonts: Open Sans and Open Sans Condensed from Google Fonts.

License
-------
This project is for educational purposes only and is not intended for commercial use.
