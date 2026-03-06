# Beyond Measure · South Carolina WBB
**SEC WBB Tournament: Quarterfinals · March 6, 2026**
Data visualization design and strategy by Kris Smith

---

## Overview

*Beyond Measure* is a single-file interactive data visualization documenting South Carolina Women's Basketball's SEC WBB Tournament Quarterfinals performance against the Kentucky Wildcats. Built in the editorial tradition of The Athletic and Sportico, the page leads with narrative and surfaces data on demand through collapsible sections.

The title and framing of this piece are drawn directly from the SEC Tournament hype video released by **@GamecockWBB** on X, in which the voiceover declared: *"They think they know who we are, what we're capable of. They've only known what they've seen on game day. This week is when we show that we are beyond measure."*

---

## Design Notes

- Opening paragraph font size: 13px with 1.75 line height for editorial readability
- Dawn Staley callout displays as a single line at 15px with white-space: nowrap
- All section toggles use consistent garnet button styling
- Bar chart widths are proportionally calculated against the highest value in each category

---

## How to Deploy to GitHub Pages

1. Save the visualization file as `index.html`
2. Create a new GitHub repository (suggested name: `scwbbsectourney1`)
3. Upload `index.html` to the root of the repository
4. Go to **Settings → Pages**
5. Under **Source**, select `main` branch and `/ (root)` folder
6. Click **Save**
7. Your page will be live at `https://[yourusername].github.io/scwbbsectourney1/`

> GitHub Pages may take 1 to 2 minutes to go live after the first deploy.

---

## Final Stats

**South Carolina 87 · Kentucky 64 · Final**

All statistics are final as of the buzzer on March 6, 2026. No placeholder values remain in the file.

Key final numbers:
- SC shot 52.5% from the field vs Kentucky's 43.1%
- SC dominated the paint 46 to 24
- SC forced 19 Kentucky turnovers, scoring 25 points off them
- SC finished with 21 assists and 10 steals
- Joyce Edwards led SC with 21 points on 66.7% shooting
- Ta'Niya Latson: 11 points, 6 assists · Raven Johnson: 7 points, 5 assists
- Dawn Staley earned her ninth 30-win season at South Carolina, the most in program history

---

## File Structure

```
scwbbsectourney1/
└── index.html
```

No additional files, folders, stylesheets, or scripts are required.

---

## Data Source

Statistics sourced from **SportRadar** via live game feed.
Player headshots, if added in future iterations, should be sourced from **South Carolina Athletics** (gamecocksonline.com).

---

## Quote Attribution

The voiceover excerpt featured in the opening section is taken directly from the SEC Tournament hype video published by **@GamecockWBB** on X. All rights belong to South Carolina Women's Basketball.

---

## Credits and Attributions

- Dawn Staley 30-win season stat courtesy of **Lulu Kesin** · South Carolina WBB and Football Reporter, Greenville News / USA Today Sports · Exact tweet: *"With the victory over Kentucky, Dawn Staley gets her ninth 30-win season at South Carolina."*
- SEC Tournament hype video quote from **@GamecockWBB** on X · All rights belong to South Carolina Women's Basketball
- Data visualization design and strategy by **Kris Smith**
- Built with HTML, CSS, and vanilla JavaScript · No frameworks
