# SFBS Group - Germany Visa Consultancy (Design Prototype)

Static, single-file prototype (index.html). No build step, no dependencies.
Languages: English, Deutsch, Espanol. Staff demo: footer link "Staff" -> Sign in.
Note: leads are sample data held in the browser and reset on reload. robots.txt blocks search engines on purpose (demo).

## Deploy on Cloudflare Pages (recommended)
Option A (no tools): Cloudflare dashboard -> Workers & Pages -> Create -> Pages -> Upload assets -> drag this folder -> Deploy. You get https://<name>.pages.dev
Option B (CLI): npx wrangler pages deploy . --project-name sfbs-demo

## Deploy on Vercel
cd into this folder, then: npx vercel --prod
(or drag the folder into https://vercel.com/new). Framework preset: Other. No build command, output directory ".".

## Before the real launch
- Replace robots.txt with an allow rule and add sitemap.xml.
- Connect the domain www.sfsbsgroup.com and confirm the contact email (domain and email spellings differ).
- Native German/Spanish proofreading; legal review of Impressum and Privacy.
