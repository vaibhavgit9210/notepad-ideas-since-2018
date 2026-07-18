# notepad ideas, since 2018

In my first year of college I kept a notepad with a list of projects I wanted to build.
I never built them. Now, with AI, each one takes an afternoon — so I'm working through
the list, one page per idea.

House rules: single-file HTML, no frameworks, no build step, no CDN dependencies —
every page works offline.

**Live: https://vaibhavgit9210.github.io/notepad-ideas-since-2018/**

## The ideas

### 1. `disaster-history/` — A Century of Disasters

Big-data analytics of 125 years of the world's disasters — natural and man-made —
and what the data says about the link between technology and staying alive.

- Global deaths per year 1900–2025 (log scale), with the great spikes named
- Death rate per 100,000 people by decade — a ~46× fall — overlaid with the
  warning & safety milestones (weather satellites, cyclone shelters, tsunami
  warning systems…) that caused it
- Deaths by disaster type per decade: how floods and famines stopped killing,
  earthquakes never did, and heat is the one growing
- A curated catalog of ~90 major disasters (natural / man-made / mixed) as an
  interactive explorer with per-event notes
- 5,393 NASA EONET satellite-tracked events plotted by coordinates — no basemap,
  the disasters draw the continents themselves

Data: [Our World in Data — Natural Disasters](https://ourworldindata.org/natural-disasters)
(EM-DAT, CRED / UCLouvain; CC BY), NASA EONET via
[Kaggle](https://www.kaggle.com/datasets/shreyanshdangi/global-natural-calamities-dataset) (CC0),
UN population estimates, hand-curated event catalog from public records.
All data is embedded in the page at build time — no runtime fetches.

### 2. `password-generator/` — Password Generator

Random passwords your way — pick length, digits, letters, symbols.
Cryptographically random, runs entirely in your browser.

### 3. `enigma/` — Die Enigma

A working digital Enigma machine — type and watch the rotors turn. Plus the
history, how it was broken, and the algorithm explained.

### 4. `tracka-packet` — Where Packets Actually Go

Real traceroutes from my machine visualised over the real geometry of the world's
submarine cable network — hop by hop, cable by cable, with a speed-of-light sanity
check that catches IP geolocation lying. Lives in its own repo:
[tracka-packet](https://github.com/vaibhavgit9210/tracka-packet) ·
[live](https://vaibhavgit9210.github.io/tracka-packet/)

---

*More ideas from the notepad to come.*
