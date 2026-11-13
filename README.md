# Public reel media

Public hosting for **final** reel renders. Buffer pulls videos from **release asset URLs** (not the files on `main`).

| Brand | Source (private) | Release tag | File |
|---|---|---|---|
| Nanhe Facts | muditjuneja/nanhe-facts | `batch-YYYY-MM…` | `epNNN-final.mp4` |
| Pehle Ruko | muditjuneja/pehle-ruko | `pehle-ruko-YYYY-MM` | `scNNN-final.mp4` |

URL shape: `https://github.com/muditjuneja/nanhe-facts-media/releases/download/<tag>/<file>`

Pehle Ruko Buffer cover is the first frame (`thumbnailOffset` 0 ms — the hook).
