# Dr. Ravula Uma Reddy — Consulting Website

Professional consulting front-end for Dr. Ravula Uma Reddy, MSc (Ag), PhD — Associate Director of Research, RARS Warangal, PJTSAU. Single static page, no build step.

## Files

- `index.html` — the live site (v2). Self-contained: all CSS/JS inline, fonts from Google Fonts, hero image from Unsplash, video thumbnail from YouTube's image CDN.
- `archive/v1-initial-design.html` — earlier design, kept for reference.

## TODO

1. **Banner photo**: the hero has a placeholder portrait (initials "UR"). Search for `BANNER PHOTO` in `index.html` — replace the placeholder `<div class="portrait">...</div>` inner content with `<img src="banner-photo.jpg" alt="Dr. Ravula Uma Reddy">` once the photo is added to the repo.
2. **Verify "30+ years"**: the experience figure in the hero badge and stats is an estimate — confirm with Dad and adjust.
3. **Deploy to Vercel**:
   ```bash
   cd uma-reddy-consulting
   git init && git add -A && git commit -m "Initial site"
   gh repo create uma-reddy-consulting --public --source . --push   # or push manually
   npx vercel --prod   # or import the repo at vercel.com/new for auto-deploys
   ```
   A Vercel token was generated for this (check validity). No `vercel.json` needed — static root deploy works as-is.
4. Optional: custom domain, contact form backend (currently `mailto:` to ravulaumareddy68@gmail.com — consider Formspree/Vercel Functions for a real form).

## Design notes

- Palette: pine `#10291a`, moss `#2c5e3b`, gold `#c9a24b`, cream `#faf8f2`. Fonts: Fraunces (display) + Inter (body).
- All external links (media, publications, PJTSAU records) open in new tabs (`target="_blank"`). YouTube video is a linked thumbnail, **not** an embed — per Manish's request.
- Scroll-reveal animations via IntersectionObserver; sticky nav darkens on scroll.

## Verified public sources used (the "proof" sections)

- HMTV "Nela Talli" interview — pink bollworm management in cotton: https://www.youtube.com/watch?v=UBYLh1ApkiE
- National Farmers' Day at RARS Warangal (chief guest, soil-health quote): https://hindudayashankar.com/education/national-farmers-day-celebrated-at-regional-agricultural-research-station-in-warangal/
- PJTSAU — cotton research scheme, RARS Warangal (2024): https://pjtsau.edu.in/cotton-research-scheme-rars-warangal-14-06-2024.html
- PJTSAU — residential training, modern agriculture & agri-business: https://www.pjtau.edu.in/training-modern-agriculture-agri-business-rars-warangal.html
- PJTSAU — seed distribution & kharif training for tribal beneficiaries (2023): https://www.pjtau.edu.in/rars-warangal-training-paddy-03-07-2023.html
- PJTSAU — Zonal Research & Extension Advisory Council meet (2022): https://pjtsau.edu.in/zonal-research-extension-advisory-council-meet-rars-17-03-2022.html
- Publication (2024, co-author): "Yield Attributes and Yield of Maize as Influenced by Paddy Straw Management Options and Nitrogen Levels in Rice–Maize Cropping Systems", Asian Journal of Soil Science and Plant Nutrition: https://journalajsspn.com/index.php/AJSSPN/article/view/314

Contact email on site: ravulaumareddy68@gmail.com · Location: Warangal, Telangana, India.
