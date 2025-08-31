# PausePal Website

A meditation accountability buddy website built with HTML, CSS, and JavaScript. This site helps people find meditation partners for consistent practice.

## Features

- Responsive design that works on all devices
- Modern gradient animations and smooth scrolling
- FAQ section with interactive toggles
- Testimonials from real users
- Call-to-action sections for waitlist signup

## Deployment

This website is automatically deployed to GitHub Pages using GitHub Actions. Every push to the main branch will trigger a new deployment.

### To deploy manually:

1. Push your changes to the main branch
2. Go to your repository settings
3. Navigate to "Pages" in the sidebar
4. Select "GitHub Actions" as the source
5. The site will be available at `https://yourusername.github.io/your-repository-name`

## Local Development

To run the website locally, simply open `index.html` in your web browser or use a local server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js (with http-server package)
npx http-server

# Using PHP
php -S localhost:8000
```

## Structure

```
├── index.html          # Main website file
├── .github/
│   └── workflows/
│       └── deploy.yml  # GitHub Pages deployment workflow
└── README.md          # This file
```

## Contact

For questions about the meditation program:
- General inquiries: info@familiaapp.io
- Program questions: adityaaswani1@gmail.com