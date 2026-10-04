# Congregation Assistant public website

Public landing page for Congregation Assistant. Serve index.html, site.css, and site.js together. The application link opens https://photographicode.github.io/congregation-assistant/ . Trial requests create an email draft; no automatic submission or charge occurs. Annual offer: ₹1,499.

Run npm install and npx playwright install --with-deps chromium webkit, then npm test. CI checks desktop Chromium, mobile Chromium and mobile WebKit; the deployed check verifies asset hashes before testing.
