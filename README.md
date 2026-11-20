# Personal Portfolio — Cee Sir B. Rufon

**Live Site:** [https://personal-portfoolyow.pages.dev](https://personal-portfoolyow.pages.dev)  
**GitHub Repository:** [https://github.com/Boylogro/personal-portfoolyow](https://github.com/Boylogro/personal-portfoolyow)

## Overview
A responsive multi-page personal portfolio website built with semantic HTML5 and external CSS3 for my 4th-year Computer Engineering coursework at the University of the Immaculate Conception (UIC).

### Pages Included
- **Home (`index.html`):** Interactive space-themed Peeking Earth landing intro with audio playback, hero bio, portrait photo, and core engineering skills.
- **Projects (`projects.html`):** Multi-image showcase featuring my Computer Engineering thesis (*Automated Library Management System*), a medical imaging computer vision model (*Nodule Detection Using Machine Learning*), and a boarding house rental app concept (*RentHub*).
- **Contact (`contact.html`):** Direct university email, phone, GitHub profile links, and a responsive contact form.

## Features & Technical Highlights
- **Pure Semantic HTML5 & External CSS3:** Structured with `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<figure>`, and `<footer>` with zero inline styles.
- **Responsive Design:** Tested across mobile (`360px`), tablet (`768px`), and desktop (`1440px`) viewports using CSS Grid and Flexbox without horizontal overflow.
- **Extra Credit Enhancements:** CSS-only Light/Dark theme toggle (`:checked` + custom properties), keyframe entrance animations, and an interactive Peeking Earth landing screen.

## Reflection
- **What worked well:** Structuring layouts with CSS Grid and custom CSS variables made it straightforward to support both light and dark themes and adapt multi-image project galleries cleanly from desktop down to 360px mobile screens.
- **Challenges & fixes:** Managing Windows-to-WSL file transfers introduced hidden `:Zone.Identifier` files and duplicate extensions (such as `.mp3.mp3`), which I resolved directly in the Ubuntu terminal using `ls` and `mv` before pushing to GitHub.

## AI Usage Acknowledgment
AI assistance was used to help structure semantic HTML5 templates, refine responsive CSS Grid/Flexbox rules, debug WSL file path issues, and review W3C validation compliance. All project descriptions, screenshots, and personal details are my own.