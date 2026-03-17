# GEMINI.md - Pirate Monkey Studios GitHub Pages

This repository serves as the static host for `piratemonkeystudios.com` using GitHub Pages. Its primary purpose appears to be hosting domain verification and app-related configuration files.

## Project Overview
A minimal static site repository for Pirate Monkey Studios, primarily used for hosting the `app-ads.txt` file for mobile application advertising verification and setting up a custom domain via GitHub Pages.

## Key Files
- `index.html`: A minimal landing page for the root domain.
- `CNAME`: Maps the GitHub Pages site to the custom domain `piratemonkeystudios.com`.
- `app-ads.txt`: Contains Authorized Digital Sellers (ADS) information for mobile apps, used by ad networks like Google AdMob and MoPub to verify the publisher's identity.

## Usage and Deployment
This project is hosted on GitHub Pages. Any changes pushed to the main branch are automatically deployed.
- **Updating Ads:** Modify `app-ads.txt` to add or update authorized sellers.
- **Domain Management:** The `CNAME` file ensures that GitHub Pages serves the content from the `piratemonkeystudios.com` domain.
- **Web Content:** The `index.html` file can be expanded to provide a full website if needed.
