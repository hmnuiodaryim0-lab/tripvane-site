# TripVane website

The official product, support, privacy, and search landing-page website for TripVane. This dependency-free static site deploys through GitHub Pages from the `main` branch at the repository root. It contains no analytics, cookies, advertising scripts, third-party fonts, or external runtime dependencies.

## Structure

- `index.html` — English product homepage
- `privacy.html` and `support.html` — English privacy and support pages
- `zh-hans/` — Simplified Chinese equivalents
- `travel-weather-planner/`, `trip-weather-planner/`, `road-trip-weather-planner/`, `itinerary-weather-forecast/`, `travel-weather-alerts/` — English SEO pages
- `zh-hans/…` — Simplified Chinese equivalents of each SEO page
- `sitemap.xml` and `robots.txt` — search-discovery files
- `assets/` — TripVane icon and product screenshots

## SEO

Every public page has a self-referencing canonical URL. English and Simplified Chinese equivalents reference one another with `hreflang="en"`, `hreflang="zh-Hans"`, and `hreflang="x-default"` (which points to English). Homepage structured data uses `SoftwareApplication`; landing pages use `WebPage` JSON-LD. Open Graph and Twitter metadata use the existing official TripVane icon.

- Sitemap: https://hmnuiodaryim0-lab.github.io/tripvane-site/sitemap.xml
- Robots: https://hmnuiodaryim0-lab.github.io/tripvane-site/robots.txt

## Google Search Console

- Property type: URL-prefix
- Property: https://hmnuiodaryim0-lab.github.io/tripvane-site/
- Recommended verification: HTML meta tag

After obtaining the `google-site-verification` token, add its meta tag to the HTML `head` of the property root homepage (and, if desired, all root HTML pages). Do not add a placeholder token.

## GitHub Pages

Configure Pages to deploy `main` / root.

- Homepage: https://hmnuiodaryim0-lab.github.io/tripvane-site/
- Privacy: https://hmnuiodaryim0-lab.github.io/tripvane-site/privacy.html
- Support: https://hmnuiodaryim0-lab.github.io/tripvane-site/support.html

City data includes information from GeoNames, licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
