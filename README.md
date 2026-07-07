# Studio EX test site — Exhibit 00

Test build of the new studioex.co site, built from the V2 build brief.

The idea: the site is **Exhibit 00** — Studio EX's own artwork about Studio EX.
You arrive as a node, scrolling traverses the network, and the closing form
"joins" you (your node lights up coral).

## What's in here

- Single self-contained `index.html` — no build step, same house style as the
  Orbit and Cost of War pages.
- Lenis smooth scroll + GSAP ScrollTrigger (CDN), canvas constellations
  (no video assets yet, so every media panel is a live generative visual —
  which the brief itself prefers to "videos of a network").
- Dark world (`#0A0A0F`) ↔ Studio Blue floods (`#1B1BE8`) with Signal Coral
  (`#FF5A4D`) as the single accent. Hexes still need verifying against the
  ex logo before locking.
- All counters are labelled **DEMO DATA** in the UI — honesty is on-brand.
- Full `prefers-reduced-motion` path: no pinning, static beats, final values.
- Real content folded in from the live Wix site (www.studioex.co): the Six
  Degrees waitlist ("8 billion lives, one artwork", Spring/Summer 2026),
  the full 001–009 catalogue (Olha Pra Mim, A Problem Shared, A Portrait of
  Emotions, Identity Crisis, Boy Without Balloon…), testimonial quotes,
  Our Artists (Blueprint, Thiago Santos) + become-an-artist call, "We Work
  Everywhere", purpose copy, credits (Narrative Engine, Blueprint), and the
  real contact details (greg@studioex.co / WhatsApp / +44 771 564 3569).
- Lab EX services section from the live "Our Services" page: three service
  groups (Visual & Experiential Design, Strategy & Creative Direction,
  Interactive Technology) with a described line per service, the four-step
  How We Work process, the Serving Industry Leaders client grid (names read
  from the live site's logo files — verify: BBC Studios, WB, UAL, West 13,
  Supa Ninki, Ludo, XLL, CRG, LNU, Instituto Usiminas), collaborators
  (Narrative Engine, Blueprint, Thiago Santos), and the real team from the
  About page (Gregory Taylor, David Rickmann, Daniel Atherton, Jason Davey,
  Steven Sprague) plus the five core principles.

## Run it

Any static server, e.g.

```
python3 -m http.server 8080
```

then open http://localhost:8080

## Still to verify (from the brief)

- Exact blue + coral hexes (sample the ex logo)
- Real display/mono typefaces (currently Inter Tight + JetBrains Mono stand-ins)
- Live HUD data source (Six Degrees / Orbit) — currently demo-labelled
- Orbit IMEX / EEMAGINE dates, product live links
- Real video assets for the pinned narrative, if wanted over generative canvas
