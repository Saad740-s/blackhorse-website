# BlackHorse Property Care

Marketing landing page for BlackHorse Property Care — reliable lawn care, seasonal
cleanups, driveway sealing and outdoor property services across Milton, Oakville
and Mississauga.

## Tech
Pure static HTML / CSS / JS. No build step. Deploys to Vercel as-is.

## Files
- `index.html` — page markup
- `styles.css` — all styling (turf + stable identity)
- `script.js` — nav scroll state, mobile menu, scroll reveals

## Customize before launch
1. **Contact info** — replace phone `(123) 456-7890`, email, and Instagram handle in the Contact section of `index.html`.
2. **Form** — replace `YOUR_FORM_ID` in the `<form action>` with your Formspree form ID (formspree.io — free tier works), or swap for Adel's booking endpoint later.
3. **Gallery photos** — the before/after tiles are CSS placeholders. Drop real job photos in by replacing the `.shot__ba` blocks with `<img>` tags.
4. **Booking button** — currently scrolls to the contact form. When Adel's booking page / QR is ready, point `#bookingBtn` at that URL.

## Deploy
Push to GitHub, import in Vercel, framework preset = **Other**, root = `./`. No build command needed.
