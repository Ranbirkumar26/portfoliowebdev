# portfoliowebdev
This is a portfolio developed by me as my assignment/project for my webdev class in my 4th semester of college.
website link --> https://ranbir26portfolio.netlify.app

RANBIR'S PORTFOLIO WEBSITE

DESCRIPTION
A modern, responsive personal portfolio website built with HTML5, CSS3, and vanilla JavaScript. Features dark/light mode toggle, interactive elements, and showcases achievements in robotics, AI development, and athletics.

FEATURES
- Fully responsive design for all device sizes
- Dark/Light mode toggle with system preference detection
- Interactive hero slideshow with background images
- Typing animation effect for dynamic text
- Project slideshow with navigation controls
- Real-time date and time display
- Contact form with Google Scripts integration
- Smooth scrolling navigation
- CSS Grid and Flexbox layouts
- Font Awesome icon integration

TECHNICAL STACK
Frontend: HTML5, CSS3, JavaScript (ES6+)
Icons: Font Awesome 6.4.2
Fonts: Segoe UI system font stack
Form Handling: Google Apps Script integration
No external frameworks or libraries required

FILE STRUCTURE
index.html - Main portfolio page
Array 11.html - Mathematical puzzle game
pose.html - AI fitness posture correction app
todo.html - Task management application  
dice.html - Interactive dice game
payment.png - Contribution QR code
Ranbir_Kumar_-_Robotics_Engineer.pdf - Resume/CV
passport pic(24-25).png - Profile image
videoplayback.mp4 - Project demonstration video
agriculture.jpg - Hero background image
cricket.webp - Hero background image
gym.jpg - Hero background image
AI .jpg - Hero background image
book.png - About section background
NASA_Mars_Rover.jpg - Project slideshow image
download.jpg - Project slideshow image
download-1.jpg - Project slideshow image
array_game.png - Project thumbnail
arm.png - Project thumbnail
todo_list.png - Project thumbnail
dicegame.png - Project thumbnail

CSS ARCHITECTURE
Uses CSS custom properties (variables) for theming
Organized with:
- Root variables for colors and themes
- Dark mode class toggle system
- Responsive media queries
- CSS Grid for layout sections
- Flexbox for component alignment
- Smooth transitions and animations

JAVASCRIPT FUNCTIONALITY
Theme switching with localStorage persistence
Real-time clock with date/time/day display
Typing animation with multiple profession strings
Hero background slideshow with auto-advance
Project slideshow with manual navigation
Contact form validation and submission
Smooth scrolling navigation
Responsive navigation menu

RESPONSIVE DESIGN
Desktop: Full layout with side navigation
Tablet: Adjusted grid columns and spacing  
Mobile: Stacked layout, collapsed navigation
Breakpoints: 768px and 480px

BROWSER COMPATIBILITY
Modern browsers supporting:
- CSS Custom Properties
- ES6 JavaScript features
- CSS Grid and Flexbox
- HTML5 form validation

SETUP INSTRUCTIONS
1. Download all files to a single directory
2. Ensure all image and video files are in the same folder as index.html
3. Open index.html in a web browser
4. For contact form functionality, configure Google Apps Script endpoint

CONTACT FORM SETUP
The form submits to a Google Apps Script web app
Current endpoint: script.google.com/macros/s/AKfyc...
Includes honeypot spam protection and redirect handling
Form fields: name, email, subject, message

CUSTOMIZATION
Colors: Modify CSS custom properties in :root selector
Content: Update text content in HTML sections
Images: Replace image files with same filenames
Projects: Add new project cards following existing structure
Contact: Update social media links in footer

PERFORMANCE FEATURES
Optimized images and compressed media files
CSS and JavaScript minification ready
Lazy loading compatible structure
Fast loading with minimal external dependencies
Efficient CSS transitions and animations

ACCESSIBILITY FEATURES
Semantic HTML structure
Proper heading hierarchy
Alt text for images
Keyboard navigation support
Color contrast compliance
Screen reader friendly labels

SECURITY FEATURES
Honeypot field for spam prevention
Form validation on client and server side
No inline JavaScript or CSS
Content Security Policy ready
XSS protection through proper encoding

DEPLOYMENT
Can be hosted on any static hosting service:
- GitHub Pages
- Netlify
- Vercel
- Firebase Hosting
- Traditional web hosting

The website is completely self-contained except for Font Awesome icons loaded from CDN. All other assets are local files.
