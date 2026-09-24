# CMR villa campaign landing pages

Independent, static landing pages for CMR Developers campaigns, deployed to
`campaign.cmrdevelopers.com` on Hostinger.

Each project lives in its own folder with an `index.html`, matching the path
used on Hostinger, so a page's URL is `campaign.cmrdevelopers.com/<folder>/`
with no `.html` extension:

- `aina-harmony-angamaly/index.html` — Aina Harmony, Angamaly. Form is wired
  to the live CMR enquiry API (`/api/enquiry`).
- `aiza-harmony-mulanthuruthy/index.html` — Aiza Harmony, Mulanthuruthy. Form
  is still a local-only placeholder (see below).

## Deploy to Hostinger

1. In Hostinger, open `campaign.cmrdevelopers.com`'s file manager (document
   root `public_html`).
2. Upload the project's folder (or just its `index.html` into the
   matching `public_html/<folder>/` path), overwriting the existing file.
3. Visit `campaign.cmrdevelopers.com/<folder>/` and submit a test lead form
   once its endpoint is connected.

All logo, favicon, and villa imagery use absolute CMR/WordPress URLs, so no
image files need to be uploaded alongside these pages.

## Important

`aiza-harmony-mulanthuruthy/index.html`'s form currently shows a confirmation
message and sends GTM events, but it does not yet send lead data to an API,
email inbox, or CRM.
