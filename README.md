# KKK-4X4-OFF-ROAD-WORLD-WEBSITE-PART3 
# KKK 4x4 World – Web Development Project

**Student:** Tumelo Mosetlha  
**Course:** Web Development (Introduction) – WEDE5020  
**Module:** 2026 FT DISD0601 RCGPPT Term 2 GR01  
**Institution:** The Independent Institute of Education (IIE)  
**Assessment:** Formative 2 Part 3

---

## 1. Project Overview

KKK 4x4 World is a multi-page static website for a South African off-road and 4x4 accessories business.  
The website allows customers to:

- Browse and view products (winches, bumpers, roof racks, side steps, lights, suspension)
- Learn about the company and its services
- Contact the business or submit technical enquiries
- View business locations via embedded Google Maps

The site uses a consistent dark theme with an orange accent colour (`#ff6f00`) and is fully responsive for desktop, tablet and mobile devices.
## 2. Project Structure

KKK-4x4-World/
├── index.html              # Home / Landing page
├── shop.html               # Product catalogue (20 products)
├── about.html              # About the company
├── contact.html            # Contact details, maps and contact form
├── services.html           # Installation and upgrade services
├── enquiries.html          # Vehicle setup & parts enquiry form
├── css_assets/
│   └── style.css           # External stylesheet (all pages)
├── js_assets/
│   └── script.js           # Shared JavaScript
├── _images/                # Product, logo and hero images
└── README.md               # This documentation file


---

## 3. Pages Description

| Page            | File              | Purpose                                                                 |
|-----------------|-------------------|-------------------------------------------------------------------------|
| Home            | `index.html`      | Hero section with call-to-action leading to the shop                    |
| Shop            | `shop.html`       | Displays 20 product cards with images, descriptions and prices (ZAR)    |
| About           | `about.html`      | Company mission and reasons to choose KKK 4x4 World                     |
| Services        | `services.html`   | Lists installation services (bumpers, suspension, lighting, roof racks) |
| Contact         | `contact.html`    | Business details, two Google Maps embeds, and a contact form            |
| Enquiries       | `enquiries.html`  | Detailed form for custom builds, parts availability and technical queries|

---

## 4. Features Implemented

- External CSS stylesheet linked on every page
- Sticky navigation bar with logo and links
- Mobile hamburger menu (responsive)
- Active page highlighting in the navigation
- Responsive layout using Flexbox and media queries
- Product cards with hover effects
- “Add to Cart” button visual feedback
- Client-side form validation (Contact and Enquiries forms)
- Smooth scrolling for hero buttons
- Google Maps embeds for two business locations
- Consistent branding (orange accent on dark background)
- Footer with social media links and copyright

---

## 5. Technologies Used

- **HTML5** – Semantic structure
- **CSS3** – External stylesheet, Flexbox, media queries, transitions, pseudo-classes
- **JavaScript (Vanilla)** – Menu toggle, form validation, cart feedback, active link highlighting
- **Google Maps Embed API** – Location maps on the Contact page

---

## 6. Responsive Design

Breakpoints used in `style.css`:

| Device   | Max-width | Adjustments                                      |
|----------|-----------|--------------------------------------------------|
| Tablet   | 900px     | Reduced gaps, font sizes and image sizes         |
| Mobile   | 600px     | Hamburger menu, single-column products, stacked images |
| Extra small | 400px  | Further reduction of logo and heading sizes      |

---

## 7. How to Run the Project

1. Clone or download the repository.
2. Ensure the folder structure matches the paths used in the HTML files (`css_assets/`, `js_assets/`, `_images/`).
3. Open `index.html` in a modern web browser, **or** serve the project locally.

# Changelog

All notable changes to the **KKK 4x4 World** website are documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---

## [2.0.0] – 2026-10 – Formative 2 Part 1,2,3 (Responsive + Polish)

### Added
- Full responsive design with three breakpoints:
  - Tablet: `@media (max-width: 900px)`
  - Mobile: `@media (max-width: 600px)`
  - Extra-small phones: `@media (max-width: 400px)`
- Mobile hamburger menu with toggle functionality (JavaScript)
- Smooth scrolling for hero CTA buttons
- Active page highlighting in the navigation bar
- Client-side form validation for Contact and Enquiries pages
- Visual “Added!” feedback + console log for all “Add to Cart” buttons on the Shop page
- Sticky orange navigation bar across all pages
- Consistent dark theme (`#28282B` background) with brand orange (`#ff6f00`) accents
- Product cards with hover lift + border-colour change effects
- Service cards with consistent styling
- Google Maps embeds on the Contact page (two locations)
- Detailed Enquiry form (vehicle setup / parts / technical queries)

### Changed
- External stylesheet (`css_assets/style.css`) now fully linked and used on **every** page
- Typography scaled appropriately for mobile and tablet
- Image gallery and product images now stack and become full-width on mobile
- Navigation collapses into a full-width dropdown menu on mobile
- Footer navigation becomes a vertical list on small screens
- Product grid changes from multi-column to single-column layout on mobile
- Improved spacing, padding, and font sizes across all breakpoints

### Fixed
- Layout and alignment issues that previously appeared on smaller screens
- Navigation links no longer overflow on tablet/mobile
- Hero images and product images now scale correctly without distortion
- Forms remain fully usable and readable on small devices

### Technical Notes
- Pure vanilla JavaScript (no frameworks)
- CSS Reset + consistent base styles applied globally
- Pseudo-classes (`:hover`, `:focus` behaviour) used extensively for interactive elements
- All pages share the same external CSS and JS files for maintainability

---

## [1.1.0] – Formative 2 Part 1 Feedback Implementation

### Added
- Dedicated About page with mission statement and “Why Choose Us” list
- Dedicated Services page with four service cards
- Dedicated Contact page with business details, maps, and contact form
- Dedicated Enquiries page with structured multi-section form
- Shop page product catalogue (20 products) with prices in South African Rand

### Changed
- Improved overall visual consistency (colour scheme, typography, card styling)
- Enhanced footer with social media links bar
- Better semantic HTML structure and accessibility attributes (`aria-label`, etc.)

---

## [1.0.0] – Initial Release (Formative 1 / Early Prototype)

### Added
- Basic multi-page structure (Home, Shop, About, Contact, Services)
- Initial external CSS stylesheet
- Logo and basic navigation
- Hero section on Home page
- Product cards on Shop page
- Simple footer with copyright

---

**Maintainer:** Tumelo Mosetlha  
**Project:** KKK 4x4 World – Web Development (Introduction) WEDE5020 

## References

Google. (n.d.). *Google Maps Embed API*. https://developers.google.com/maps/documentation/embed/get-started

Mozilla Developer Network. (n.d.). *CSS media queries*. MDN Web Docs. https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_media_queries

Mozilla Developer Network. (n.d.). *HTML: HyperText Markup Language*. MDN Web Docs. https://developer.mozilla.org/en-US/docs/Web/HTML

Mozilla Developer Network. (n.d.). *JavaScript*. MDN Web Docs. https://developer.mozilla.org/en-US/docs/Web/JavaScript

W3Schools. (n.d.). *CSS Flexbox*. https://www.w3schools.com/css/css3_flexbox.asp

W3Schools. (n.d.). *HTML Forms*. https://www.w3schools.com/html/html_forms.asp

W3Schools. (n.d.). *Responsive Web Design – Media Queries*. https://www.w3schools.com/css/css_rwd_mediaqueries.asp

World Wide Web Consortium. (n.d.). *HTML Living Standard*. WHATWG. https://html.spec.whatwg.org/



## 2. Project Structure
