The Breslauers – Official Website 🎸
Welcome to the official website of The Breslauers, a rockabilly band from Wrocław, Poland. This site showcases their music, videos, merchandise, upcoming events, media coverage, and provides a contact form for reaching out.

Live Site: https://hultgka.github.io/the-breslauers-site/

Project Overview
The site is a static multi-page website built with HTML, CSS, and JavaScript, featuring:

Embedded audio and video players using <audio>, <video>, and <iframe> elements.

Modal popups that autoplay embedded videos on the Music page.

Integration with Bandcamp for merchandise sales on the Merch page.

A simple contact form that submits data via Formspree.

Responsive layout optimized for desktop and mobile devices.

Custom styling with Google Fonts (Orbitron) and Font Awesome icons.

No language translation features included.

Site Structure
the-breslauers-site/
├── index.html # Homepage with band introduction, images, and text content
├── music.html # Music page with modal video popups and embedded media players
├── merch.html # Merchandise page integrating Bandcamp storefront via iframe/embed
├── about.html # About Us page with band bios and photos
├── media.html # Media page featuring press reviews and articles
├── events.html # Upcoming concerts and events listing
├── contact.html # Contact form page
├── assets/ # Fonts, icons, images, and other static resources
└── README.md # This file

Features
Embedded Media:
Audio and video content are embedded directly using native HTML5 elements and iframes from platforms such as YouTube.

Modal Popups:
Videos on the Music page open in modal windows and start playing automatically.

Bandcamp Integration:
Merchandise is showcased on the Merch page using embedded Bandcamp storefronts for easy browsing and purchasing.

Contact Form:
Simple contact form with Name, Email, and Message fields submitting via Formspree, requiring no backend server.

Responsive Design:
Layout adapts across devices with CSS Flexbox and media queries.

Custom Styling:
Dark theme with a futuristic font (Orbitron) and vector icons from Font Awesome.

How to Run Locally
Clone the repository:

git clone https://github.com/hultgka/the-breslauers-site.git
cd the-breslauers-site

Open any .html file directly in your browser, or serve locally with a static server for full functionality:

npx http-server .

Navigate to http://localhost:8080 (or your chosen port).

Deployment
The website is deployed using GitHub Pages:

URL: https://hultgka.github.io/the-breslauers-site/

Source branch: main

Push changes to main to update the live site.

Credits
Developed and maintained by @hultgka

Fonts: Google Fonts - Orbitron (https://fonts.google.com/specimen/Orbitron)

Icons: Font Awesome (https://fontawesome.com)

License
This project is licensed under the MIT License.

Thank you for visiting The Breslauers official website!
