# I-WORKS Website

Premium Technology presentation website for I-WORKS (North Macedonia).

## Features
- Responsive, dark premium design
- Four languages: English, Macedonian, Albanian, Russian
- StellarECC, SARISA and HAVOC GUARD portfolio
- About, Expertise, Labs, Mission and Contact sections
- Static files: no build dependencies, no backend, no analytics or cookies

## Local preview
Open `index.html` in a browser, or run `python -m http.server 8000` in this directory and visit http://localhost:8000.

## Deploy to Cloudflare Pages
1. Create a new GitHub repository named `I-WORKS-WEBSITE`.
2. Push the files in this directory to its `main` branch.
3. Cloudflare dashboard → Workers & Pages → Create → Pages → Connect to Git.
4. Select the repository; framework preset **None**, build command **empty**, output directory **/** (repository root).
5. Deploy, then under Custom domains add `i-works.com.co` and `www.i-works.com.co` and follow DNS prompts. Configure a canonical redirect if desired.

## Before launch
- Confirm I-WORKS legal status and ownership of project names.
- Approve product descriptions, especially HAVOC GUARD capabilities and SARISA prototype status.
- Add an authorized contact email before adding a contact form.
- Review translations and accessibility with native speakers.
- Review privacy/legal pages before adding analytics, forms or personal-data processing.
- Replace proposed graphical branding if an official logo exists.

No changes to the StellarECC, SARISA or HAVOC GUARD source repositories are required.
