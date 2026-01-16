DARK FAN PAGE - Static Website Project

PROJECT OVERVIEW
This is a complete static website fan page dedicated to the Netflix series "Dark". 
Built with semantic HTML and CSS only - no JavaScript required. The site features 
five pages covering the series' characters, episodes, timeline, and sci-fi elements.

FOLDER STRUCTURE
breaking-dark-fanpage/
├─ index.html              (Home page with hero section)
├─ characters.html         (Character directory grouped by family)
├─ episodes.html           (All episodes across three seasons)
├─ timeline.html           (Series timeline and summary table)
├─ scifi-elements.html     (Sci-Fi concepts explained)
├─ css/
│  └─ style.css           (All styling for the site)
├─ images/
│  ├─ background.jpg      (Blurred background image)
│  ├─ default.jpg         (Placeholder image)
│  ├─ characters/         (Character images)
│  │  ├─ jonas_child.jpg
│  │  ├─ jonas_adult.jpg
│  │  └─ [other character images]
│  ├─ s1/                 (Season 1 episode images)
│  ├─ s2/                 (Season 2 episode images)
│  └─ s3/                 (Season 3 episode images)
└─ README.txt             (This file)

HOW TO RUN
1. Extract the breaking-dark-fanpage.zip file
2. Open index.html in any web browser by double-clicking it
3. Navigate between pages using the top navigation menu

REQUIRED IMAGES
The following image files should be placed in the images/ folder:

Background:
- background.jpg (main background image, used throughout the site)
- default.jpg (placeholder for missing images)

Character Images (images/characters/):
- jonas_child.jpg
- jonas_adult.jpg
- [Additional character images as available]

Episode Images:
- images/s1/*.jpg (Season 1 episodes: s1e01.jpg through s1e10.jpg)
- images/s2/*.jpg (Season 2 episodes: s2e01.jpg through s2e08.jpg)
- images/s3/*.jpg (Season 3 episodes: s3e01.jpg through s3e08.jpg)

NOTE: If an image file is missing, the site will use images/default.jpg as a placeholder.

CSS STYLING
- Internal CSS: The index.html page contains an internal <style> block only for hero section styling.
  This allows for inline styling of the hero layout and appearance.
- External CSS: All other styling is managed in css/style.css, including:
  - Navigation bar
  - Card designs
  - Character grid layouts
  - Episode rows
  - Timeline cards
  - Sci-Fi element cards
  - Table styling
  - Responsive design for mobile and tablet

DESIGN FEATURES
- Dark theme with muted green (#2ecc40) accent color
- Yellow (#d4af37) accent for highlights
- Blurred background image using CSS filter
- Rounded black cards with subtle green border glow
- Responsive design that adapts to mobile, tablet, and desktop screens
- Semantic HTML with proper use of nav, header, main, section, article, figure, and footer
- Lazy loading for all images to improve performance
- Accessible design with proper alt text and ARIA labels

TECHNOLOGY USED
- HTML5 (semantic markup)
- CSS3 (flexbox, grid, gradients, filters)
- No JavaScript
- No external libraries or frameworks
- No build tools required

VIVA SCRIPT (2-3 minutes)
This Dark fan page project demonstrates a complete understanding of web fundamentals using 
only HTML and CSS. The project is organized into five thematic pages: Home, Characters, Episodes, 
Timeline, and Sci-Fi Elements. The styling approach separates concerns by using internal CSS 
only in index.html for the hero section styling, while all other pages rely on css/style.css 
for consistent design. Characters are intelligently grouped by family (Kahnwald, Nielsen, Doppler, 
Tiedemann) using semantic HTML and CSS grid, which improves user navigation and understanding of 
the show's complex relationships. The timeline page uses a card-based layout alternating between 
left and right text/image placement to visually represent the progression of events, with a 
comprehensive summary table at the end. The sci-fi elements page explains key concepts like the 
God Particle, bootstrap paradox, and time machine using the same card layout. The entire project 
uses CSS custom properties for theming, lazy loading for image optimization, semantic HTML elements 
(nav, header, main, section, article, figure, footer), and a mobile-first responsive design 
approach using media queries.

CREDITS & ATTRIBUTION
[Add your name and credits here]

- Dark is a Netflix series created by Baran bo Odar and Jantje Friese
- This is a fan-made website for educational purposes
- Images should be sourced from official Dark Netflix promotional materials or fan art
- Background image credit: [Add source]

DEPLOYMENT (Optional)
To deploy this static site to Vercel:
1. Push the project to GitHub
2. Import the repository into Vercel
3. The site will deploy automatically

For other static hosting (Netlify, GitHub Pages, etc.), simply upload the breaking-dark-fanpage 
folder as-is. No build process is required.

BROWSER COMPATIBILITY
- Modern browsers (Chrome, Firefox, Safari, Edge)
- Mobile browsers (iOS Safari, Chrome Android)
- Minimum: CSS Grid and Flexbox support

NOTES FOR STUDENT
- Replace all placeholder images (images/default.jpg) with actual Dark series images
- Update the credits section in README.txt with your name and image sources
- Test the site on multiple screen sizes using browser DevTools
- Ensure all navigation links work correctly between pages
- Verify that all images load properly (check browser console for errors)
