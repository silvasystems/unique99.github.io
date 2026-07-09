# Unique 99

Unique 99 is a Commander deck uniqueness scoring tool.

Paste a Commander decklist, analyze card popularity using Scryfall EDHREC rank data, and get a uniqueness score out of 100.

## Project Structure

```txt
unique99/
  index.html
  styles.css
  app.js
  README.md
  .gitignore
```

## Current Notes

This cleanup build restores the simple U99 text logo and removes the need for mana image assets. Mana colors are now CSS pips, so there is no `assets` folder required for the current version.

## Deploying on Vercel

This is a static site.

Recommended Vercel settings:

- Framework Preset: Other
- Build Command: leave empty
- Output Directory: leave empty or `.`
- Install Command: leave empty


## Mana Symbol Assets

This build expects these files inside the `assets` folder:

```txt
assets/mana-w.png
assets/mana-u.png
assets/mana-b.png
assets/mana-r.png
assets/mana-g.png
```

Do not upload these mana files to the root of the repository. They must be inside `assets/`.


## Feedback Round Update

Layout changes:
- Left side now prioritizes commander identity, score, verdict, stats, and score explanation.
- Right side starts with Deck at a Glance.
- Removed Deck Identity section.
- Renamed quick tables to Most Common Cards and Most Unique Cards.
- Moved report filter explanation under Full Card Report.
- Tried brighter neon blue theme.
