# fika-art

## TLDR

Reusable line graphics for the Fika morning email.<br>
Headers, section glyphs and story illustrations give the email a consistent visual vocabulary.<br>
This repository holds image assets; it does not send the email or contain its private source material.

## The problem and approach

- Problem: an email needs its images on a public host that Gmail can reach.
- What it holds: header cups for sun, cloud and rain with a wind variant, 24 px section glyphs including weekday dots, and one 600 x 260 figure per story.

## Review and pick up the work

[Agent guide](AGENTS.md)

Start with the linked source, setup and evidence. Recorded demos and sample data keep their original scope; use the repository instructions for a fresh run.

Line graphics for Fika, a daily morning email. PNG at 2x, one blue (#3E5C76) on #F6F7F5.

- `marks/` the daily header cup. Sky is `sun`, `cloud` or `rain`; `-wind` bends the steam (max wind 30 km/h or more).
- `glyphs/` section glyphs, 24 px. `week-<day>` fills today's dot.
- `segments/` one figure per story, 600 x 260. Caption and source stay as live text in the email.

Public so Gmail's image proxy can fetch the files.

## License and data boundaries

This checkout has no root license file establishing general reuse rights. Data, provider responses, media, fonts and other third-party assets may have separate terms. Repository access alone does not grant rights to those materials. 
