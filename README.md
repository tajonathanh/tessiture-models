# tessiture-models
Model artefacts (co-occurrence + ALS) for the Tessiture music recommender. Derived from ListenBrainz CC0 listen dumps; no personal data.

`models-v1.zip`: co-occurrence and ALS (256 factors, α 100) artefacts built 2026-10-26 from ListenBrainz incremental dump 2744 (CC0, https://listenbrainz.org). Every file's sha256 is in the zip's `manifest.json` and is checked at deploy. Contains no personal data: sessions are anonymous rows, tracks are "artist / title" keys.
