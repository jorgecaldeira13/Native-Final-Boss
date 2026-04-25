# Native Final Boss 🎮

> Defeat your non-native English. One challenge at a time.

A gamified English learning app powered by Claude AI. Built for non-native speakers who are tired of infantile language apps.

## What it is

- **Daily 3-round challenges** — logical games, grammar games, idiom challenges
- **Claude AI as the brain** — every exercise is generated in real time, adapted to your level and your mistakes
- **15 arcade mini-games** as rewards — Snake, Pong, Surf Run, Flappy Bird, and more
- **6 worlds** — The Briefing Room, The Lineup, The Court, The Pitch, The Feed, The Boss Door
- **Spaced repetition** — idioms come back at the right intervals
- **Pixel art aesthetic** — 8/16-bit arcade cabinet vibes

## How to run

Just open `index.html` in a browser. No build step, no dependencies.

It uses the Anthropic API directly from the browser. The API key is handled by the Claude.ai artifact environment.

> To run locally with your own API key, add your key to the fetch headers in the script.

## Stack

- Vanilla HTML/CSS/JS — single file, zero dependencies
- Claude API (`claude-sonnet-4-20250514`) for all exercise generation
- HTML5 Canvas for all arcade games
- Google Fonts (Press Start 2P + Rajdhani)

## Worlds

| World | Topics |
|---|---|
| 🏢 The Briefing Room | Marketing, copy, strategy, client emails |
| 🌊 The Lineup | Surf, outdoor, sport, weather |
| 🎾 The Court | Social, friends, banter, small talk |
| 💼 The Pitch | Negotiation, persuasion, selling ideas |
| 📱 The Feed | Slang, memes, internet English (unlocks Lv.5) |
| 💀 Boss Door | Advanced — weekly boss fight (unlocks Lv.10) |

## Arcade games

Snake · Pong · Breakout · Flappy Bird · Dodge · Memory Match · Colour Rush · Whack-a-Mole · 2048 Lite · Gravity Flip · Surf Run · Pixel Racer · Lava Rise · Simon Says · Bouncer

## Learning mechanics

1. **Your mistakes become your curriculum** — error patterns tracked and fed back into future exercises
2. **Spaced repetition** — idioms resurface at increasing intervals
3. **Mirror moment** — every session ends showing you what you got wrong and how a native would say it
4. **Weekly boss fight** — use 3 idioms from the week in natural context

---

Built with Claude. Deployed with ❤️ from Lisbon.
