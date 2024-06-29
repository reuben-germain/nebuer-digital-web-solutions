# Nebuer Digital Web Solutions

Nebuer Digital Web Solutions is a modern, responsive, and accessible website template designed for a digital solutions consultancy. This template includes essential sections for showcasing services, portfolio, and company information, along with a contact form for potential clients to reach out.

## HTML Structure

### Header Section
- Contains navigation links to different sections of the website.
- The ```<header>``` tag contains the navigation bar.
- ```<nav class="navbar">``` defines the navigation container.
- ```<a href="#" class="nav-branding">NDWS</a>``` is the branding link.
- ```<ul class="nav-menu">``` contains the navigation links to different sections of the website.
- The ```.hamburger``` div is for the mobile menu icon.

### Hero Section
- Features a prominent call-to-action button to engage visitors.
- The ```<section id="hero">``` contains a hero banner with a brief description and a call-to-action button.

### Services Section
- Showcases the different services offered by the consultancy.
- This section details the various services offered by the company, each within a ```<div class="service-item">```.

### Portfolio Section
- Displays completed projects to demonstate
- This section showcases previous projects with images and titles.

### About Section
- Introduces the company and provides background information.
- This section provides information about the company and its mission.

### Contact Section
- Includes a form for potential clients to send inquiries.
- This section includes a contact form for visitors to reach out to the company.

### Footer Section
- Contains copyright information and any additional links or information.

## CSS Structure

### Global Styles
- The ```*``` selector targets all elements, resetting their padding, margin, and box-sizing to ensure consistent styling across different browsers.
- The ```body``` selector sets a default line-height and text color for the entire document.

### Header Section
- ```header``` sets the background color for the header section.
- ```li``` removes bullet points from list items.
- ```a``` removes underlines from links and sets their default color to white.
- ```.navbar``` styles the navigation bar with flexbox for layout, padding, and minimum height.
- ```.nav-menu``` styles the navigation menu with flexbox for horizontal layout and spacing between items.
- ```.nav-branding``` styles the branding text.
- ```.nav-link``` applies a transition effect to navigation links.
- ```.nav-link:hover``` changes the color of links on hover.
- ```.hamburger``` styles the hamburger menu icon for smaller screens, initially hidden.
- ```.bar``` styles the bars of the hamburger menu icon.

### Responsive Styles For Navbar
- The ```@media``` rule applies styles for screens with a maximum width of 768px.
- Displays the ```.hamburger``` menu icon on smaller screens.
- Styles the active state of the hamburger icon, transforming the bars into an 'X' shape.
- ```.nav-menu``` changes to a fixed position, taking up the full width of the screen, with vertical layout and centered text.
- ```.nav-menu.active``` positions the menu on the screen when activated.

### Hero Section
- ```#hero``` styles the hero section with a background color, text color, padding, and centered text.
- ```.container``` sets a width, centers the content, and hides overflow.
- ```.cta-button``` styles call-to-action buttons with background color, padding, and border-radius.
- ```.cta-button:hover``` changes the background and text color on hover, with a transition effect.

### Services and Portfolio Sections
- ```h2``` centers section headings and adds bottom margin.
- ```.section-padding``` adds padding to sections.
- ```.services-grid``` and ```.portfolio-grid``` use CSS Grid to layout items, with responsive columns.
- ```.service-item``` and ```.portfolio-item``` style individual items with background color, padding, and border-radius.
- ```.portfolio-item img``` styles images within portfolio items to be fully responsive.

### Footer Section
- ```footer``` styles the footer with background color, text color, centered text, and padding.

### Form Styles
- ```.form``` styles forms with CSS Grid for layout.
- ```.form-group``` styles individual form groups with flexbox for vertical alignment.
- ```.form-group label``` adds bottom margin to labels.
- ```.form-group input``` and ```.form-group textarea``` style form inputs with padding, border, and border-radius.
- ```button.cta-button``` styles submit buttons within forms, including a background color and padding.