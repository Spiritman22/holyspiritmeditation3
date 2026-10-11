Holy Spirit Meditation (72) — Part 3

This build keeps the existing 21 scene texts, 24 language options, on-demand translation/narration logic, playback controls and PWA shell.

Manuscript-specific art mapping: opening invocation; Glory; the first, second and third falls; the Crucifixion; bloodied Jesus on the Cross; crown of thorns; left hand, right hand and feet pierced by nails; the spear; the dead body of Jesus on the Cross for the silent/prayer sequences; the body illuminated by light; the Host above the chalice for the Eucharistic prayers; and the final light descending from heaven to earth.

Artwork is embedded in index.html so it displays without separate image requests. The artwork/ folder contains the same background images as reviewable files. Scene manuscript text and translation/narration implementation were preserved.

Language behavior: translations are fetched on first use and cached when browser storage is available; they are not all pre-embedded. Speech depends on voices supplied by the browser/device.

To run: serve this folder over HTTPS or localhost for full PWA/service-worker behavior, then open index.html. English entry key: am.

FIX v10: The start keyword is always 'am' as specified in the manuscript, regardless of selected interface language. Translation requests time out and narration can fall back to source text instead of waiting forever.
