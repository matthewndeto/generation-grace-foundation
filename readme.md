# Generation Grace website starter

A free, mobile-first static website starter for Generation Grace.

## Structure

- `index.html` — homepage
- `about.html` — organisation purpose and approach
- `programs.html` — community support, health, disaster relief and December food project
- `impact.html` — impact numbers and stories
- `volunteer.html` — volunteer application
- `donate.html` — donation information + donation-interest form
- `contact.html` — contact form
- `assets/css/style.css` — all styling
- `assets/js/main.js` — mobile menu + current year

## Important before publishing

1. Replace the `GG` logo placeholder with the official two-hands logo.
2. Add the official Generation Grace email, phone and location.
3. Add verified M-Pesa PayBill/Till details.
4. Add the official international donation link (PayPal or another provider).
5. Replace placeholder impact numbers with verified figures.
6. Only publish photos/stories when the organisation has the appropriate consent.

## Forms

The volunteer, contact and donation-interest forms use Netlify Forms attributes. They will work after deployment on Netlify with form detection enabled. They do not process payments.

## Recommended free deployment

For the easiest start, deploy this folder to Netlify or Cloudflare Pages. GitHub Pages is another free static hosting option.

## Payment note

A real M-Pesa checkout normally needs a payment provider/API and server-side handling. Do not put M-Pesa API secrets in HTML/JavaScript. Start with a verified PayBill/Till donation instruction, then add a secure payment integration later.


## Generation Grace details currently configured

- Email: generationgracefoundation@gmail.com
- Media Manager: 0113 644 272
- Chairman: 0794 204 580
- Secretary: 0714 018 721
- M-Pesa PayBill: 3374279
- Community photographs supplied by Generation Grace are stored in `assets/images/`.

## Still needed

- Official two-hands logo file
- Official organisation location/address, if you want it displayed
- International donation/payment link, if available
- Verified impact statistics and additional stories
