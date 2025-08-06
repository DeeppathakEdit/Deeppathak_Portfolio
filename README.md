Deep Pathak - Video Editor Portfolio
Overview
This is a personal portfolio website for Deep Pathak, a professional video editor specializing in long-form documentaries and dynamic social media clips. The website showcases Deep's skills, projects, and contact information, designed with a modern, responsive layout and engaging animations.
Features

Responsive Design: Adapts seamlessly to various screen sizes, from mobile to desktop.
Theme Toggle: Switch between dark and light themes for better accessibility and user preference.
Smooth Animations:
Scroll-based animations for sections, cards, and images using Intersection Observer.
Hover effects on navigation links, project links, and contact icons with animated underlines and scaling.


Sections:
Home: Introduction with a profile image and tagline.
About: Brief bio and a personal image.
Skills: Grid of skills with descriptions (e.g., Video Editing, Motion Graphics, Color Grading).
Projects: Showcase of notable projects with links to external content.
Contact: Social media and email links with animated icons.


Tech Stack:
HTML5, CSS3, and JavaScript.
Font Awesome for icons.
External image hosting via GitHub.



Setup Instructions
To run or modify this portfolio locally, follow these steps:

Clone the Repository:
git clone https://github.com/DeeppathakEdit/Deeppathak_Portfolio.git
cd Deeppathak_Portfolio


Open the Project:

No build process is required as this is a static website.
Open index.html in a web browser to view the portfolio.
Alternatively, use a local server for a better development experience:npx http-server

Then navigate to http://localhost:8080 in your browser.


Dependencies:

No local dependencies are required.
The website uses CDN-hosted Font Awesome for icons (https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css).
Images are hosted externally on GitHub (https://raw.githubusercontent.com/DeeppathakEdit/Deeppathak_Portfolio/main/images/).


Customization:

Update content in index.html (e.g., text, links, or images).
Modify styles in the <style> section of index.html to adjust colors, animations, or layouts.
Ensure any new images are hosted online (e.g., via GitHub or another service) and update the URLs in the HTML.



File Structure
Deeppathak_Portfolio/
├── index.html        # Main portfolio webpage
├── images/           # Folder for images (hosted on GitHub)
│   ├── logologo.webp # Hero section profile image
│   ├── deeppathak.jpeg # About section image
└── README.md         # This file

Usage

Navigation: Use the sticky header to jump to sections (Home, About, Skills, Projects, Contact).
Theme Toggle: Click the moon/sun icon in the header to switch between light and dark themes.
Interactivity: Scroll to see elements fade in and slide up. Hover over links and icons for animated effects.
Projects: Click project links to visit external content (currently set to YouTube placeholders).
Contact: Use the email or social media links to connect with Deep Pathak.

Notes

The website is optimized for performance with minimal external dependencies.
Animations are powered by CSS transitions and JavaScript's Intersection Observer for scroll effects.
Ensure external image URLs remain valid. If hosting images elsewhere, update the src attributes in index.html.
The theme toggle persists the chosen theme via JavaScript and CSS custom properties.

Contributing
This is a personal portfolio, but suggestions or improvements are welcome! Please submit issues or pull requests to the repository, or contact Deep Pathak directly via the links in the Contact section.
License
This project is for personal use by Deep Pathak. Unauthorized commercial use or distribution is prohibited. For permissions, please contact Deep
