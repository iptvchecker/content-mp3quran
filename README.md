# MP3Quran original resource mirror

Faithful copies of selected original MP3Quran Warsh and Qaloon recordings and
publisher timing responses. Publisher permission: https://www.mp3quran.net/ar/privacy
Original publisher: https://www.mp3quran.net/

This repository makes these Islamic resources available for reuse. It does not
claim ownership, close the material, edit recordings, or replace publisher credit.
Original bytes are retained. No Mishary Alafasy recording is included.

Audio is supplied as public GitHub release assets, one immutable dated release
per publisher recording ID. Each release retains SOURCE.json and CHECKSUMS.sha256.
Resource files are downloadable without account credentials. Publishing credentials
are private operator credentials and never belong in this repository or the app.

Publisher timing JSON lives under timings/READING-ID/2026-10-08/. These are exact
original responses, not app-corrected timing data. Known app-specific corrections
must be reviewed separately at integration; they are not applied to source mirrors.

Source versions, observed HTTP validators, retrieval dates, byte counts and SHA-256
hashes are recorded. Publisher publication dates are not invented when absent;
HTTP Last-Modified is kept as an observed validator, not assumed to be publication.

Later updates go into new dated snapshots and review branches. Never delete older
files or releases automatically because upstream removes or changes its resources.
Existing app-pinned releases must remain available. No app endpoint is changed here.
