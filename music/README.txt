DROP YOUR SONGS HERE
====================

The homepage (index.html) plays music and visualises it cava-style.

Drop audio files named:
    music1.mp3, music2.mp3, music3.mp3, ... (up to music16.mp3)

- The song of the day is picked automatically from the date
  (day-of-year % number of songs found).
- The "next / prev" buttons cycle through whatever songs exist.
- Missing files are skipped automatically.
- If no songs are found at all, the page falls back to a
  synthesized ambient beat so the visualizer still works.

Formats supported by browsers: .mp3, .ogg, .wav, .m4a (rename to .mp3,
or edit TRACK_EXT in index.html if you prefer another extension).
