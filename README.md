# fujirock

Unofficial single-page viewer for the **FUJI ROCK FESTIVAL '26** free live streams
on Twitch (Amazon Music — Channels 1/2/3 = `amazonmusicjp` / `amazonmusicde` / `amazonmusicuk`).

- One embedded Twitch player with channel switching + optional live chat
- Full 3-day timetable (Jul 24–26, all times **JST**)
- Real-time **ON NOW / Up next** detection computed in JST
- Day-colored theme (Fri red · Sat blue · Sun green), light + dark

Hosted at **https://miyagawa.co/fujirock/** via GitHub Pages.

Twitch requires the embed's `parent=` to match the host domain; the page sets it
from `location.hostname` at runtime, so it works on `miyagawa.co` and `localhost`.

## Local preview

Twitch won't load from `file://`. Serve over http:

```sh
python3 -m http.server
# open http://localhost:8000/
```

Schedule subject to change.
