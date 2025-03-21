# Pawley Digital Website

A modern, responsive static website for pawleydigital.com.

## Domain Configuration

The website is configured with a WWW-first approach:
- Primary domain: https://www.pawleydigital.com
- Apex domain (pawleydigital.com) redirects to WWW
- SSL: Enabled via GitHub Pages
- DNS: Managed through Namecheap

## Navigation

The site uses hash-based routing for smooth section navigation:
- Home: https://www.pawleydigital.com/
- About: https://www.pawleydigital.com/#about
- Work: https://www.pawleydigital.com/#work
- Contact: https://www.pawleydigital.com/#contact

All paths work with both WWW and apex domains, with proper redirect handling.

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
- Hash-based section routing
- Preserved paths in domain redirects

## Local Development

To view the website locally, simply open `index.html` in your web browser or run a local server.

## Deployment

The site is hosted on GitHub Pages with the following configuration:
1. Repository settings:
   - Branch: main
   - Custom domain: www.pawleydigital.com
   - HTTPS: Enforced
   - Force HTTPS: Enabled

2. DNS Configuration:
   - WWW: CNAME record pointing to GitHub Pages
   - Apex: URL redirect to www.pawleydigital.com
   - Path preservation: Enabled in redirects

3. Testing Status:
   - WWW domain: ✓ Verified with HTTPS
   - Section navigation: ✓ Working
   - Path handling: ✓ Tested
   - SSL certificates: ✓ Valid
