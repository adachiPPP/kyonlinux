# kyonlinux

an independent arch-based distribution designed with a focus on user-friendly accessibility and refined aesthetics. (CURRENTLY IN DEVELOPMENT)

support me on https://github.com/sponsors/adachiPPP (please 3;)

## the website

Everything lives in a single file: **`index.html`** — home, music player with a cava-style visualizer, gallery, wiki, credits and dev notes are all niri-style scrolling windows on one page. The old pages (wiki/credits/gallery/releases) redirect into their sections.

- **music**: drop songs into `music/music1.mp3`, `music2.mp3`, … (up to 16). The song of the day is picked from the date, ⏮/⏯/⏭ buttons cycle through whatever exists, and missing files are skipped. If no songs are found, a generative ambient beat keeps the visualizer alive. Keyboard: `space` play/pause, `←`/`→` prev/next.
- **visualizer**: cava-style spectrum bars + beat-reactive logo pulse (WebAudio AnalyserNode).
- **theme**: Jost (Futura-style) via Google Fonts, snow particles, aurora background.
- **donations**: fixed ♥ donations button in the top-right (GitHub sponsors link).
- **gallery**: carousel with ‹ › arrows, dots and auto-advance.
- **wiki**: live search bar that filters the accordions.
- The Turkish (`tr/`) and German (`de/`) sites are restyled to match (same theme, top nav, carousel + wiki search).
- **rotating jokes**: the italic line under the tagline cycles through the phrases in `humornotes.json` every 5 seconds — edit that file to add your own.

# people who helped me <3

SmyczyKox: tested the website a lot and recommended (by bothering me a lot) some extra things (day 1 guy) <3
waffle: made an ascii logo <3
