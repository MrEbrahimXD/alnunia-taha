# alnunia-taha

Al-Nuniyya (al-Kāfiya al-Shāfiya) of Ibn al-Qayyim — recitation by **Sheikh Taha al-Fahd**.

Audio files are named by the **AlNunia app verse number** (`<verseNumber>.mp3`).
Each clip was matched to its bayt by **audio alignment** — faster-whisper
large-v3 transcription of every clip + a banded monotonic Needleman–Wunsch
against the poem text (see `tools/taha_align` in the app repo). This replaced the
earlier text-based alignment whose drift made verses play the wrong clip
throughout the poem.

- 5785 files. The 52 verses below are **absent**: Sheikh Taha's recited edition
  does not include them (the app's text edition has abyat he doesn't recite,
  e.g. the whole 1012–1045 section). Those numbers have no file (404 by design);
  the app skips them and never substitutes another reciter.
- See `verse_map.json` for the app-verse → Taha-segment mapping and the `gaps`.
- Source: Muyassir al-Mutoon app (Taha/noniya1–6 on niszak.com), stitched +
  audio-realigned.

Served via GitHub Pages: https://mrebrahimxd.github.io/alnunia-taha/<verseNumber>.mp3
