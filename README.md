# ازاى افرح - Hugo Static Website

A simple Hugo-based website for displaying the PDF book "ازاى افرح+" page by page.

## Files Structure

```
.
├── config.toml          # Hugo configuration file
├── index.html          # Main HTML page with PDF viewer
├── deploy.yml          # GitHub Pages deployment workflow
├── ازاى افرح+.pdf      # The PDF book to be displayed
└── README.md           # This file
```

## Features

- **PDF Viewer**: Page-by-page navigation with PDF.js
- **Responsive Design**: Works on desktop and mobile devices
- **Arabic Support**: RTL layout and Arabic font optimization
- **Navigation Controls**: Previous/Next page buttons
- **Zoom Controls**: Zoom in/out and reset functionality
- **Keyboard Navigation**: Arrow keys for navigation, +/- for zoom
- **Modern UI**: Beautiful gradient design with smooth animations

## Configuration

Edit `config.toml` to customize:

- `baseURL`: Your GitHub Pages URL
- `pdf_file`: Name of your PDF file
- `site_title`: Website title
- Colors and styling options

## Deployment

1. Push this repository to GitHub
2. Enable GitHub Pages in repository settings
3. The workflow will automatically build and deploy the site

## Local Development

Install Hugo and run:
```bash
hugo server
```

The site will be available at `http://localhost:1313`

## GitHub Pages Settings

- **Source**: Deploy from a branch
- **Branch**: `gh-pages` (or `main` depending on your workflow)
- **Folder**: `/root`

## URL

Once deployed, your site will be available at:
`https://portfoliohubs.github.io/sanwy2/`
