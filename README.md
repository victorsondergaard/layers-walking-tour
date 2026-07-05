# Layers — Historical Walking Tours (working title)

Phase 1 demo build of the AI historical walking tour concept: a static, host-anywhere
mobile web app. One live city (Palma de Mallorca), one complete human-reviewable route
— *Layers of Palma: From Madina Mayurqa to the Sea Walls* — 8 stops behind the Cathedral.

- **Nothing generated at runtime.** All narration is pre-authored in `palma-route.json`;
  every specific historical claim carries sources (the hidden fourth layer).
- Narration is spoken by on-device text-to-speech as a free stand-in for the recorded
  narrator voice of later stages.
- Maps: Leaflet + OSM/CARTO tiles. No API keys, no backend, no cost.
- GPS-triggered stops, out-of-order walking, progress persistence, learn-more layer,
  soft paywall with email capture (nothing processed).
- Demo mode: the 🚶 button simulates a walker strolling the route — it pauses to
  listen at each stop — so the full experience can be demoed from anywhere on earth.

Built from the concept brief, Part B. Deployed via GitHub Pages.
