# HomeSmart USA — Static Website

A multi-page, static HTML/CSS/JavaScript website for homeowner education and browser-based planning calculators. No build step, Node.js, database, or paid API is required.

## Folder contents
- `index.html` — homepage
- `energy.html`, `solar.html`, `maintenance.html`, `heating-cooling.html`, `improvement.html` — topic hubs
- `calculators.html` — six interactive calculators
- `guides.html` — directory of the ten articles
- `articles/` — ten individual article pages
- `about.html`, `contact.html`, `privacy.html`, `terms.html`, `editorial-policy.html`, `disclaimer.html` — trust and policy pages
- `404.html` — custom not-found page
- `assets/styles.css`, `assets/main.js`, and local SVG illustrations
- `robots.txt`, `sitemap.xml` — SEO starter files

## Before launch
1. Choose your final domain or free subdomain.
2. Replace every `https://www.homesmartusa.example/` canonical/Open Graph/schema URL with the exact live HTTPS base URL. Also update `sitemap.xml` and `robots.txt`.
3. Replace `hello@homesmartusa.example` with an email address you control.
4. Review Privacy Policy and advertising disclosures against your actual host, ad network, analytics, forms, and applicable law. The current site has no analytics, contact form backend, newsletter, or active ad scripts.
5. Review all editorial content and source links. Check current solar incentives and safety guidance from official sources.
6. The article pages intentionally do not claim publication or reviewed dates that have not been established.
7. Ad areas are labeled placeholders. Add only actual code from an ad network after approval and after reviewing current policies and privacy/consent obligations.

## Deploy to Netlify (manual static deploy)
Hosting interfaces can change. As a general workflow, use the provider's current official instructions:
1. Download this ZIP and extract it on your computer.
2. Open the extracted `homesmart-usa` folder. Confirm `index.html` is directly inside it (not buried in a second nested folder).
3. In your Netlify account, open the manual deploy / drag-and-drop deploy area (often called Netlify Drop or a deploy page). Upload or drag the extracted site folder, or the folder's contents if the interface requests files. Do not upload the ZIP unless the current interface explicitly accepts ZIP uploads.
4. Wait for the deploy to finish, then open the generated `*.netlify.app` URL. Save/claim the site in your account if prompted so you can manage future deployments. Netlify's UI and account workflow may change; follow the current official Netlify documentation if labels differ.
5. Test the homepage, every top navigation link, all ten articles, the six calculators, and the 404 page by visiting a deliberately incorrect URL.
6. Replace canonical URLs and Open Graph URLs throughout HTML with your actual deployed URL. Update `sitemap.xml` and `robots.txt`, then redeploy.
7. In Google Search Console, add your site using the supported property type, complete verification, and submit the sitemap URL (for example, `https://YOUR-SITE.netlify.app/sitemap.xml`). Inspect important URLs and monitor indexing. Search appearance and rankings are not guaranteed.
8. To use a custom domain later, register a domain with a registrar, add it in your hosting provider's domain settings, and follow the provider's DNS instructions. Enable HTTPS and update canonical URLs, sitemap, robots, and Search Console after the domain is live.

## Local testing
You can open `index.html` directly in a modern browser. For more reliable local testing, run a basic local static server if available, or deploy a temporary preview. No compilation is needed.

## SEO and launch checklist
- [ ] Replace `.example` canonical and Open Graph URLs with the live domain.
- [ ] Update `sitemap.xml` and `robots.txt`.
- [ ] Replace placeholder contact email.
- [ ] Confirm Privacy Policy and legal text fit actual data flows and jurisdiction.
- [ ] Review article links and all calculator results.
- [ ] Add approved ad code only after publisher approval; keep ads labeled and distinct.
- [ ] Verify site ownership and submit sitemap in Search Console.
- [ ] Test on mobile and desktop, keyboard navigation, and reduced-motion preferences.
