# learn-bangla

A daily Bangla word and phrase, archived and browsable.

`bangla.json` is written automatically by the
[daily briefing](https://github.com/chrisb347/daily_email) workflow after each
morning's email. Nothing here is edited by hand.

Each entry:

```json
{
  "bangla": "ভালোবাসা",
  "phonetic": "bhalo-basha",
  "english": "love",
  "example_phrase": "আমি তোমাকে ভালোবাসি। — I love you.",
  "date_sent": "2026-07-19T11:04:22.101"
}
```

`index.html` is a static reader over that file — no build step, no dependencies.
