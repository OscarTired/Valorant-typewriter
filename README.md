<div align="center">
<h1>Valorant Typewriter</h1>

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Contributions welcome](https://img.shields.io/badge/contributions-welcome-ff4655?style=flat-square)

</div>

A lightweight typewriter effect inspired by the Valorant HUD, built with just plain HTML, CSS, and JS.

I put this together as a fun project to recreate that tactical, gamey feel—complete with rotating roles, glitch flashes, and a blinking cursor. Since it's all in a single file, it's super easy to poke around the code, tweak things, or just grab what you need for your own experiments.

> [!NOTE]
> Just a fan-made UI project by an amateur. Not affiliated with or endorsed by Riot Games at all. (Don't bother suing, I've got zero DIY budget anyway.)

## Quick Start

You do not need to install anything or run any build commands.

1. Clone this repository: `git clone https://github.com/OscarTired/Valorant-typewriter.git`
2. Open `index.html` in your favorite browser.
3. That is it. No frameworks, no headaches.

## Features

- Rotating typewriter text with typing and deleting states
- Glitch transition effect between phrases
- Animated cursor and progress bar
- Dot indicators synced with the active phrase
- Valorant-inspired HUD visual styling
- Single-file structure for quick editing and reuse
- No frameworks, no build tools, no dependencies beyond the browser

## Tech Stack

- HTML
- CSS
- JavaScript (Vanilla)

## Customization

You can personalize the effect directly inside `index.html`.

### Edit the rotating text
Update the `words` array to change the displayed labels and colors.

### Adjust the animation timing
Modify these constants to control the pacing:
- `TYPE_SPEED`
- `DELETE_SPEED`
- `HOLD_TIME`
- `PAUSE_BEFORE`

### Restyle the interface
Change the CSS custom properties in `:root` to tweak the color palette, glow, and overall mood.

## Project Structure

```text
.
├── README.md
└── index.html
```

## Why This Project

This demo is useful if you want to:

- Study a polished typewriter animation without a framework
- Reuse a stylish hero or intro effect in a portfolio or landing page
- Learn how timing, DOM updates, and visual feedback can work together
- Build on top of a compact, beginner-friendly vanilla setup

![valorant-typewriter](https://github.com/user-attachments/assets/5cbae68f-2381-4f9d-98eb-8bc90ab4cc4a)
