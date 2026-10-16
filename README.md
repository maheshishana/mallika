# Mahesh Ishana — personal creator website

A responsive, static personal-brand website for GitHub Pages. No backend, database, third-party form service, build step, or secret keys are required.

## Files
- `index.html` — page structure, SEO metadata, and content
- `styles.css` — responsive layout, typography, visual design, and reduced-motion support
- `script.js` — mobile navigation, current year, and lightweight scroll reveals
- `favicon.svg` — simple monogram icon
- `CNAME` — custom domain `maheshishana.in`

## Publish with GitHub Pages
1. Create a new GitHub repository. For a personal site, a repository named `<your-github-username>.github.io` is simplest. A normal repository can also be published through Pages.
2. Upload all files from this folder to the repository root and commit them.
3. Open **Settings → Pages** and choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
4. In **Settings → Pages → Custom domain**, enter `maheshishana.in` and save. Verify ownership of the domain in GitHub if possible.
5. At your domain registrar's DNS panel, configure the apex domain using GitHub Pages' current official A/AAAA records, and add `www` as a CNAME pointing directly to `<your-github-username>.github.io`. Do not replace existing DNS records until you know what they are used for.
6. Wait for DNS and certificate provisioning, then enable **Enforce HTTPS** in Settings → Pages when available.

Official instructions: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site

## Before publishing
- Confirm that `https://maheshishana.in/` is the intended canonical domain and that you control its DNS.
- Confirm the Instagram profile URL in `index.html` and the project descriptions.
- Replace the YouTube search links with the exact channel/video URLs when ready.
- The `The Loan Trap` project text is written as a portfolio summary; update the description and status to match the published video precisely.

## Security notes
This is a static website, so it does not store visitor data or credentials and has no server-side login or database. GitHub Pages supports HTTPS; use the official custom-domain setup and enable HTTPS. Do not add API keys, private contact information, or secrets to a public repository. GitHub Pages does not let you set arbitrary server response headers, so this starter does not claim to configure server-level security headers.
