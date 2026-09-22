# Piano Simulator 1000 — playtests

Static, single-song builds of Piano Simulator 1000, shared with individual
testers by link. Each folder is one song and runs entirely in the browser:
no backend, no account, nothing to install. The front page (`index.html`)
lists every song and is regenerated whenever a song is built.

- The notation, the keyboard and the "generated piano" are produced
  automatically from a recording. They are test output, not arrangements, and
  are published unedited on purpose.
- The original recordings are **not** stored here. Each page embeds the song's
  YouTube video (privacy-enhanced mode) and follows its clock.
- Feedback stays in the tester's browser until they choose to copy, share or
  download it. Nothing is sent anywhere.

| folder | song |
|---|---|
| `silo-s2e4-outro/` | *Silo* Season 2 Episode 4 outro (music by Loney Dear), from a YouTube upload |
| `nier-automata-medley/` | *NieR:Automata* soundtrack medley, piano arrangement and performance by Animenz (music by Keiichi Okabe, Keigo Hoashi and Kuniyuki Takahashi), from the performer's YouTube upload |

## Credits and licences

- Piano sound: **Salamander Grand Piano** (Yamaha C5) by Alexander Holm,
  [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/) — browser subset,
  one velocity layer. See `*/samples/salamander/ATTRIBUTION.txt`.
- Notation: [OpenSheetMusicDisplay](https://github.com/opensheetmusicdisplay/opensheetmusicdisplay)
  (BSD-3-Clause), which renders with VexFlow (MIT).
- Audio scheduling: [Tone.js](https://github.com/Tonejs/Tone.js) (MIT).
- Interface: [React](https://react.dev) (MIT).
