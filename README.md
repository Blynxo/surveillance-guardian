# Surveillance Guardian: prototype

Live demo: https://blynxo.github.io/surveillance-guardian/

A clickable prototype from the NavX Academia Hackathon 2026 (Theme 2: Cyber-Secure Skies). It shows how software could help a surveillance engineer judge whether aircraft position reports can be trusted when GPS is jammed or spoofed.

**All traffic and events are synthetic.** The page shows the idea, not a finished product.

## What it shows

- One map: the sky over the UAE, with a zoom into DXB airport
- Six demo scenarios: normal day, GPS jamming at DXB, ghost aircraft, sudden position jump, ground radar reflection, vehicle reflection on the runway
- Badges on checked targets: J (jamming, nothing to do), R (reflection, nothing to do), ! (needs a person)
- Evidence and decision options for each alert. Guardian recommends an option, the engineer decides, and every decision is logged.

## Useful links

- Freeze the traffic: `?still`
- Open a scenario directly: `?scenario=normal`, `jamming`, `ghost`, `jump`, `reflection` or `rwyreflection`

Built with React, shadcn/ui, mapcn (MapLibre), React Bits and border-beam. Map data © OpenStreetMap contributors; imagery and basemap © Esri.
