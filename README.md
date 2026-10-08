# Laisamis Climate and Land Initiative (LCLI)

**A static website for land justice and climate resilience in northern Kenya.**

LCLI is a community movement, hosted as a program of the Feiyah Action Network (FAN), a registered Community Based Organization in Marsabit County. The site documents community land registration under the Community Land Act, land rights advocacy, climate resilience work, and LCLI's position against carbon finance on unregistered or non consenting community land.

LCLI takes no carbon finance, brokers no carbon deals, and has no carbon partnerships. See the "Our position on carbon" section on the homepage and in the partnership briefing for the full position.

---

## Site structure

This is a plain static site, no build step, no backend, served directly by GitHub Pages at [laisamisclimate.co.ke](https://laisamisclimate.co.ke).

```
LaisamisClimate/
├── index.html           # Homepage
├── services.html        # Programs: registration, advocacy, resilience, accountability
├── briefing.html         # Partnership briefing document (web version)
├── briefing.pdf          # Partnership briefing document (PDF)
├── insight-asal.html     # Field article: land rights in ASAL Kenya
├── insight-nlc.html      # Field article: the NLC community land registration process
├── insight-zones.html    # Field article: the constituency's four ecological zones
├── policies.html         # Privacy policy and terms of use
├── exchange.html         # Retired page notice (former carbon exchange concept)
├── robots.txt
├── sitemap.xml
├── CNAME                 # Custom domain configuration for GitHub Pages
└── funding/               # Internal funding outreach documents (not linked from the public site)
```

## Running locally

```bash
python3 -m http.server 5000
# then open http://localhost:5000
```

## Analytics

Cookieless, privacy friendly analytics via [GoatCounter](https://www.goatcounter.com/). Disclosed in `policies.html`.

## License

MIT License, see `LICENSE` if present.

## Contact

Feiyah Action Network / LCLI
Marsabit County, Kenya
