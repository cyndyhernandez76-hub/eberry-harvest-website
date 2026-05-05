# EBerry Harvest Company — Website

Single-page website for EBerry Harvest Company LLC, a family-owned farm labor contractor headquartered in LaBelle, Florida.

**Live site:** _(set after GitHub Pages is enabled)_

## About

EBerry Harvest Company has been providing farm labor solutions for over 40 years across six states: Florida, Georgia, Tennessee, Virginia, Indiana, and New York.

Services include:
- Prep operations & irrigation
- Field harvest
- Post-harvest sorting & grading
- Packing & repacking
- Hauling & transport (DOT-compliant)
- H-2A compliance & petition management
- Worker housing
- Payroll services (via FieldPay Solutions)

## Structure

This is a single HTML file (`index.html`) with all CSS and JavaScript inline. No build step, no dependencies — just open it in a browser.

Fonts are loaded from Google Fonts:
- **Cormorant Garamond** (display headings)
- **Outfit** (body text)

## Deployment to GitHub Pages

1. Create a new GitHub repository (suggested name: `eberry-harvest-website` or `eberryharvest`)
2. Upload `index.html` and this `README.md` to the repo
3. Go to **Settings → Pages**
4. Under **Source**, select **Deploy from a branch**
5. Choose `main` branch and `/ (root)` folder
6. Click **Save**
7. Wait 1–2 minutes — your site will be live at `https://[username].github.io/[repo-name]/`

## Connecting a Custom Domain (eberryharvest.com)

Once GoDaddy access is restored:

1. In GoDaddy DNS settings for eberryharvest.com, add these records:
   - `A` record pointing `@` to `185.199.108.153`
   - `A` record pointing `@` to `185.199.109.153`
   - `A` record pointing `@` to `185.199.110.153`
   - `A` record pointing `@` to `185.199.111.153`
   - `CNAME` record pointing `www` to `[username].github.io`
2. In the GitHub repo, go to **Settings → Pages**
3. Under **Custom domain**, enter `eberryharvest.com` and save
4. Check **Enforce HTTPS** once the certificate provisions (can take up to 24 hours)

## Updating Content

To make changes to the site:
1. Edit `index.html` directly in GitHub (pencil icon) or clone the repo locally
2. Commit and push changes
3. GitHub Pages will redeploy automatically within 1–2 minutes

## Customization Notes

The current site uses placeholder values for:
- **Phone number** — search for `(Phone number)` in `index.html`
- **Email** — currently `info@eberryharvest.com`
- **Logo** — currently a stylized "E" in a gradient circle. To use the real EBerry logo, replace the `.logo-mark` div with an `<img>` tag pointing to your logo file.

## Contact

Questions about this site? Reach out via the contact form on the live site or email info@eberryharvest.com.

---

© 2026 EBerry Harvest Company LLC. All rights reserved.
