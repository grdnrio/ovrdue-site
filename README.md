# ovrdue.app website

Static site, no build step. Open `index.html` in a browser to preview.

Hosting: GitHub Pages from the `ovrdue-site` repo (this folder is mirrored
there). `CNAME` points the Pages site at ovrdue.app; DNS needs the four
GitHub Pages A records on the apex plus a `www` CNAME to `<user>.github.io`.

Waitlist: set `WAITLIST_ENDPOINT` in `index.html` to the form provider's POST
URL. Until it's set, the form tells people to email hello@ovrdue.app.

`home.webp` is a simulator screenshot of the iPhone app with sample data
(the names are made up).
