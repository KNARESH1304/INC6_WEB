# The Haunted Harvest

A spooky, fully interactive Halloween story built with **HTML5 + CSS3 only (no JavaScript)**. Three chapters are switched with the CSS `:target` selector:

1. **Trick-or-Treat Lane / Haunted Town Square**
2. **Graveyard Hill / Midnight Graveyard Stroll**
3. **Witches' Party**

## Files

| File | Purpose |
|---|---|
| `index.html` | Splash gate; clicking it enters the town and starts the music |
| `town.html` | The three chapters |
| `haunted-harvest.css` | All styles; palette defined in CSS variables |
| `assets/` | Images, fonts, and `creepy-ambience.wav` (28-second looping audio) |

Fonts load from Google Fonts. Keep the `assets/` folder next to `index.html` so the audio loads.

## Features

- **Chapter switching** with `:target` only, no JavaScript.
- **Chapter 1:** bat on a flickering lamp post, ghost-story bench, floating balloons and ghost, falling candy and leaves, witch crossing the moon, hearse, fog, lightning, and cat.
- **Chapter 2:** couple walking hand in hand with the cat, blinking green ghost orbs, swaying dead tree, distant cyclist, and ghosts that rise above gravestones on hover or focus.
- **Chapter 3:** flying witches, hay wagon, and flickering candles.
- **Creepy sound:** native `<audio controls loop autoplay>` player. Browsers block autoplay with sound, so visitors usually press play once.
- **Pop-up ghosts on load:** ghosts, skulls, zombies, and pumpkins appear with "Boo!" captions, then fade away.
- **Pointer effects:** ghost cursor plus a hover-cell trail of ghosts, bats, spiders, skulls, and pumpkins.
- **Accessibility:** all motion sits inside a `prefers-reduced-motion` block.

## Team

Both members worked on this project together, planning, building, reviewing, and testing it as a pair.

| Member | GitHub | Contribution |
|---|---|---|
| Sri Krishna Teja Gangina | `<your-github-username>` | Splash gate (`index.html`) and music start; CSS palette/variables and base layout; Chapter 1 (Town Square) scenes and animations; audio track and player integration; deployment to codd.cs.gsu.edu |
| Naresh Kothoju | `<your-github-username>` | Chapter structure and `:target` navigation (`town.html`); Chapter 2 (Graveyard Stroll) scenes and gravestone ghosts; Chapter 3 (Witches' Party); pop-up ghosts on load and pointer-trail effects; `prefers-reduced-motion` handling |

### Shared work

Both members did these together:

- Brainstormed the theme, story, and chapter options
- Reviewed each other's code and merged changes
- Cross-browser testing (desktop and mobile) and bug fixing
- Writing this README and completing the submission template

> **Note:** Edit the GitHub usernames and the split above so it matches what each of you actually did before submitting.

## Running locally

Open `index.html` in a browser (or serve the folder with any static web server), click the gate, then press play on the audio player.

## Deployment

Upload the whole project folder, including `assets/`, to codd.cs.gsu.edu.

## Credits

- Audio: synthesized ambience (`assets/creepy-ambience.wav`). Swap in a properly licensed recording if desired.
- Fonts: Google Fonts.
