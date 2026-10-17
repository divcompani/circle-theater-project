# Circle · دایره

Web proposal for **Circle (دایره)**, written and directed by **Parastu Mohafezatkar**
(Faculty of Arts, Islamic Azad University, Central Tehran Branch). Official Selection and
**Stage Movement Award**, FIST 2026 (Belgrade). Next: 18th ETHOS Ankara International Theatre Festival 2026.

پروپوزال وب نمایش «دایره» — چهارزبانه (فارسی / English / Türkçe / العربية)، واکنش‌گرا.

## Structure

```
index.html                      the whole site (HTML + CSS + JS, no build step)
img/                            performance photos (resized for web)
fonts/                          Doran webfonts (Persian: Doran FaNum, Arabic: Doran)
audio/circle-theme.mp3          the play's music (add it yourself — see audio/README.txt)
vendor/lenis.min.js             smooth-scroll library (local copy, works without CDN)
Circle-Booking-Request-FA.pdf   fillable booking form — Persian
Circle-Booking-Request-EN.pdf   fillable booking form — English
Circle-Booking-Request-TR.pdf   fillable booking form — Turkish
Circle-Booking-Request-AR.pdf   fillable booking form — Arabic
```

## Publish on GitHub Pages

1. Create a new repository and upload the **contents** of this folder to its root.
2. Settings → Pages → Source: `Deploy from a branch`, Branch: `main`, folder `/ (root)`.
3. The site goes live at `https://<username>.github.io/<repository>/`.

## Online booking form

GitHub Pages is static and cannot store data, so the form uses **FormSubmit** (formsubmit.co, free, no account)
to email each request to `parastumohafezatkar.art@gmail.com`.

- **One-time activation:** after the site is live, send one test request. FormSubmit emails an
  activation link to that inbox — click it once. From then on every request arrives by email.
- Visitors can also send the same request by **WhatsApp** (+98 901 131 9876) or **email** with one click.

## Credits

- Project consultant: Deev Theatre Company
- Photos: Erfan Aghaei (marked) and production photographers
- Persian/Arabic typeface: Doran, by Fereshte Iranshahi & Reza Bakhtiarifard — fontiran.com (commercial license, see below)
- Latin typefaces: Cormorant Garamond, Vazirmatn (Google Fonts, OFL)

## Font license note

Doran is proprietary software from fontiran.com. Uploading it to a website requires a license
registered on fontiran.com for this project (a free non-commercial license is available).
Register it before making this repository or the site public.
