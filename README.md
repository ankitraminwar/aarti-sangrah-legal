# Aarti Sangrah Privacy Policy

This repository hosts the public privacy policy for the **Aarti Sangrah** app on Google Play Store.

## Contents

- **index.html** — Privacy policy landing page, styled to match the Aarti Sangrah app design language.
- **styles.css** — Visual styling using the app's color palette (warm saffron and cream editorial theme), typography (Noto Serif + Plus Jakarta Sans), and responsive layout.
- **README.md** — This file.

## Purpose

This static site provides a publicly accessible privacy policy URL required by Google Play Store during app submission and review. The policy explains:

- No personal data is collected
- All data stays on-device (using SQLite)
- Internet is used only for content sync from CDN
- No ads or third-party tracking
- App is safe for all ages
- Policy update procedures

## Deployment

1. Enable GitHub Pages on this repository:
   - Go to **Settings > Pages**
   - Select **Deploy from a branch**
   - Choose **main** branch, **/ (root)** folder
   - Save

2. The policy will be live at:
   ```
   https://ankitraminwar.github.io/aarti-sangrah-legal/
   ```

3. Use this URL in Google Play Console under **App content > Privacy policy**.

Simply upload `index.html` and `styles.css` to any web server. The page is fully static and requires no backend.

## Design

The page matches the Aarti Sangrah app's visual identity:

- **Color Palette**: Warm saffron (#8f4e00 primary), cream surface (#faf9f6)
- **Fonts**: Noto Serif for headings, Plus Jakarta Sans for interface text
- **Spacing & Radius**: Consistent with app's Material Design–inspired system
- **Responsive**: Works on mobile, tablet, and desktop

## Maintenance

### Updating the Policy

1. Edit `index.html` to change policy text
2. Ensure changes align with actual app behavior and Play Console Data safety form
3. Update the "Last updated" date in the footer
4. Commit and push changes
5. GitHub Pages updates automatically

### Google Play Compliance

When updating the policy:

- Keep the URL stable (don't move the page)
- Ensure wording matches your Play Console **Data safety form** declarations
- Include any changes to how data is collected, stored, or shared
- If you add new permissions or SDKs, update the policy accordingly

## Contact

For privacy-related inquiries:

- **Website**: [https://www.thinkercart.com](https://www.thinkercart.com)
- **App**: Aarti Sangrah (Google Play)

---

**Last updated**: April 2026
