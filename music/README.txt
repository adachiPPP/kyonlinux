DROP YOUR SONGS HERE
====================

The homepage (index.html) plays music and visualises it cava-style.

YOU CAN NAME YOUR FILES ANYTHING
--------------------------------

Edit the file  songs.json  (in this folder) and list your songs, one per line:

    [
      "myfavorite.mp3",
      "summer-tune.ogg",
      "anything.wav"
    ]

- The song of the day is picked automatically from the date
  (day-of-year % number of songs).
- The "next / prev" buttons cycle through the list.
- Songs that are listed but missing are skipped automatically.

NO songs.json? OLD WAY STILL WORKS
----------------------------------

Without the manifest the page falls back to looking for
music1.mp3, music2.mp3, ... (up to music16.mp3).

If no songs are found at all, the page plays a synthesized ambient
beat so the visualizer still works (until you drop songs in).
