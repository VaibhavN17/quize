# Spring Microservices Quiz Site

Live URL: https://vaibhavn17.github.io/quize/

## Publish This Site Using Git

This repository is already connected to GitHub:
- Remote: https://github.com/VaibhavN17/quize.git
- Branch: main

The project now includes a GitHub Actions workflow at .github/workflows/deploy-pages.yml that deploys the site to GitHub Pages on every push to main.

## One-time GitHub setup

1. Open your repository on GitHub.
2. Go to Settings -> Pages.
3. Under Build and deployment, set Source to GitHub Actions.

## Publish updates

Run these commands from the project folder:

```powershell
git add .
git commit -m "Publish latest site updates"
git push origin main
```

After push, GitHub Actions deploys automatically. The updated site is available at:
https://vaibhavn17.github.io/quize/
