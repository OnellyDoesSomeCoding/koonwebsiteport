# Hyper Teal Markup Language Website

A small static website built with HTML and CSS, ready to deploy on Vercel.

## Important Note

Original repository by: https://github.com/koonratchaphruek1/websiteport
Rehosted on my repository due to Vercel's problem with Microsoft Family security system. You may refer to the original project via this link.

## Project Overview

This repository contains a simple front-end website using the Hyper Teal Markup Language concept.

- `1.html`, `2.html`, `3.html`, `something.html` — example pages for the site
- `style.css` — shared styling for the pages
- `README.md` — this project overview and deployment guide

## Features

- Static HTML pages
- Responsive layout with shared CSS
- Easy to preview locally and deploy on Vercel

## Local Preview

To preview the site locally, simply open any of the HTML files in your browser, or use a local server tool.

Example using VS Code Live Server or a simple Python server:

```powershell
python -m http.server 8000
```

Then open `http://localhost:8000/1.html` in your browser.

## Deploying on Vercel

1. Sign in to Vercel at https://vercel.com
2. Create a new project and connect your GitHub repository or import this folder
3. Set the root directory to the project folder if required
4. Deploy the project

Vercel will automatically detect the static site and publish it.

## Notes

- No build step is required for this project.
- Any HTML file can serve as an entry point depending on your chosen landing page.
- If you want a default home page, rename the desired file to `index.html` or configure Vercel redirects.

## License

This project is released under the MIT License.
