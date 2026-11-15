# BalaGaneshKumar D | Portfolio

Personal portfolio of **BalaGaneshKumar D**, Cloud & Infrastructure Automation Support Engineer.

**Live site:** https://balaganeshkumar.github.io

## About this site

A single-page portfolio covering my experience in cloud automation and infrastructure support (AWS, Azure, GCP, CI/CD, Chef, Jenkins, Git), my skills, and the projects I have built on my own.

- Light and dark theme
- Interactive hero illustration drawn as inline SVG: each tech tile jumps to the Skills section and the AI board jumps to Projects
- Sections: Home, About, Case Study, Skills, Experience, Projects, Contact
- Built with AI assistance, as a single `index.html` file with no frameworks

## Bot protection

My contact details and resume are protected from automated scraping:

- My email address, phone number and resume are **not** in the page code. They load only after a [Cloudflare Turnstile](https://www.cloudflare.com/application-services/products/turnstile/) check, served by a small Cloudflare Worker.
- If the resume download is unavailable, visitors can send a request to access it.
- `robots.txt` allows major search engines and the Claude and Gemini crawlers, and asks all other crawlers to stay out. Only well-behaved crawlers follow it, so the Turnstile check is the real protection.

## Repository contents

| File | Purpose |
| --- | --- |
| `index.html` | The whole portfolio: page, styles, scripts and images |
| `robots.txt` | Crawler rules |
| `README.md` | This file |

## Notes

- Best viewed on a desktop or laptop. Mobile and tablet layouts are still being worked on.
- Logos and product names (AWS, Microsoft Azure, Google Cloud, Jenkins, Chef, Git, HCLTech) are trademarks of their respective owners, used for identification only. No affiliation or endorsement is implied.

&copy; 2026 BalaGaneshKumar D. All rights reserved.
