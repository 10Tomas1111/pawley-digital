# Pawley Digital Website

A modern, responsive static website for pawleydigital.com.

## Domain Configuration

The website is configured with a WWW-first approach:
- Primary domain: https://www.pawleydigital.com
- Apex domain (pawleydigital.com) redirects to WWW
- SSL: Enabled via GitHub Pages
- DNS: Managed through Namecheap

## Structure

```
pawley-digital/
├── index.html
├── css/
│   └── styles.css
└── README.md
```

## Features

- Clean, modern design
- Responsive layout
- Smooth scrolling navigation
- Interactive hover effects
- Google Fonts integration (Inter)

## Local Development

To view the website locally, simply open `index.html` in your web browser or run a local server.

## Deployment

The site is hosted on GitHub Pages with the following configuration:
1. Repository settings:
   - Branch: main
   - Custom domain: www.pawleydigital.com
   - HTTPS: Enforced

2. DNS Configuration:
   - WWW: CNAME record pointing to GitHub Pages
   - Apex: URL redirect to www.pawleydigital.com
