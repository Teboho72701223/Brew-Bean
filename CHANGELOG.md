# Brew & Bean Changelog

This document records the development progress and changes made to the
Brew & Bean website throughout the project.

---

## [1.0.0] - Initial Project Setup

### Added

- Created the Brew & Bean project folder.
- Created the initial HTML project structure.
- Created the images folder.
- Created the main website pages.

### Pages Created

- `index.html`
- `menu.html`
- `about.html`
- `contact.html`

---

## [1.1.0] - Website Navigation

### Added

- Added the main navigation menu.
- Added links between the Home, Menu, About Us and Contact pages.
- Tested internal navigation links.

---

## [1.2.0] - Homepage Development

### Added

- Added Brew & Bean business name.
- Added the website slogan.
- Added a welcome section.
- Added information about Brew & Bean.
- Added coffee information.
- Added bakery information.
- Added a "Why Choose Brew & Bean?" section.
- Added a call-to-action section.
- Added homepage images.

---

## [1.3.0] - Menu Development

### Added

- Created the Brew & Bean Menu page.
- Added Coffee category.
- Added Cold Drinks category.
- Added Tea category.
- Added Bakery category.
- Added Desserts category.
- Added menu item descriptions and prices.
- Added relevant menu images.

---

## [1.4.0] - About Us Development

### Added

- Added information about Brew & Bean.
- Added the company mission.
- Added company values.
- Added information explaining what makes Brew & Bean different.

---

## [1.5.0] - Contact Page Development

### Added

- Added Brew & Bean contact information.
- Added telephone contact details.
- Added email contact details.
- Added location information.
- Added opening hours.
- Added customer enquiry form.
- Added fields for customer name, email, phone number, subject and
  message.

---

## [1.6.0] - Images and Accessibility

### Added

- Added relevant images to the website.
- Added alternative text to images using the `alt` attribute.
- Checked image file paths.
- Tested images to ensure they display correctly.

---

## [1.7.0] - HTML Structure and Documentation

### Added

- Added HTML5 semantic elements.
- Added HTML comments explaining important sections of the code.
- Reviewed website navigation.
- Checked website content.
- Created the README document.
- Created the CHANGELOG document.

---

## [1.8.0] - Testing

### Completed

- Tested all website pages.
- Tested navigation links.
- Checked images.
- Checked page titles.
- Checked contact form fields.
- Checked HTML structure.
- Corrected broken links and file paths where necessary.

---
## [1.9.0] - About Us and Contact Page Styling

### Added

- Styled the About Us page using the site's existing visual language (dark background, #d4a57a accent colour).
- Added a page_banner section to About Us and Contact, replacing the plain unstyled heading with a smaller hero-style banner.
- Added content_section styling for the About Us story, mission and values content, alternating between dark and panel backgrounds.
- Added a values_list chip-style layout for the company values.
- Added cta_buttons styling to the About Us page's closing call-to-action.
- Styled the Contact page using a two-column contact_section layout, with contact_info for business details and contact_form_wrap for the enquiry form.
- Styled all contact form fields (form_row, form_group) to match the site's dark theme, including input and textarea focus states.
- Added a map_section with a map_placeholder box on the Contact page, left empty for a Google Maps (or other) embed to be added later.

### Changed

- Replaced the plain, unstyled <section> elements on About Us and Contact with the styled classes above.
- Kept the header, navigation and footer identical across all pages.

## [2.0.0] - Responsive Design

### Added

- Added responsive breakpoints across style.css for tablets, mobile phones and other smaller devices:
- 1024px - small laptops / large tablets.
- 900px - tablets (portrait).
- 768px - tablets (portrait), including a wrapping navigation bar.
- 600px - large phones.
- 480px - phones.
- 360px - small / older phones.
- Added responsive scaling for the hero slogan, page banner heading and body text at each breakpoint.
- Added responsive behaviour for the navigation menu, wrapping the nav links onto a new line on smaller screens.
- Added responsive stacking for the About Us image/content layout, the Menu and Bakery sections, and the Contact page's info/form layout on smaller screens.
- Added responsive column adjustments for the footer, collapsing from a multi-column layout down to a single column on phones.
- Added a rule so an embedded map (e.g. a Google Maps iframe) placed inside .map_placeholder automatically fills the container at any screen size.

-----

## Current Status

The Brew & Bean website is a functional HTML prototype developed for the Web Development (Introduction) module.

Further improvements may be made as required by the project brief.