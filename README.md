# Ocean Breeze Spa Website

## Project Overview
This is a professional, responsive, and visually consistent website for Ocean Breeze Spa. The site features six main pages with spa-themed design, interactive elements, and smooth animations.

---

## Pages

1. **Home (index.html)**
   - Hero section with parallax background and fade-in animations.
   - Quick navigation to services, gallery, and contact.
     Interactive Elements

Hero Section

Hover effects on hero background: slight zoom and brightness increase.

Hover effects on middle/top images: scale and shadow.

Hero CTA button (BOOK) — hover: slight lift + shadow.

Navigation Bar

Links: hover color change + slight text shadow.

Popup Message

Delayed popup (4s after load) “Book your relaxation today!” — fades in/out.

Animations

Entire page fade-in on load.

Hero text fade-in sequentially (tagline, description, button).
   
   <img width="1907" height="870" alt="image" src="https://github.com/user-attachments/assets/1957ef8f-f07c-49c2-9148-3a94af59aa73" />

2. **About Us (about.html)**
   - Floating overlay header.
   - Image box with hover zoom/tilt.
   - Embedded YouTube video with hover animation.
   - Interactive Elements

Background Image

Parallax scroll effect (background-attachment: fixed).

Hover scale effect (transform: scale(1.005)).

About Header

Floating header with fade-in.

Content

About-us image: hover scale, rotate, shadow, filter (brightness).

Video iframe: hover scale, slight rotation, shadow.

Back Button

Hover effect: background color change, slight scale + rotation, shadow.

Modal Popup

Triggered by clicking about-us image or video: overlay modal with fade-in animation.

Animations

Body fade-in on load.

Header fade-in.

Image and video fade-in sequentially.

Back button fade-in.

Footer fade-in.

   <img width="1916" height="867" alt="image" src="https://github.com/user-attachments/assets/f70d41d7-e8c9-4a9e-8cf6-414a8d6201e7" />

   <img width="1917" height="868" alt="image" src="https://github.com/user-attachments/assets/8c85607f-59e5-40d8-9192-2f870428e567" />

3. **Services (services.html)**
   - Service cards with fade-in and hover effects.
   - Clean layout highlighting spa offerings.
   - Search bar
   - Interactive Elements

Service Cards / Images

Hover scale + shadow effect.

Navigation Bar

Same hover effects as homepage.

Animations

Page fade-in.

Service headings/images fade-in sequentially.

CTA Buttons

Hover lift + shadow.

<img width="1908" height="713" alt="image" src="https://github.com/user-attachments/assets/60f2e260-5eac-4001-baa8-9a8ac5ca9267" />


4. **Gallery (gallery.html)**
   - Image grid with hover zoom.
   - Modal/lightbox for larger image preview.
   Interactive Elements

Carousel

Horizontal scroll carousel.

Next/Prev arrows: hover scale + background color change.

Carousel images: hover scale + shadow.

Image Titles

Slight hover emphasis.

Navigation Bar

Hover effects as above.

Animations

Page fade-in.

Carousel slide animation.

Responsive adjustments for smaller screens.

  <img width="1914" height="869" alt="image" src="https://github.com/user-attachments/assets/87a54917-7d35-4de5-9a58-44674d04423f" />


5. **Contact (contact.html)**
   - Contact form with styled inputs, hover effects, and fade-in animation.
   - Submission handling with success message.
   - Interactive Elements

Contact Form

Hover/focus effects on input fields.

Submit Button

Hover lift + shadow.

Interactive Map (if included)

Zoom/scroll interaction.

Animations

Page fade-in.

Form elements fade-in sequentially.

Mailto Links

Proper line breaks for Gmail/Outlook.
  
   <img width="1909" height="870" alt="image" src="https://github.com/user-attachments/assets/176e0cf4-8fa3-40bd-b417-c5eade7bd3b4" />

6. **Enquiry (enquiry.html)**
   - Enquiry form with input validation.
   - Success message on submission.
   - Modal popup for interactive message.
Interactive Elements

Form Fields

Hover/focus effects: border color change or shadow.

Submit Button

Hover lift + shadow.

Validation (if implemented)

Inline validation error messages with fade-in.

Animations

Page fade-in.

Form fields sequential fade-in
  
     <img width="1914" height="869" alt="image" src="https://github.com/user-attachments/assets/3908a4dd-4815-4fef-9000-7065dd211b90" />


---

## Features

- **Responsive Design**: Fully mobile-optimized (≤768px).
- **Navigation Bar**: Fixed top, gradient background, hover effects, active page highlight.
- **Animations**: Fade-in for content, zoom and shadow effects on hover.
- **Forms**: Contact and enquiry forms with validation and success messages.
- **Interactive Modals**: Opens on image/video clicks (About Us, Gallery, Enquiry).
- **SEO Optimized**: Meta tags for description, keywords, author, robots.
- **Accessibility**: Alt tags for images and semantic HTML tags used.

---

## Folder Structure
ocean-breeze-spa/
│
├── index.html
├── about.html
├── services.html
├── gallery.html
├── contact.html
├── enquiry.html
├── images/
│ ├── Backgroundabout.png
│ ├── Aboutus.png
│ └── gallery/ (images)
├── css/
│ └── style.css
├── js/
│ └── modal.js
│ └── validation.js
└── README.md


---

## Usage

1. Open any HTML page in a modern web browser.
2. Navigate between pages using the header menu.
3. Interact with images and videos to trigger modals.
4. Use back buttons to return to the homepage.
5. Submit forms on `contact.html` or `enquiry.html` for demonstration.

## Authors

- Carmen Jecole

## Notes

- Animations are CSS-driven.
- JavaScript handles modal popups and form interactions.
- All pages share consistent spa theme: colors, gradients, fonts, and layout.
