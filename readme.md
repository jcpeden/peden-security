# Locksmith Site

Static website for Peden Security, converted from WordPress to static HTML and hosted on GitHub Pages.

## Hosting Setup

- Hosted on GitHub Pages
- Domain configured via GitHub Pages settings
- SSL certificate automatically provisioned by GitHub

## DNS Configuration

A Records:

```
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153
```

## Local Development

1. Clone the repository
2. Serve locally using any static file server
   ```bash
   # Example using Python
   python -m http.server 8000
   ```

## Deployment

Site automatically deploys when changes are pushed to the `master` branch.

## Site Structure

- `index.html` - Homepage
- `css/` - Stylesheets
- `js/` - JavaScript files
- `images/` - Site images and assets
