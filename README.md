# SamTech Inc. – Company Profile

Static site with Tailwind CSS (CDN), ready to deploy on any static host (GitHub Pages, Netlify, Vercel, S3).

## Structure
```
samtech-profile/
├─ index.html          # Landing page with sections (Hero, About, Services, Industries, Contact)
├─ css/
│  └─ styles.css       # Minimal brand CSS (CTA button, glow)
└─ assets/
   ├─ logo.png         # Provided logo
   └─ favicon.png      # Favicon (same as logo)
```

## Edit Contact
Update the email in **index.html** (search for `mailto:`). The link already uses your requested class:
```html
<a href="mailto:samtechs.inc@gmail.com" class="cta-button">Email Us</a>
```

## Running locally
Just open `index.html` in a browser. No build step required.

## Deployment
- GitHub Pages: commit the folder as a repository and enable Pages.
- Netlify/Vercel: drop the folder as a static site.
- Any S3/CloudFront or Nginx: serve the folder as-is.
