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
