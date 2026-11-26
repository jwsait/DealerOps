# DealerOps System Design website

This repository is prepared for GitHub Pages.

## Publish
1. Upload all files and folders in this package to the root of a GitHub repository.
2. In GitHub, open **Settings > Pages**.
3. Under **Build and deployment**, choose **GitHub Actions**.
4. Push or commit to the `main` branch. The included workflow publishes the site.

## Required external assets
The main HTML is included as `index.html`, with its formatting, inline CSS, and inline SVG diagrams preserved.
To make every image and download work, add the original files at these exact paths:

- `design/assets/dealerops-c4-container-diagram.svg`
- `requirements/backup-data/01-southgate-dashboard.png`
- `requirements/backup-data/02-lakeshore-dms.png`
- `requirements/backup-data/03-platform-admin-dealerships.png`
- `project-plan/poster/DealerOps-Poster.pdf`
- `project-plan/prototype/DealerOps-Prototype.html`

The site can publish without them, but those specific images/download links will be unavailable until the files are added.
