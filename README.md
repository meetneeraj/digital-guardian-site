# Digital Guardian — verification website

A static site that satisfies the website requirements for payment-gateway
(Razorpay) activation: product description, pricing, Terms, Privacy Policy,
Refund/Cancellation Policy, and Contact Us.

## Business details (already filled in)

| Field | Value |
|---|---|
| Business name | Digital Guardian |
| Support email | neerajhcumca@gmail.com |
| Support phone | +91 8919674480 |
| Registered address | Ameenpur, Hyderabad, Telangana 502032 |
| Jurisdiction | Hyderabad, Telangana |

> Make sure the **business name on your Razorpay account matches "Digital
> Guardian"** (or update the pages to match the exact name on your PAN /
> registration). Razorpay also verifies the email/phone are reachable.

## Deploy on GitHub Pages (free)

1. Create a new GitHub repo, e.g. `digital-guardian-site`, under your account.
2. Push these files to the repo's `main` branch:
   ```
   cd digital-guardian-site
   git init && git add . && git commit -m "Verification site"
   git branch -M main
   git remote add origin https://github.com/meetneeraj/digital-guardian-site.git
   git push -u origin main
   ```
3. GitHub → repo → **Settings → Pages** → Source: **Deploy from a branch** →
   Branch: **main** / **/ (root)** → Save.
4. After ~1 minute your site is live at
   `https://meetneeraj.github.io/digital-guardian-site/` — submit that URL to
   Razorpay (the website field).

## Optional: custom domain (digitalguardian.in)

1. Add a file named `CNAME` containing just `digitalguardian.in`.
2. At your domain registrar, add a CNAME/ALIAS record pointing to
   `meetneeraj.github.io` (and the four GitHub Pages A records for the apex
   domain — see GitHub's "Managing a custom domain" docs).
3. Settings → Pages → Custom domain → enter `digitalguardian.in` → enforce HTTPS.

Then submit `https://digitalguardian.in` to Razorpay.

## Pages
- `index.html` — landing + features + pricing summary
- `pricing.html` — full pricing & billing terms
- `privacy.html` — Privacy Policy
- `terms.html` — Terms & Conditions
- `refunds.html` — Refund & Cancellation Policy
- `contact.html` — Contact Us
- `styles.css` — shared styling
