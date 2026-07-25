# LOJ Photography Inc. — Website

Design source of truth for **www.lojphotography.com**. The live site is built and hosted on Squarespace; this repo holds the design blueprint, the reusable Custom CSS, the build plan, and brand assets, with version history for easy iteration.

## What's here

```
loj-photography-website/
├── mockup/
│   └── index.html          # The interactive design mockup (open in a browser)
├── squarespace/
│   ├── custom-css.css      # Paste-ready Custom CSS for Design > Custom CSS
│   └── build-plan.md       # Step-by-step Squarespace build plan
├── assets/
│   └── logo.png            # Brand logo (gold on black)
└── README.md
```

## Important: GitHub does not deploy to Squarespace

Squarespace is a closed host with no Git connection, so pushing here does **not** update the live site. Use this repo to iterate on the design and keep history. Changes reach the live site two ways:

- **Custom CSS** round-trips: edit `squarespace/custom-css.css` here, then copy it into Squarespace under **Design > Custom CSS**.
- **Everything else** (pages, galleries, commerce, scheduling) is edited inside the **Squarespace editor**, using `squarespace/build-plan.md` as the guide.

Think of it as: repo for design + history, Squarespace editor for the live site, CSS as the bridge.

## Iterating going forward

Open this repo in **Claude Code** and ask for changes to the mockup or CSS. It edits, commits, and pushes without needing the chat interface. Then paste any updated CSS into Squarespace.

## Brand quick reference

- Domain: www.lojphotography.com
- Email: contact@lojphotography.com
- Instagram: https://www.instagram.com/lojphotography
- Facebook: https://www.facebook.com/lojphotography
- Fonts: Bodoni Moda (headings), Jost (body)
- Core colours: gold `#C6A23C`, cream `#FBF7EE`, ink `#1A1410`
