### BandSite - Sprint 1 🚀
An up-and-coming band has approached me to design their website! This is the first sprint of a 3-part project. The goal for Sprint 1 is to build a responsive and functional website using the provided mockups, design specs, and assets.

### Table of Contents
Project Overview
Technologies Used
Project Structure
Features
Setup and Installation
Usage
Future Improvements
Credits
### Project Overview 📋
This sprint focused on building a biography page for the band using a mobile-first responsive design.
Key requirements include:

A navigation bar with a home link using the band’s logo.
A hero section displaying a prominent band introduction.
An about section showcasing musician details and images.
A photo gallery section with hover effects.
A footer containing contact information and links.
The website closely follows the provided mockups and design specifications to ensure visual consistency.

Technologies Used 🛠️
HTML5: For semantic structure.
SCSS (Sass): For styling with modular partials, variables, and mixins.
CSS3: For compiled SCSS styling.
Flexbox: For responsive layout and alignment.
BEM Methodology: For clean, reusable class naming.
Visual Studio Code: Development environment.
Git & GitHub: Version control.
Project Structure 📂
python
Copy code
Bandsite/
├── assets/
│   ├── fonts/                # Custom fonts (NunitoSans)
│   ├── images/               # Band images & gallery photos
│   ├── logos/                # Band logo
│   └── icons/                # Social media icons
├── styles/
│   ├── partials/             # SCSS partials
│   │   ├── _variables.scss   # Variables (colors, fonts)
│   │   ├── _mixins.scss      # Media query mixins
│   │   ├── _base.scss        # Base styles
│   │   ├── _header.scss      # Navbar styles
│   │   ├── _hero.scss        # Hero section styles
│   │   ├── _gallery.scss     # Gallery styles
│   │   ├── _footer.scss      # Footer styles
│   ├── bio.scss              # Main SCSS file
│   ├── bio.css               # Compiled CSS file
│   └── bio.css.map           # Source map for debugging
├── index.html                # Main HTML file
└── README.md                 # Project documentation
Features ✨
Responsive Design

Mobile-first approach with breakpoints for tablet (768px) and desktop (1440px).
Flexbox for layout and alignment.
Navigation Bar

Logo as a home link.
Highlighted active menu items.
Hero Section

Large background image with band title.
About Section

Descriptive text and musician images.
Photo Gallery

Images displayed in a responsive grid.
Hover effect: Images are grayscale by default, returning to color on hover.
Footer

Contact information for band agents with mailto links.
Social media links with hover effects.
Setup and Installation ⚙️
Clone the Repository:
Open your terminal and run:

bash
Copy code
git clone https://github.com/your-username/bandsite.git
cd bandsite
Install Live Sass Compiler (If not installed):

Use VS Code extensions to install "Live Sass Compiler."
Compile SCSS:

Run the Live Sass Compiler to generate the bio.css file from bio.scss.
Open the Project:

Open index.html in your browser.
Usage 🌐
Open the index.html file to view the site.
Resize your browser window to test the responsive design.
Interact with:
Navigation links.
Hero and gallery hover effects.
Footer contact links.
Future Improvements 🚀
Add interactivity for additional pages (e.g., Shows page).
Implement smooth scrolling and animations for a better user experience.
Optimize images for faster load times.
Improve accessibility (ARIA roles, semantic HTML).
Credits 👏
Design Specs: Provided as part of the project.
Tools: Visual Studio Code, GitHub, Live Sass Compiler.
Fonts: Nunito Sans (provided in project assets).
