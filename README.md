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

## Published snapshot — 2026-10-08

All seven recordings below contain 114 unchanged original MP3 files. All 798
MP3s total 11,277,368,909 bytes (11.28 GB); each release asset is below 2 GiB.
An independent post-publication audit matched the sizes and GitHub SHA-256
content digests of all 812 release assets, including provenance/checksum files.
Anonymous range downloads were also checked, including Yassin Yusuf (012).

[Download inventory with per-surah URLs, sizes and SHA-256 hashes](DOWNLOADS.json).

| Narration | Reciter | Original MP3s |
| --- | --- | --- |
| qalon | [الدوكالي محمد العالم](https://github.com/iptvchecker/content-mp3quran/releases/tag/qalon-dokali208-2026-10-08) | 114 |
| qalon | [علي الحذيفي](https://github.com/iptvchecker/content-mp3quran/releases/tag/qalon-hudhaify75-2026-10-08) | 114 |
| qalon | [محمود خليل الحصري](https://github.com/iptvchecker/content-mp3quran/releases/tag/qalon-husary270-2026-10-08) | 114 |
| warsh | [محمود خليل الحصري](https://github.com/iptvchecker/content-mp3quran/releases/tag/warsh-husary120-2026-10-08) | 114 |
| warsh | [العيون الكوشي](https://github.com/iptvchecker/content-mp3quran/releases/tag/warsh-koshi16-2026-10-08) | 114 |
| warsh | [عمر القزابري](https://github.com/iptvchecker/content-mp3quran/releases/tag/warsh-qazabri80-2026-10-08) | 114 |
| warsh | [ياسين الجزائري](https://github.com/iptvchecker/content-mp3quran/releases/tag/warsh-yassin14-2026-10-08) | 114 |

## Distinct source mirrors

| Publisher mirror | Published scope |
| --- | --- |
| [Quran SVG](https://github.com/iptvchecker/content-quran-svg) | Original repository history and 604 original v1.1.1 word-coordinate sidecars |
| [Tanzil](https://github.com/iptvchecker/content-tanzil) | Original Uthmani 1.1 text and notice |
| [Quranpedia](https://github.com/iptvchecker/content-quranpedia) | Original Asbab book 2919 archive and license |
| [QuranEnc](https://github.com/iptvchecker/content-quranenc) | Six original publisher SQLite ZIPs and 684 unchanged chapter responses |
| [Quran JSON](https://github.com/iptvchecker/content-quran-json) | Original Warsh/Qalun text, mapping and upstream attribution |
| [Al Quran Cloud](https://github.com/iptvchecker/content-alquran-cloud) | Original Pickthall and al-Muyassar responses and edition credits |
| This MP3Quran mirror | Seven complete recordings and 798 unchanged timing responses |

These are scoped mirrors, not a claim that every app resource is redistribution
cleared. EveryAyah and QuranFoundation resources remain outside this public
batch pending redistribution clearance. Two QuranEnc Muhtasar editions remain
pending required publisher version metadata. Original source rights and credits
continue to apply; availability alone does not mean public domain.

App integration, trust-key management and server failover are a separate phase.
The app does not yet use these mirrors. Original timing data is intentionally
unchanged; integration must preserve existing app timing corrections.
