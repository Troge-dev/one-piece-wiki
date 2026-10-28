# One Piece Wiki — Frontend Web Application

A responsive, client-side wiki website dedicated to the *One Piece* anime series. It provides character encyclopedias, story saga breakdowns, and an interactive data visualization tracking Straw Hat pirate bounties over time.

---

## Key Features

* **Bounty Progression Over Time:** Interactive line chart (powered by Chart.js) visualizing bounty milestones from East Blue (30M ฿) to Post-Wano (8.8B ฿).
* **Character Wanted Posters:** Authentic Marine wanted poster cards with live search and category filters (Straw Hats, Emperors, Worst Generation).
* **Story Sagas & Episode Metrics:** Summary table of anime sagas, episode ranges, and average ratings.
* **100% Client-Side:** Built strictly using vanilla HTML5, CSS3, and JavaScript — zero backend setup required.

---

## Project Structure

```text
one_piece_wiki/
├── index.html              # Main Wiki Landing Portal
├── pages/
│   ├── bounties.html       # Bounty timeline & Chart.js graph
│   ├── characters.html     # Character roster & Wanted posters
│   ├── arcs.html           # Story sagas & episode statistics
│   ├── luffy.html          # Monkey D. Luffy profile
│   ├── zoro.html           # Roronoa Zoro profile
│   ├── nami.html           # Nami profile
│   ├── usopp.html          # Usopp profile
│   ├── sanji.html          # Vinsmoke Sanji profile
│   ├── chopper.html        # Tony Tony Chopper profile
│   ├── robin.html          # Nico Robin profile
│   ├── franky.html         # Franky profile
│   ├── brook.html          # Brook profile
│   └── jinbe.html          # Jinbe profile
├── assets/
│   ├── css/
│   │   ├── style.css       # Global layout & design tokens
│   │   └── components.css  # Cards, wanted posters & table styling
│   ├── js/
│   │   ├── data.js         # Static dataset (bounties, characters, arcs)
│   │   ├── main.js         # Navigation & global utilities
│   │   ├── bounty_tracker.js # Chart.js setup & milestone rendering
│   │   └── characters.js   # Search & filter logic
│   └── img/                # Image and icon assets
└── README.md
```


