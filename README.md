# Signal Siege

## Overview
Signal Siege is a small lane-based tower defense game. Enemies enter a 5-lane board from the right and walk toward your base on the left. Build Pulse, Frost, and Cannon towers to stop them. The game is a single HTML file using the Canvas API.

## How to Play
- Select a tower, then click or tap an empty tile to place it.
- Towers fire along their own lane. Frost slows enemies; Cannon ignores most armor and splashes nearby enemies.
- Earn money from kills, from a wave-clear bonus, and slowly over time.
- Click or tap a placed tower to upgrade it (up to level 3) or sell it for 60% of the money invested.
- Waves get harder. Fast enemies appear from wave 2, armored from wave 3, and a boss arrives every 5th wave.
- Your base has 10 lives. A boss that gets through costs 3. At 0 lives the game ends.

## Controls
| Input | Action |
|---|---|
| Mouse click / tap | Place tower, or select a placed tower |
| 1 / 2 / 3 | Select Pulse / Frost / Cannon |
| U | Upgrade selected tower |
| X | Sell selected tower |
| P or Pause button | Pause / resume |
| Esc | Deselect tower |
| Enter / Space | Start, or resume from a menu |

## Scoring
- +10 per enemy destroyed, +100 per boss.
- +100 x wave number each time a wave is cleared.
- Best score is saved in your browser (localStorage).

## Run Locally
Save the file as `index.html` and open it in a browser. No build step or server needed. An internet connection is only needed for the Google Fonts (a fallback font is used offline).

## Tech Used
HTML5 Canvas, vanilla JavaScript, CSS, Google Fonts (Chakra Petch, IBM Plex Mono). No libraries.

## Project Structure
```
index.html   # markup, CSS and game script in one file
README.md
```

## Credits
Developed by S YASHAS
And Dhruthishree V
