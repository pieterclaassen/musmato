# Musmato — proposed corporate website

Static, responsive website for Musmato. This repository contains an initial **proposal** for a company-led positioning, moving away from an individual ZZP presentation and introducing Riskonami as a featured product.

## View

Open `index.html` in a browser for a local preview. There is no build step.

## Publish using GitHub Pages

1. Open repository **Settings → Pages**.
2. Under **Build and deployment → Source**, choose **GitHub Actions**.
3. The workflow at `.github/workflows/pages.yml` deploys the site on pushes to `main`.
4. Site URL is expected to be `https://pieterclaassen.github.io/musmato/` after deployment succeeds. Verify the deployment in **Actions**.

**Do not add a custom domain or change Musmato DNS until this proposal is approved.**

## Required before production approval

- Verify the contact email `info@musmato.com` or replace it with the correct address.
- Confirm product brand and domain: **Riskonami** versus **Riskonomy**. This proposal uses Riskonami.
- Verify corporate registration details before adding KvK number, address or legal language.
- Review all service and product claims against currently available capabilities.
- Confirm privacy and legal information before collecting enquiry data. This version uses an email link and no form analytics or tracking.
- Review GitHub Pages deployment and any domain-specific changes before launch.

## Files

- `index.html`: Complete static website (responsive styling and tiny navigation script).
- `.github/workflows/pages.yml`: GitHub Pages deployment using GitHub Actions.
