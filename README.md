# Mission Mode — A Self-Directed PM Growth Case Study

A self-initiated product management exercise: how would you grow daily-active
users for a major consumer app in India, where roughly one-in-six of the
platform's global users live but engagement lags significantly behind volume?

## TL;DR — The bet

**Mission Mode**: short, career-relevant English missions (interview prep,
workplace email, customer calls) targeted at the urban-intermediate-English
career-motivated segment who want functional career fluency, not gamified
streaks. A 60-day completion arc with three V1 missions and a clear V2 expansion
path.

## Live prototype

→ https://mission-mode-casestudy.vercel.app/mission_mode_prototype_embed.html

Six screens, keyboard-navigable, vanilla HTML/CSS/JS, iframe-safe.

> Note: the prototype is built in the visual and mechanical idiom of a popular
> gamified language-learning app to demonstrate how the proposed feature would
> integrate with familiar mechanics (points, streaks, leagues). It's a
> self-directed PM exercise, not affiliated with or commissioned by any company.

## How I approached it

1. **Segmentation** — disaggregated "India" into ~5 user archetypes; identified
   urban-intermediate-English career-motivated users as the highest-leverage
   segment for a DAU-led intervention
2. **JTBD** — the job is "feel competent in English at work," not "learn a
   language for fun" — implies missions, not lessons
3. **Mechanic design** — short missions over long courses; bite-sized contextual
   practice over abstract grammar drills; deadline-paced rather than infinite
4. **Metrics** — DAU/MAU lift, mission completion rate, day-7 / day-30 retention,
   willingness-to-pay signal as a V2 indicator
5. **V2 roadmap** — mission library expansion (industry-specific, negotiation,
   conflict English), graduation flow to standard track, discovery surface

## What's in this repo

| File | What it is |
| --- | --- |
| `mission_mode_prototype.html` | Standalone 6-screen prototype with keyboard nav |
| `mission_mode_prototype_embed.html` | Iframe-safe variant for deck embeds |
| `extension_mockup.html` | Browser-extension entry-point mockup |
| `completion_*.html` | End-of-mission celebration screens |
| `prototype_screenshots/` | Phone-frame Retina PNGs |

## Tech notes

Vanilla HTML/CSS/JS. No build step, no framework. Renders in any browser and
inside an iframe.

## Author

Akshey Walia · [LinkedIn](https://linkedin.com/in/aksheywalia) · [aksheywalia.in](https://aksheywalia.in)

## License

MIT
