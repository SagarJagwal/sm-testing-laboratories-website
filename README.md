# S.M. Testing Laboratories — Website

A responsive static website built with HTML, CSS and vanilla JavaScript.

## Pages
- `index.html` — Home
- `about.html` — About the laboratory
- `services.html` — Seven material categories
- `accreditation.html` — NABL documentation placeholder
- `contact.html` — Phone, address, hours and Google Maps

## Run locally
Open `index.html` in a browser, or use a local static server. For example, from this folder with Python installed:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Before publishing
1. Get client approval for all copy and the logo.
2. Replace stock imagery with genuine laboratory/equipment photos where possible.
3. Obtain and verify the current NABL certificate and scope of accreditation before publishing accreditation claims or certificate downloads.
4. Confirm the precise tests offered, test methods/standards, sample requirements and turnaround times.
5. Confirm the phone number and whether WhatsApp should be enabled.
6. Confirm domain name, hosting, account ownership, and access recovery arrangements.
7. Check the map pin and address with the client.
8. Test all pages on mobile and desktop.
9. Consider adding privacy and cookie information if analytics, forms or other tracking are added.

## Notes
- This version does not include an enquiry form, WhatsApp integration, backend, analytics or CMS.
- The phone number is configured for click-to-call.
- Google Maps is embedded using the supplied address; confirm the pin is correct before launch.
- The homepage and service copy avoids claiming specific tests beyond the seven supplied categories.
- The accreditation page is explicitly a placeholder and should be updated only after document review.
- Some illustrative photos load from Unsplash and therefore require an internet connection. Replace with client-approved images for production where possible.


## Laboratory photographs
The `assets/laboratory-photos/` directory contains optimized copies of the client-supplied laboratory photographs. One duplicate upload was not copied twice. Images are used in the homepage, About, Services and Contact pages. Confirm image permissions and all photo captions with the client before publishing.
