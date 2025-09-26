# WEDE5020_POE
Part 1 submission
.
.
.
/*---Part2 changelog---*/
Part 1 Feedback & Initial Code fixes
- Missing Assets: Sourced and added all previously missing images and video files to the /Images directory.
- Content Completeness: Filled in placeholder text and added missing contextual information to sections across the website, including the "Products and Services" and "News Update" pages, ensuring the site provides sufficient detail.
- Code Quality: Ensured all file paths (e.g., href and src attributes) are relative to maintain portability.
- HTML Semantics: Verified header and footer structures are semantically correct across all pages.

Responsive Design & Mobile Implementation (Part 2)
- Critical Responsiveness Fix: Added the essential <meta name="viewport" content="width=device-width, initial-scale=1.0"> tag to the <head> of all HTML pages to ensure correct scaling on mobile devices.
- CSS-Only Navigation: Implemented the full CSS-only hamburger menu logic (#nav-check and <label for="nav-check">) across all pages.
- Mobile Legibility: Updated the mobile media query (@media (max-width: 768px)) to set .nav-item { color: white; } for increased legibility on the dark mobile menu background.
- Eliminated Horizontal Scrolling: Modified fixed pixel widths on content images (e.g., in about.html) to use fluid scaling (max-width: 400px; width: 100%; height: auto;) to prevent layout overflow on small screens.
- Responsive Images: Applied the srcset and sizes attributes to the main site logo (Logo.jpeg) on all pages to optimize image delivery based on device screen size and resolution.
- CSS Clean-up: Removed redundant/duplicate .nav-item declarations within the responsive media query block.

Responsive desing evidence
Desktop View (Above 768px)


Tablet View (768px Breakpoint)
The navigation has collapsed into the hamburger icon, and content is optimized for a single column.


Mobile View (767px Width and less)
for example: 360px width
The layout is fully optimized for a vertical viewport, and the hamburger menu is visible.
