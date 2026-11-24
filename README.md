# Beat Bill: The Order Engine

A 3D visualization of information organizing itself. Six thousand file cards
start as grey chaos, sort into rings by kind, snap into a layered gem
(Concept, Spec, Build, Revenue), and pay out into the vault.

Built as a friendly show-and-tell challenge with a friend named Bill.

## Run it

Open `prototype/index.html` through any local web server, for example:

    python -m http.server 5173 --directory prototype

Then visit http://localhost:5173. It needs an internet connection to load
Three.js from a CDN.

## Controls

- **Organize** plays the full sequence; the slider scrubs between chaos and order.
- **Use my files** sorts the file names from a folder you pick. Only names are
  read, in your browser; nothing is uploaded.
- **Flow** (keys 1-4) switches the ordered shape: Stack, Pipeline, Network or Funnel.
  During the payout the market shifts every 11-17 seconds; the matching shape pays 3x
  and the others pay 0.6x. The news strip and the shouting commentators tell you which.
- **Sound** is generated in the browser (no audio files) and starts on your first click or key
  press; the Sound button mutes it.
- **Absorb Bill's Brain** is the opening gag.

The news outlets and commentators are invented parodies, not real broadcasters or people.

Copyright (c) 2026 austinhs2002. All rights reserved. See `LICENSE`.
