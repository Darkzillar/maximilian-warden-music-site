# Maximilian Warden Music Site

Enthalten:
- `index.html` – vollständige One-Page-Website
- `assets/covers/` – hier kommen deine JPG-Cover rein
- `assets/scroll-stop-animation.mp4` – hier kommt deine 16:9-Introanimation rein

## Dateien einfügen
Lege die Cover-Dateien mit diesen Namen in `assets/covers/`:

- acerbic.jpg
- asymptote.jpg
- bedingung.jpg
- cogito.jpg
- data.jpg
- everyday.jpg
- geometry.jpg
- hamster.jpg
- hand.jpg
- herz.jpg
- klangkaskaden.jpg
- like.jpg
- limbic.jpg
- meta.jpg
- mono.jpg
- mulligan.jpg
- musical.jpg
- ode.jpg
- pheno.jpg
- poly.jpg
- rhymes.jpg
- semantic.jpg
- times.jpg
- variable.jpg
- waking.jpg
- weltspartag.jpg
- zwischen.jpg

## Scroll-Stop-Animation
Lege deine MP4 hier ab:
`assets/scroll-stop-animation.mp4`

Die Seite startet beim ersten Scroll-Impuls die Intro-Animation und springt danach in die Album-Chronologie.

## Spotify aktivieren
In `index.html` gibt es ein Objekt namens `SPOTIFY_IDS`.

Dort kannst du pro Release eintragen:
- eine Album-ID mit 22 Zeichen
- einen Spotify-Link
- oder eine Spotify-URI wie `spotify:album:...`

Beispiele:
```js
const SPOTIFY_IDS = {
  "Weltspartag": "6rqhFgbbKwnb9MLmUQDhG6",
  "Klangkaskaden": "spotify:album:6rqhFgbbKwnb9MLmUQDhG6",
  "Rhymes and Reason": "https://open.spotify.com/album/6rqhFgbbKwnb9MLmUQDhG6"
};
```

## Nutzung
Die Seite funktioniert lokal direkt per Doppelklick auf `index.html`.
Sauberer ist es, sie auf deinen Webspace hochzuladen.

## Hinweis
Die Diskografie und Tracklisten wurden bereits in die Seite eingetragen.
