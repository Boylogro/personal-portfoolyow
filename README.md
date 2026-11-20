cat << 'EOF' > README.md
# Personal Portfolio — Cee Sir B. Rufon

**Live Site:** [https://personal-portfoolyow.pages.dev](https://personal-portfoolyow.pages.dev)  
**GitHub Repository:** [https://github.com/Boylogro/personal-portfoolyow](https://github.com/Boylogro/personal-portfoolyow)

## What I Built
A responsive 3-page personal portfolio website (`index.html`, `projects.html`, `contact.html`) built with semantic HTML5 and an external stylesheet (`styles.css`). It showcases my Computer Engineering background, technical skills, personal interests, featured hardware/software projects, and a direct contact page with a CSS-only dark/light theme toggle and interactive landing screen.

## Deployment Setup
The project is version-controlled with Git and hosted in a public GitHub repository (`personal-portfoolyow`). The repository is connected directly to **Cloudflare Pages** with no build command or output directory required for static HTML/CSS, automatically deploying updates to `personal-portfoolyow.pages.dev` on every `git push`.

## Reflections
- **What I found hardest:** Keeping multi-image project galleries responsive across 360px mobile, 768px tablet, and 1440px desktop viewports without horizontal overflow, as well as resolving duplicate file extensions and `:Zone.Identifier` metadata files when moving assets between Windows and Ubuntu WSL.
- **What I would improve:** In a future version, I would connect the contact form to a serverless backend handler (such as Cloudflare Workers or Formspree) so messages submit directly without opening an external email client, and add a custom `404.html` page.

## AI Usage Acknowledgment
AI tools were used to assist with drafting semantic HTML5 structure, refining responsive CSS Grid/Flexbox layouts, troubleshooting WSL file issues, and verifying W3C validation rules. All personal biography details, project descriptions, and images are my own work.
EOF