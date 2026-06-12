# Dr. Ravula Uma Reddy — Consulting Website

Professional consulting front-end for Dr. Ravula Uma Reddy, MSc (Ag), PhD — Associate Director of Research, RARS Warangal, PJTSAU. Single static page, no build step.

## Files

- `index.html` — the live site (v2). Self-contained: all CSS/JS inline, fonts from Google Fonts, hero image from Unsplash, video thumbnail from YouTube's image CDN.
- `archive/v1-initial-design.html` — earlier design, kept for reference.

## Status

- **Deployed**: https://uma-reddy-consulting.vercel.app/ (Vercel project `uma-reddy-consulting`; redeploy with `npx vercel deploy --prod --yes`). GitHub repo: https://github.com/manishravula/uma-reddy-consulting
- **Profile photo**: `profile-photo.jpg` — 4:5 crop from the HMTV maxres thumbnail (`ffmpeg crop=480:600:565:25` on `i.ytimg.com/vi/UBYLh1ApkiE/maxresdefault.jpg`). Replace with a real photo when available.
- **In the Media**: 19 verified YouTube broadcasts (deep-researched June 2026, each video ID checked live via YouTube oEmbed) + 9 press/institutional links, all identity-verified against RARS Warangal/ADR context. Excluded same-name people (FKCCI Bangalore entrepreneur, US obstetrician, politicians).

## TODO

1. **Verify "30+ years"**: the experience figure in the hero badge and stats is an estimate — confirm with Dad and adjust.
2. Optional: custom domain, contact form backend (currently `mailto:` to ravulaumareddy68@gmail.com — consider Formspree/Vercel Functions for a real form).
3. Medium-confidence videos held back (could add after Dad confirms it's him): Agritex 2014 ANGRAU interview (8gHdE2DXUHI), 2013 drum-seeder Jaikisan clip (aycOFXCIj2U).

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
