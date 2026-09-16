# Certified PAI — website

Static site: `index.html`, `css/style.css`, `js/script.js`. No build step.

## Publish with GitHub Pages

1. Create a new GitHub repository, e.g. `certifiedpai`.
2. Upload all the files in this folder, keeping the same structure:
   ```
   certifiedpai/
   ├── index.html
   ├── css/style.css
   ├── js/script.js
   └── README.md
   ```
3. In the repo, go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Set branch to `main` and folder to `/ (root)`, then **Save**.
6. GitHub will publish the site at:
   `https://YOUR-GITHUB-USERNAME.github.io/certifiedpai/`

## Using your certifiedpai.com domain

In the same **Settings → Pages** screen, add `certifiedpai.com` under **Custom domain**, then update your domain's DNS records to point to GitHub Pages (GitHub shows the exact records to add once you enter the domain).

## What to edit before launch

- Replace the placeholder email (`hello@certifiedpai.com`) and any copy in `index.html` with your real contact details and service descriptions.
- The EOS Dashboard button/link in the header, resources section, and footer all point to:
  `https://certfiedpai.ctonew.app/login`
