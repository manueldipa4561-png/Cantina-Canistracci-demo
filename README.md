# Cantina Canistracci — concept demo

Concept website for **Cantina Canistracci**, an enoteca / wine bar in Parma, created as an unsolicited demonstration by **Punto Due Studio**.

> Concept dimostrativo non commissionato. This repository does not imply endorsement, approval, or a commercial relationship with Cantina Canistracci.

## Crescita scope

This demo represents the Punto Due Studio **Crescita — €700** package. It deliberately stays within a focused static-site scope:

- custom one-page visual design;
- mobile-first responsive layout;
- accessible navigation and focus states;
- click-to-call;
- Google Maps directions;
- official social links;
- factual LocalBusiness structured data;
- basic SEO / Open Graph metadata;
- favicon;
- restrained reveal interactions with reduced-motion support;
- branded 404 page;
- Netlify-ready deployment settings and security headers.

No login, database, custom booking engine, CRM, loyalty system, payment flow, admin dashboard or other Evoluzione-level functionality is implemented.

## Business represented

**Cantina Canistracci**  
Piazzale San Lorenzo, 3  
43121 Parma PR, Italy  
Phone: +39 379 128 6833  
Instagram: https://www.instagram.com/cantinacanistracci/  
Facebook: https://www.facebook.com/CantinaCanistracci

### Public opening hours used in the demo

- Monday: closed
- Tuesday: 18:30–01:00
- Wednesday: 18:30–01:00
- Thursday: 18:30–01:00
- Friday: 18:30–02:00
- Saturday: 12:00–02:00
- Sunday: 18:30–00:00

Hours can change. A production site should confirm them directly with the business before launch.

## Public sources

Research was based on public information available in September 2026. Important sources include:

- Restaurant Guru — current address, phone, hours, Instagram handle, services and business category: https://restaurantguru.it/Canistracci-Parma
- Tripadvisor — public reviews and current visitor feedback: https://www.tripadvisor.it/Attraction_Review-g187804-d5928554-Reviews-Cantina_Canistracci-Parma_Province_of_Parma_Emilia_Romagna.html
- Municipality of Parma public document — Daniele Piccioni states he opened Cantina Canistracci in 2011: https://www.elezioni.comune.parma.it/handlers/GetDocumentoTrasparenza.ashx?id=1609
- Confesercenti — Cantina Canistracci participation in the San Lorenzo cultural programme: https://www.confesercenti.it/blog/confesercenti-parma-i-martedi-in-san-lorenzo-per-unestate-di-musica-e-letteratura-in-piazzale-san-lorenzo/
- Gazzetta di Parma — Cantina Canistracci participation in wine tastings during the Dal Mississippi al Po festival: https://www.gazzettadiparma.it/spettacoli/2023/06/06/news/il-festival-blues-dal-mississippi-al-po-anche-quest-anno-fa-tappa-a-parma-717096/
- Historic acoustic-design case study — identifies the venue as an enoteca in Parma and documents its original design project: https://www.lavoripubblici.it/documenti/88-8207-909-3-abstract.pdf

Third-party claims that could not be verified strongly enough were not used as hard factual promises in the website.

## Content deliberately omitted

The concept does **not** invent or publish:

- a fixed wine list;
- wine prices;
- a food menu;
- WhatsApp availability;
- legal / VAT information;
- an online booking provider;
- an email address as a primary CTA;
- exact current event dates;
- awards or unverified commercial claims.

A legacy `canistracci.it` email/domain appears in some older directories, while current public listings point visitors mainly to Facebook/Instagram. The demo therefore does not present a standalone official website or that email as current without direct confirmation.

## Design direction

The visual system is intentionally different from a generic restaurant template. It uses an editorial wine-label language with burgundy, warm paper, serif typography, bottle/glass illustrations and restrained motion. No generic stock photography is presented as if it depicts the real venue.

## Project structure

```text
/
├── index.html
├── styles.css
├── script.js
├── 404.html
├── _headers
├── netlify.toml
├── robots.txt
└── assets/
    └── favicon.svg
```

## Local development

No build step or package installation is required.

Run any simple static server from the repository root, for example:

```bash
python -m http.server 8080
```

Then open `http://localhost:8080`.

## Netlify deployment

Import the GitHub repository into Netlify.

- Base directory: leave empty
- Build command: leave empty
- Publish directory: `.`
- Functions directory: leave empty

`netlify.toml` already declares the repository root as the publish directory. `_headers` contains lightweight security headers.

## Production requirements

Before converting this concept into an official production website, confirm directly with Cantina Canistracci:

- current opening hours;
- preferred phone/contact flow;
- current social URLs;
- current wine/food offering and any menu content;
- reservation policy;
- approved photography and brand assets;
- legal entity / privacy information if needed;
- final domain and canonical URL.

Once a production URL exists, add the canonical URL, `og:url`, sitemap reference and any approved social-share image.
