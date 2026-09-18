# Kwa-Mzilikazi Website Project

## Student Information
**Student Name:** Sphesihle Qwabe
**Course:** Diploma in IT Management
**Project:** Website Development POE
**Current Phase:** Part 2 – Designing the Visuals: CSS Styling and Responsive Design


## 1. Project Overview
Kwa-Mzilikazi is a fictional home-style eatery located at 43 Eloff Street in the Johannesburg CBD. The business serves affordable, authentic South African meals, meat bones, and refreshments for dine-in and takeaway customers. 

This project builds a professional, user-friendly website for the eatery. While Part 1 focused on establishing the HTML foundation, Part 2 focuses on advanced CSS styling, implementing a Zulu heritage-inspired design, and ensuring the website is fully responsive across all devices.


## 2. Website Goals and Objectives
The primary goals of the Kwa-Mzilikazi website are to:
* **Inform:** Provide clear, accessible information about the menu, location, and business history.
* **Engage:** Create a visually appealing, culturally inspired design that attracts and retains customers.
* **Convert:** Make it easy for users to view the menu and submit enquiries for takeaway or bulk orders.
* **Accessibility:** Ensure the website functions perfectly and looks professional on desktop, tablet, and mobile screens.


## 3. Key Features and Functionality
* **Consistent Navigation:** A global header and footer are used across all five pages to ensure easy navigation.
* **Zulu Heritage Design:** The site features a premium colour palette (terracotta, deep blue, and gold) paired with elegant typography to reflect the brand's identity.
* **Responsive Layouts:** The website uses CSS Grid and Flexbox to adapt seamlessly from multi-column desktop layouts to single-column mobile layouts.
* **Responsive Images:** The `<picture>` element and `srcset` attributes are used to optimise image loading for different screen sizes.
* **Search Functionality:** A search bar is integrated into the header to help users quickly find menu items.
* **Semantic HTML:** The site is built using proper HTML5 tags (`<header>`, `<nav>`, `<main>`, `<section>`, and `<footer>`) for better structure and SEO.

---

## 4. Sitemap
1. **Home** (`index.html`) – Features a hero section, business introduction, and a summary of offerings.
2. **About Us** (`about.html`) – Details the organisation's story, mission, vision, and team.
3. **Menu** (`menu.html`) – Displays food categories, prices, and high-quality images of the dishes.
4. **Enquire** (`enquiry.html`) – Contains a form for customers to make enquiries about takeaway, catering, or bulk orders.
5. **Contact** (`contact.html`) – Provides the physical address, trading hours, an embedded map, and a contact form.


## 5. Part 2 Implementation Details (CSS & Responsive Design)
To meet the Part 2 learning outcomes, the following design and development techniques were applied:

**External Stylesheet & Base Styles**
A single external `style.css` file was created and linked to all HTML pages. This ensures consistency across the website and takes advantage of the "cascading" nature of CSS to style elements efficiently. A global CSS reset was applied to ensure consistent styling across different web browsers, and default styles (font family, base font size, and colour scheme) were established using CSS variables.

**Typography & Visual Styles**
Google Fonts (`Playfair Display` for headings and `Montserrat` for body text) were imported to create a harmonious typography scale. Properties like `font-weight`, `line-height`, and `letter-spacing` were used to improve readability. Visual depth was added using `box-shadow`, `border-radius`, and decorative CSS beadwork borders. Interactive elements were enhanced using pseudo-classes like `:hover`, `:focus`, and `:active`.

**Layout Structure**
The website layout was structured using modern CSS techniques. **CSS Grid** (utilising `grid-template-areas`) was used to create a clean, complex header layout, while **Flexbox** (using `display: flex`, `justify-content`, and `align-items`) was used to align the navigation menu and centre content within cards. 

**Responsive Design & Relative Units**
Relative units like `rem` were used for font sizes and spacing, while `%` and `max-width` were used for element widths to ensure the site scales smoothly. Key breakpoints were identified, and media queries (e.g., `@media (max-width: 768px)`) were implemented to switch the multi-column grid to a single-column layout on smaller screens. The navigation menu stacks vertically on mobile devices to improve the user experience.

## 6. Changelog
This section tracks all changes made to the project, including detailed corrections based on Part 1 feedback and new developments for Part 2.

**Version 1.0 – Initial Part 1 Setup**
* Created the initial Kwa-Mzilikazi website project structure.
* Developed the five required HTML pages (Home, About Us, Menu, Enquire, Contact).
* Implemented the main navigation menu and homepage hero section.
* Organised files into HTML, CSS, JavaScript, and image folders.

**Version 1.1 – Part 1 Feedback Corrections**
* **Accessibility Improvements:** Added missing and descriptive `alt` attributes to all `<img>` tags to ensure the site is accessible to screen readers.
* **Heading Hierarchy:** Fixed inconsistent heading levels by changing `<h4>` tags to `<h3>` in the About Us section to maintain a logical document outline.
* **Form Accessibility:** Improved form usability by ensuring all `<input>` fields have correctly linked `<label>` tags with matching `for` and `id` attributes.
* **Code Readability:** Corrected minor HTML indentation issues and added descriptive comments to explain complex sections of the code.

**Version 1.2 – Part 2 CSS Foundation**
* Created and linked the external `style.css` file to all HTML pages.
* Implemented CSS variables to establish a Zulu heritage colour palette and typography scales.
* Applied a global CSS reset to ensure cross-browser consistency.

**Version 1.3 – Part 2 Layout & Visual Styling**
* Applied `grid-template-areas` to the header for a complex, clean layout, and CSS Grid to the menu section.
* Added visual styling including `box-shadow`, `border-radius`, and decorative CSS beadwork borders to the header and footer.
* Implemented interactive hover and focus states for navigation links and buttons.

**Version 1.4 – Part 2 Responsive Design**
* Added media queries for mobile and tablet breakpoints (max-width: 768px).
* Modified the CSS Grid to switch to a single-column layout on smaller screens.
* Adjusted font sizes using `rem` and made the search bar full-width using `%` for better mobile usability.

**Version 1.5 – Responsive Images**
* Updated standard `<img>` tags to use the `<picture>` element with `srcset` and `sizes` attributes. This optimises image loading by serving appropriate image resolutions based on the user's screen size.


## 8. References

Canva, 2026. Colour palette generator*. Available at: <https://www.canva.com/colors/color-palettes/>  [Accessed: 19 September 2026].

freeCodeCamp, 2026. Learn CSS*. Available at: <https://www.freecodecamp.org/news/learn-css/>  [Accessed: 19 September 2026].

Google, 2026. Google fonts*. Available at: <https://fonts.google.com/> (Accessed: 19 September 2026).

Google, 2026. *Responsive web design basics*. Available at: <https://web.dev/learn/design/> [Accessed: 19 September 2026].

MDN Web Docs, 2026. *CSS flexbox*. Available at: <https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_flexible_box_layout>  [Accessed: 19 September 2026].

MDN Web Docs, 2026. *CSS grid layout*. Available at: <https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_grid_layout> [Accessed: 19 September 2026].


*© 2026 Sphesihle Qwabe. All rights reserved.*
