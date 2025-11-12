Baryp-Kel Airlines ✈️🇰🇿
Overview
Welcome to the world of Baryp-Kel Airlines—a modern front-end demonstration website designed to simulate an airline that prioritizes safety, comfort, and affordability. This project showcases advanced front-end development capabilities, including responsive design, complex interactive components using jQuery and JavaScript, and a simulation of user authentication.

The Baryp-Kel website is created to connect people and cities, focusing particularly on regional flights across Kazakhstan.

Pages Included
The website consists of the following pages:

1. Home Page (index.html)
The main page featuring a call to action and a booking form.

A dynamic greeting based on the time of day (time-based-greeting).

Interactive city search with an autocomplete function (city-autocomplete).

A modal window for contacts that opens via the 'Buy Ticket' button.

2. About Page (about.html)
Detailed information about the airline, its goals, and achievements.

Interactive elements:

Expandable sections (Accordion) with animated counters (count-up) to display achievements (e.g., '120 destinations').

A scroll progress bar for the page (scroll-progress-bar).

A tool for searching and highlighting keywords on the page.

A 'Copy to clipboard' button for founder contacts.

A section displaying the logos of partner airlines.

3. Services Page (services.html)
The services section, showcasing the main cities in Kazakhstan served by the airline.

City Gallery: A carousel/slider with city images and thumbnail previews.

Flight Classes: Cards describing Economy, Comfort, and Business classes.

Class Filter: A search field to filter flight classes by name (class-filter-input).

Modal window with detailed information about the flight class.

4. Authentication Pages (login.html, register.html, profile.html)
Login/Register: Demonstration of sign-in and registration with client-side form validation (validateRegistrationForm, handleLoginForm in script.js) and use of localStorage/sessionStorage to simulate user data.

Profile: A personal user page, accessible only after 'logging in'.

5. Contact Page (contact.html)
A contact form page utilizing Bootstrap 5 styles and additional styling for responsiveness and dark theme.

Simulation of asynchronous data submission (submitDataAsync in script.js).

Features
Responsive Layout: All pages are optimized for viewing on mobile devices, using flexible layouts (@media queries in style.css).

Theme Toggle: Quick switching between light and dark themes, with the preference saved in localStorage.

Authentication (Demo Auth): Full registration/login/logout cycle using client-side storage (localStorage, sessionStorage).

Form Validation: Includes field checks, password comparison, and a 'shake-animation' for invalid input.

Notifications (Toasts): Uses pop-up notifications for feedback (successful login, errors).

Animations: Animated counters (count-up) and a loading spinner during registration.

Autocomplete: Input assistance function for entering cities on the main page.

Tech Stack
HTML5: Semantic and structured markup.

CSS3: Used for styling and responsive design.

JavaScript (ES6): For main logic and interactive features.

jQuery 3.7.1: For DOM manipulation and event handling.

Bootstrap 5 CDN: Used on the contact.html page for basic form and grid styles.

No Backend: All forms are demo-only and do not require server-side data processing.

How to Use
Download or clone the project folder.

Ensure the folder structure and files are maintained (especially the image/ and .js/.css files).

Open the index.html file in any modern browser.

Use the navigation bar to move between sections.

Test the registration (register.html) and login (login.html) functionality using any data, as it is saved locally in the browser.

Credits
Project: Baryp-Kel Airlines

Authors: Danial & Nurgaly

Year: 2025

Technologies: HTML5, CSS3, JavaScript, jQuery.

License
This project is created exclusively for educational and demonstration purposes.
