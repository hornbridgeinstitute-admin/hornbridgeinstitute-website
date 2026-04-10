# Horn Bridge Institute — Official Website

**Organization:** Horn Bridge Institute (HBI)  
**Tagline:** Bridging knowledge across the Horn of Africa  
**Stack:** Pure HTML5 + CSS3 + Vanilla JS — zero dependencies  
**Hosting:** GitHub + Cloudflare Pages  

## Pages
| File | Page |
|------|------|
| `index.html` | Homepage |
| `about.html` | About HBI |
| `programs.html` | Our Programs |
| `research.html` | Research & Policy |
| `get-involved.html` | Get Involved |
| `contact.html` | Contact |

## Deployment (Cloudflare Pages)

1. Push this repo to GitHub
2. Log into [Cloudflare Pages](https://pages.cloudflare.com/)
3. Click **Create a project** → **Connect to Git**
4. Select this repository
5. Build settings:
   - **Framework preset:** None
   - **Build command:** *(leave empty)*
   - **Build output directory:** `/` (root)
6. Click **Save and Deploy**
7. Your site is live at `https://your-project.pages.dev`
8. Add your custom domain: `hornbridgeinstitute.org` → Settings → Custom Domains

## Custom Domain Setup
1. In Cloudflare Pages → Custom Domains → Add Domain
2. Enter `hornbridgeinstitute.org`
3. Update your domain's nameservers to Cloudflare
4. SSL is automatic via Cloudflare

## Development
```bash
# No build step needed — open any HTML file in your browser
# Or use a simple local server:
npx serve .
# or
python3 -m http.server 8000
```

## Fonts
Google Fonts CDN: Playfair Display + DM Sans + DM Mono  
No self-hosting required.

## Brand
Logo files are embedded as base64 SVG data URIs — no external image dependencies.

---
**Prepared by:** Abdirahman Jama, Executive Director  
**Horn Bridge Institute** | Addis Ababa, Ethiopia  
