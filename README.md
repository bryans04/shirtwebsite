# ComfyTees — T-Shirt Website

ComfyTees — T-Shirt Website

Project Repository: https://github.com/bryans04/shirtwebsite

🚀 Web Collaboration Test (IS117)
This project was built for the IS117 Web Collaboration Test by our team.

## Team
Jonathan (naathanjo)
Bryan (bryans04)

## 🎯 Project Details
**Brand Archetype: The Lover**

Our Choice: We chose "The Lover" archetype (as detailed in our research) to position our brand as premium, elegant, and aspirational.

Customer Segment: Our target audience is consumers who view clothing as a source of identity, confidence, and self-worth.

Implementation: The website's visual identity (elegant fonts, rich colors) and messaging ("Invest in your signature style") are designed to create an intimate and sophisticated emotional connection.

### Persuasion Method: Social Proof (Cialdini)
Our Choice: From our Cialdini research, we focused on "Social Proof" as the most effective principle for a clothing brand.

Implementation: We directly implemented this by building a dedicated `reviews.njk` page. This page is designed to build trust and confidence in new customers by showing them that others have purchased and enjoyed our products.

## 🛠️ Tech Used
- Static Site Generation with Eleventy (11ty)
- Templating with Nunjucks
- Automated CI/CD and Deployment via GitHub Actions
- Git and GitHub for team collaboration

## Run locally
1. Install dependencies

```powershell
npm install
```

2. Build the site

```powershell
npm.cmd run build
```

3. Serve locally (dev server)

```powershell
npm.cmd run serve
```

## Notes & recommendations
- This repository uses Eleventy; `_site/` is generated build output and should not be committed. A `.gitignore` has been added to keep build artifacts and `node_modules/` out of the repository.
- Consider adding a LICENSE (MIT or other) and a small GitHub Actions workflow that builds on push to `main` if not already present.

---
_Edited to keep a single canonical repository URL and add local run instructions._
