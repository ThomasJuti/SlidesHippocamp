# Hippocamp — pitch deck

Slides for Platanus Hack 26 (team-27, Bogotá). Single self-contained `index.html`,
no build step and no runtime dependencies beyond Google Fonts.

Live: https://thomasjuti.github.io/SlidesHippocamp/

## Presenting

| Key | Action |
|---|---|
| `→` `↓` `space` | Next slide |
| `←` `↑` | Previous slide |
| `Home` / `End` | First / last slide |

Scroll and trackpad swipe work too — the deck snaps one slide at a time.

Built for a dark room and a live stream: warm near-black ground, large type,
no thin light-on-dark hairlines that break up under compression.

## Exporting to PDF

Print the page (`⌘P`) with **landscape** orientation and background graphics on.
The print stylesheet drops the ambient canvas and paginates one slide per page.

## Editing

Everything lives in `index.html` — tokens at the top of the `<style>` block,
one `<section class="slide">` per slide. Add a slide and the progress spine
picks it up automatically.
