# ☕ KOPPEE - Responsive Multi-Page Coffee Shop Web Application

A fully responsive, modern 7-page web application layout designed for an artisanal coffee shop. Built from scratch to demonstrate advanced front-end architecture, clean semantic HTML5, modular **SCSS/Sass** styling, and dynamic user interactions using JavaScript and jQuery.

## 🚀 Live Demo & Screenshots
> **Note to Recruiters & Technical Reviewers:** This repository serves as a **Front-End UI/UX and SCSS Architecture Showcase**. Some text sections intentionally retain *Lorem Ipsum* placeholder copy to emphasize layout structure, typography hierarchy, and visual design patterns over content management.

## ✨ Key Technical Features

- **Multi-Page Architecture:** Includes 7 interconnected, fully designed pages (`Home`, `About`, `Service`, `Menu`, `Reservation`, `Testimonials`, and `Contact`).
- **Modular SCSS Architecture:** Advanced usage of SCSS preprocessor features, including custom variables, mixins, responsive grid breakpoints, and modular utility classes for scalable styling.
- **Responsive Web Design:** Fluid layouts built on Bootstrap Grid, ensuring seamless adaptability across desktop, tablet, and mobile viewports.
- **Interactive Table Reservation System:** Integrated with `Tempus Dominus` and `Moment.js` to provide customized date and time pickers for real-time table booking.
- **Dynamic Client Testimonials:** Smooth touch-enabled and responsive sliders implemented using `Owl Carousel 2`.
- **Asynchronous Form Validation:** Custom JavaScript and jQuery validation (`jqBootstrapValidation`) connected to an AJAX backend handler (`contact.php`) for seamless message submission without page reloads.

## 🛠️ Built With

- **Markup & Styling:** HTML5, CSS3, SCSS / Sass, Bootstrap 4.5
- **Scripting & Logic:** JavaScript (ES6+), jQuery 3.4.1
- **UI Libraries & Plugins:** 
  - [Owl Carousel 2](https://owlcarousel2.github.io/OwlCarousel2/) (Touch sliders)
  - [Tempus Dominus](https://tempusdominus.github.io/bootstrap-4/) (Date & Time picker)
  - [Font Awesome 5](https://fontawesome.com/) (UI Icons)

## 📁 Directory Structure

```text
├── css/                 # Compiled minified stylesheets
├── img/                 # Optimized UI assets and brand images
├── js/                  # Main interactive scripts (menu, scroll, sliders)
├── lib/                 # Third-party vendor libraries (OwlCarousel, Waypoints, etc.)
├── mail/                # AJAX validation scripts and PHP form handlers
├── scss/                # Modular SCSS source files (Mixins, Variables, Utilities)
├── index.html           # Main landing page
├── about.html           # Story and vision page
├── service.html         # Services overview
├── menu.html            # Dynamic pricing and beverage menu
├── reservation.html     # Interactive table booking form
├── testimonial.html     # Client review slider page
└── contact.html         # Contact form and location details
